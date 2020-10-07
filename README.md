# Shutdown Controller Config
## ARGS spec
ACTION can be none, shutdown, or awake
DATE and/or MILITARY TIME|ACTION ie 2020/10/01 13:00|shutdown or 14:00|none or 2020/10/02|awake

## Config lines
Line 1 is default config; Unlike other lines, default config does not start with any device name; it only contains one or more ARGS
Everyline after Line 1 must start with device name (lower case) followed by colon.
Will disregard content after lastIndex dash (ie NAME-IGNOREME); One or more ARGS follow after colon.
