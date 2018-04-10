# plantuml-file

Converts a plantuml file into an svg file.

Uses docker image [think/plantuml](https://hub.docker.com/r/think/plantuml/).

## Prerequisites

 * Docker

## Usage examples

Convert `examples/alice-hello-bob.plantuml` to `examples/alice-hello-bob.svg`:

```bash
./plantuml-file examples/alice-hello-bob.plantuml           
```

Convert `examples/*.plantuml` to `examples/*.svg`:

```bash
find examples -name \*.plantuml -exec ./plantuml-file {} \; 
```

## TODO

 * Require correct number of argument(s)
