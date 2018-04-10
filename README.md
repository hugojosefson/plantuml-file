# plantuml-file

Converts a plantuml file into an svg file.

Uses docker image [think/plantuml](https://hub.docker.com/r/think/plantuml/).

## Prerequisites

 * Docker

## Usage examples

Convert `examples/bob-hello-alice.plantuml` to `examples/bob-hello-alice.svg`:

```bash
./plantuml-file examples/bob-hello-alice.plantuml           
```

Convert `examples/*.plantuml` to `examples/*.svg`:

```bash
find examples -name \*.plantuml -exec ./plantuml-file {} \; 
```

## TODO

 * Require correct number of argument(s)
