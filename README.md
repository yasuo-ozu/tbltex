# tbltex --- latex table generator

This program generates latex table from tsv file.

## global options

- `--document` or `-d` ... create entire latex-formated file

## column options

repeat the following options to create multiple columns.

- `--file` or `-f` ... input file (tsv) (needed)
-  N(number) ... use the Nth column of the input file (default: 0, 1, 2, ...)
- other string ... create new colum titled with the string

