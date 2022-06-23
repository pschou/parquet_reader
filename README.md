# parquet2csv

A tool to convert Parquet files into CSV files.

## Usage

```
$ ./parquet2csv -h
Parquet Reader.
Usage:
  parquet_reader -h | --help
  parquet_reader [--only-metadata] [--no-memory-map] [--json]
                 [--print-key-value-metadata] [--columns=COLUMNS] <file>
Options:
  -h --help                     Show this screen.
  --print-key-value-metadata    Print out the key-value metadata [default: false]
  --only-metadata               Stop after printing metadata, no values.
  --no-memory-map               Disable memory mapping the file.
  --json                        Format output as JSON instead of text.
  --columns=COLUMNS             Specify a subset of columns to print, comma delimited indexes.
```
