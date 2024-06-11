# bgt60-configurator-cli

The BGT60 configurator tool is a command line tool
that allows to convert the radar configuration saved
as a JSON file to register values. These register values
can then directly be written to a BGT60TRxx radar sensor.

The source code is also available as part of the Radar SDK.
For convenience the tool is provided here as executable.

Usage:
$ bgt60-configurator-cli -c path/to/config.json

For further refer to the help page:
$ bgt60-configurator-cli -h