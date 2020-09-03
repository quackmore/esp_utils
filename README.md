# Tools for ESP8266 and ESPBOT

## ESP8266 upload tool [for ESPBOT]

This is a bash script to upload files to a ESP8266 device running [ESPBOT](https://github.com/quackmore/espbot_2.0).

The command line takes three parameters:

- the file name
- the device IP address
- the --verbose option (optional)

Files with extension .html or .js are changed before uploading:

- size is compressed removing comments and blank spaces at the beginning of the lines
- a file version is stated (invoking git) and appended at the beginning of the file

## JS minifier

This is a bash script to minify JS scripts an update the reference into the HTML files that use the script.

The list of the files HAS to be customised according to the projects.

## License

The utils come with a [BEER-WARE] license.

Enjoy.
