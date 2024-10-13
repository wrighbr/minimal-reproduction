# Unresolved alias - yaml files #31902

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

Renovoate fails with the error `Unresolved alias (the anchor must be set before the alias):` due to Pull Reqest [refactor: use yaml instead of js-yaml for parsing YAML files #31336](https://github.com/renovatebot/renovate/pull/31336)
Its unable to parse yaml files with used archors example here https://github.com/wrighbr/minimal-reproduction./blob/main/helmfile.yaml#L16

## Expected behavior

Renovate should be able to parse the yaml files an igorne `unused anchors`

## Link to the Renovate issue or Discussion

[Put your link to the Renovate issue or Discussion here.](https://github.com/renovatebot/renovate/discussions/31902)
