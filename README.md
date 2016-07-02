# envato-license-check

This is a command line client Envato API license validator.

## Getting Started

*  Install with npm: `npm install -g envato-license-check`
*  Run it with `envato`

### Initial Setup
When running the first time (or if you didn't create a config file), it will ask you for your Envato username and API Key and a new config file will be created in `~/.envato-cli.json` with this data. If you want you can create or modify this file manually.

## Usage

There is only one main command `check [license_id]` if no command is provided help is shown:

```
  Usage:  [options] [command]


  Commands:

    check [env]  Validate the license by id

  Options:

    -h, --help     output usage information
    -V, --version  output the version number

```

## License

Copyright (c) 2014 Miguel Mich  
Licensed under the MIT license.