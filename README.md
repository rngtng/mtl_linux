Nabaztag:Tag Bytecodes (MTL) compiler for Linux and Mac OSX

# Requirements

Require 32 bits architecture.
On an Amd64 architecture you will need to install some components.

On Debian:

    apt install g++-multilib libc6-dev-i386

# Compilation

Simply:

    make

# Usage

## Simulator

Simply:

    ./mtl_simu

For full options:

    ./mtl_simu -h

## Compiler

    ./mtl_compiler [-s] source output
