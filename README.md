# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a perosn to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you

## Example usage

```yaml
uses: actions/hello-world-javscript-action@e76147da8e5c81eaf017dede5645551d4b94427b
with:
    who-to-greet: 'Mona the Octocat'
```