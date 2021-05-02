# minigrep
Simple grep written for practice.

## Usage
* Takes `CASE_INSENSITIVE` env variable.

```
$ CASE_INSENSITIVE=1 minigrep <string_to_search> <file_location>
```
OR
```
$ export CASE_INSENSITIVE=1
$ minigrep <string_to_search> <file_location>
```
* Case insensitive argument can be passed through CLI as well.

`0` for case-sensitive and `1` for case-insensitive
```
$ minigrep <string_to_search> <file_location>
```