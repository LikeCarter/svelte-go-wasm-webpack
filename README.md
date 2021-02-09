# Go WASM Template in Svelte
A quick start template to compile a Golang to WebAssembly for use with a Svelte front end. It is presented as a simple web app which shows how it all fits together.

This uses a fork of the golang-wasm-async-loader webpack plugin in order to work with Golang *v1.16*.

## Current Status

This is a working fork of Mark Hughes version for `go` v1.16.

## Setup

### Pre-requisites
Tested using `go` v1.16, `node` v14.14 and `yarn` v1.22.

### Clone the plugin and this template

If you have `node` and `yarn`, on Linux you should be able to just copy the following and paste it into your terminal.
``` bash
# Make sure GOROOT and GOPATH are set in the terminal, for example:
export GOROOT=`go env GOROOT`
export GOPATH=`go env GOPATH`

# Get the app template
git clone https://github.com/LikeCarter/svelte-go-wasm-webpack
cd svelte-go-wasm-webpack
yarn && yarn build

# If all looks good, start the app
yarn dev
# Open app in the browser by visiting localhost:5000
```

## LICENSE

Everything is GPL3.0 unless otherwise stated. Any contributions are accepted on the condition they conform to this license.

See also ./LICENSE