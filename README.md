# json2yaml - convert JSON to YAML on command line

A trivial script to convert JSON to YAML.

# Usage

Pipe to stdin:

    echo '{"foo": 42}' | json2yaml

Or pass in a file parameter:

    json2yaml /path/to/baz.json

The corresponding YAML will be written to standard out.

# Installation

Requires Python 3 and PyYAML.

TODO: Make this easier for someone who's not already an expert in Python to install

For now, you must either create a virtual environment (using
requirements.txt), or install PyYAML some other way onto the
system. Once that's done, you can simply invoke json2yaml on the
command line.

# Author

Aaron Maxwell - http://redsymbol.net

# License

Public domain

