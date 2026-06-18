# Ramalama Workshop

## Table of Contents

- [Ramalama Workshop](#ramalama-workshop)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Running your first model](#running-your-first-model)
  - [Agents with Ramalama](#agents-with-ramalama)
  - [Stop Ramalama](#stop-ramalama)
  - [Next Steps](#next-steps)

## Installation

### Universal Install Script (Linux and macOS)
The easiest way to install RamaLama is using the universal install script:
```bash
curl -fsSL https://ramalama.ai/install.sh | bash
```
### Fedora
On Fedora systems, you can install RamaLama directly from the official repositories:
```bash
sudo dnf install ramalama
```
### PyPI (All Platforms)
RamaLama is available on PyPI and can be installed using pip:
```bash
pip install ramalama
```
### Verify Installation
After installation, verify that RamaLama is working correctly:
```bash
ramalama version
```

## Running your first model

Pull your first model: 
```bash
ramalama pull smollm:135m
```

Run a model: 
```bash
ramalama run smollm:135m
```

Explore available commands: 
```bash
ramalama --help
```

### Other models you can download and run

```bash
ramalama info --shortnames
```

```bash
ramalama inspect smollm:135m
```

## Agents with Ramalama

```bash
ramalama sandbox opencode --thinking=off smollm:135m
```

```bash
ramalama sandbox goose --thinking=off smollm:135m

```

## Stop Ramalama

```bash
ramalama stop --all
```

## Next Steps

- [Ramalama Containers](https://ramalama.ai/docs/commands/ramalama/containers)
- [Ramalama Configuration](https://ramalama.ai/docs/configuration/conf)
- [Ramalama RAG](https://ramalama.ai/docs/commands/ramalama/rag)
