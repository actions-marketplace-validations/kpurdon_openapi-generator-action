# openapi-generator-action

A GitHub action for the [OpenAPI Generator](https://openapi-generator.tech/).

## Inputs

### `args`

**Required** The same arguments you would pass to `openapi-generator`.

## Example usage

```yaml
uses: actions/openapi-generator-action@v1
with:
  args: "generate -i spec.yaml -g typescript-fetch -o ./generated-code"
```
