# octo-exp-orb

Experimental orb for working with the Octopus CLI. This orb is provided as-is, with no support available.

Email circleci@octopus.com if you have questions about the orb.

This is a proof of concept orb for integrating CircleCI and Octopus Deploy.

The orb exposes the following functions from the Octo CLI: build-information, create-release, deploy-release, pack, promote-release, and push.

## Limitations

`build-information` does not include commits or work-items.

Providing parameters multiple times to a command (--package on `create-release` for example) is not supported.

The commands have to be run on the Bash shell.

## Usage

See the [octo-exp orb page](https://circleci.com/orbs/registry/orb/octopus-samples/octo-exp#usage-examples) for usage examples.
