# cas-notarize-docker-image-github-action

GitHub action that uses the **[cas](https://github.com/codenotary/cas)** tool to notarize and generate a SBOM for docker images.

## How to use it

Have a look in the provided [example workflow](.github/workflows/example.yml).

:bulb: The underlying cas Docker image can also be run directly (an example is also provided in the same [example workflow](.github/workflows/example.yml)). This way one can **specify any cas** :boom: flag, not just the ones exposed by the GitHub action.

👉 [This link](https://github.com/marketplace?type=actions&query=publisher%3Acodenotary+) lists all the other GitHub actions that are available from CodeNotary.
