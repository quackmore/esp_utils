# ESP8266 upload tool [for ESPBOT]

This is a bash script to upload files to a ESP8266 device running [ESPBOT](https://github.com/quackmore/espbot_2.0).

## Summary

The command line takes three parameters:
1)the file name
2)the device IP address
3)the --verbose option (optional)

Files with extension .html or .js are changed before uploading:
1)size is compressed removing comments and blank spaces at the beginning of the lines
2)a file version is stated (invoking git) and appended at the beginning of the file

## License

The utils come with a [BEER-WARE] license.

Enjoy.
