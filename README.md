# jsonnet-101

## Installation

```sh
brew install jsonnet
```

## Example

```sh
jsonnet example/main.jsonnet --tla-str country="th" --tla-str env="dev"
```

## Testing

```sh
jsonnet example/tests/test_api.jsonnet
```

## Formatter

```sh
jsonnetfmt -i *.jonnet && jsonnetfmt -i *.libsonnet
```
