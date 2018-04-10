# plantuml-file

Converts a plantuml file into an svg file.

Uses docker image [think/plantuml](https://hub.docker.com/r/think/plantuml/).

## Prerequisites

 * Docker

## Usage

```bash
./plantuml-file <filename.plantuml>
```

Creates and writes to the same filename, but with an `.svg` extension.

### Usage examples

Create `examples/alice-hello-bob.svg`:

```bash
./plantuml-file examples/alice-hello-bob.plantuml           
```

Create `examples/*.svg`:

```bash
find examples -name \*.plantuml -exec ./plantuml-file {} \; 
```
