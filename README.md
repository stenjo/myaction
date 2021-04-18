# myaction
Testing creating actions

Trying to learn how to create a reusable action for github actions

## Inputs

### `Trying out creating actions`
**Required** The name of the person to greet. Default `"World"`

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/myaction@v1
with:
  who-to-greet: 'Mona the Octocat'