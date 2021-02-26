# openapi-generator-action

A GitHub action for the [OpenAPI Generator](https://openapi-generator.tech/).

## Inputs

### `args`

**Required** The same arguments you would pass to `openapi-generator`.

## Example usage

```yaml
- name: OpenAPI Generator Action
  uses: kpurdon/openapi-generator-action@v0.0.1
  with:
      args: "generate -i spec.yaml -g typescript-fetch -o ./generated-code"
```
