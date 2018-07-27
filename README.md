# hue-cli-extended

[![NPM version](https://img.shields.io/npm/v/@weasnerb/hue-cli-extended.svg)](https://www.npmjs.com/package/@weasnerb/hue-cli-extended)
![Node version](https://img.shields.io/badge/node-%3E%3D5.0.0-brightgreen.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

> Simple command line interface for Philips Hue.

## Installation

```bash
npm install -g @weasnerb/hue-cli-extended
```

### Usage

```text
Usage: hue [setup|scene|on|off]

Commands:
  setup            Configure hue bridge or show current config
    -l, --list     List bridges on the network
    -i, --ip       Set bridge ip (use first bridge if not specified)
    --force        Force setup if already configured

  g, group <name>

  s, scene <name>  Activate scene starting with <name>
    -l, --list     List scenes, using <name> as optional filter
    -m, --max <n>  Show at most <n> scenes when listing (10 by default)
    -c, --create   Create scene <name> using current lights state

  i, on            Switch all lights on  
  o, off           Switch all lights off
```
