# tbltex --- latex table generator

This program generates latex table from tsv file.

## installation
```
sudo npm install -g tbltex
```

## global options

- `--document` or `-d` ... create entire latex-formated file

## column options

repeat the following options to create multiple columns.

- `--file` or `-f` ... input file (tsv)
- `--sort` .. specify one of uUdD to do sorting (uppercase is stronger)
- `--resolution` ... specify resolution. also `X.Y` type string is allowed.
-  N(number) ... use the Nth column of the input file (default: 0, 1, 2, ...)
- other string (required) ... create new colum titled with the string

if no files are specified with the column, stdin will be used.

## license
MIT

