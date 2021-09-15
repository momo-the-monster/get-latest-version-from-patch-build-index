# Get PATCH Build Version Action

This action returns the latest version in a Builds Index file as a string when using [PATCH](https://github.com/emanzione/PATCH)

## Inputs

## `pathToBuildsIndex`

The path to the actual builds_index.json file, defaults to "PATCHWorkspace/Builds/builds_index.json"

## Outputs

## `version`

The latest version found, as a string

## Example usage

uses: actions/get-latest-version-from-patch-build-index@v0.1
with:
    pathToBuildsIndex: 'PATCHWorkspace/Builds/builds_index.json'