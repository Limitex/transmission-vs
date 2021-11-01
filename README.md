# Forked from [depler/transmission-vs](https://github.com/depler/transmission-vs)

# Transmission cli for Windows

## Changes

1. Delete `daemon.c` from project.
2. Add file `cli.c` to project.  [Sauce](https://github.com/transmission/transmission/blob/3.00/cli/cli.c)

## Build

Build to Release

## Run
`./transmission.exe -w "Destination path" -u 0 "uri"`
