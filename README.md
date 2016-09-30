# rpigo
A quick script for cross compiling Go to the Raspberry Pi. Pronounced "Arpeggio" 

Totally assumes you're running Raspian or some other Linux distro on the RPi.

## Requirements

- Go 1.5 or greater
- Some POSIX-compliant operating system
- Targets RPi 2 or greater

## installation

### easy mode

- Clone this repo
- run `./install.sh`

### slightly less easy mode

- Download `rpigo`
- Copy `rpigo` to `/usr/local/bin`

## usage

Let's say you want to cross compile `main.go` for the Raspberry Pi.

- `rpigo main.go`
- copy `main-rpi` to your Raspberry Pi
- PAT YERSELF ON THE BACK

