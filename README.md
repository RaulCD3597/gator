# Gator

gator is a CLI application that allows to aggregate RSS
feeds. In order to use install and run gator you need
to make sure you have postgresql and go installed.

## Installation

To install gator run:

```bash
go install github.com/RaulCD3597/gator
```

## Configuration

To run gator you need to setup a configuration
file at `~/.gatorconfig.json`. The base content should be:

```json
{
  "db_url": POSTGRES_CON_STRING
}
```
