# testing-actions
A public repository that will be used to test actions.

# Hello world docker action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: alberto-hyperion/testing-actions@v1
with:
  who-to-greet: 'Alberto'
