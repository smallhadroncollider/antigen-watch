# watch

A watch script for Antigen

## Install

Include the following in your `.zshrc`:

```
antigen bundle smallhadroncollider/antigen-watch
```

## Config

There two settings that should be set in `.watchrc`:

- `command`: the command to run (e.g. `make watch`)
- `interval`: how frequently (in seconds) the command should run - must be a value between 0.1 and 5
