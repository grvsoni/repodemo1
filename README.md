# Application Demo 1

This is a minimal Vue.js application with a single page that displays:

`This is Application Demo 1`

## Prerequisites

Install the following on both Mac and Linux:

- Node.js 20.x (or newer LTS)
- npm (usually included with Node.js)

### macOS (Homebrew)

```bash
brew install node@20
```

### Linux (Debian/Ubuntu)

```bash
sudo apt-get update
sudo apt-get install -y nodejs npm
```

## Install dependencies

```bash
npm install
```

## Run tests

```bash
npm run test
```

## Build the application binary/bundle

Build production output:

```bash
npm run build
```

The build output is generated in `dist/`.

To package a distributable artifact for macOS:

```bash
tar -czf repodemo1-mac.tar.gz dist
```

To package a distributable artifact for Linux:

```bash
tar -czf repodemo1-linux.tar.gz dist
```
test pr4
