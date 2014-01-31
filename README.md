# pfixer

A simple cli tool to prefix and postfix content in files. This is espeically useful if you require to paste content into the comments section of source code.

## CLI

Asume you need the content 

    This is really useful content.
    I would like to have this in my source files

Just run

    $ prefixer -i -p ' * '
    paste your text here
    CTRL-C

This will output:

     * This is really useful content.
     * I would like to have this in my source files


## File input

Just run

    $ prefixer -f ./myfile -p ' * '

## Help

    $ pfixer -h
    prefix and postfix text input from cli or files.
    Usage: node ./pfixer
    
    Options:
      -f, --file     Load a file
      -i, --input    input from cli
      -p, --prepend  text that will be prepended
      -a, --append   text that will be appended
      -h, --help     outputs this help

## Installation

    npm install -g pfixer

# Author

 * Christoph Hartmann <chris@lollyrock.com>

# License

MIT
