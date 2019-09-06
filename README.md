# How much does a file weigh?

Based on [IBM's research](http://gizmodo.com/5875674/ibm-figures-out-how-many-atoms-it-takes-to-hold-a-bit-hint-its-12), one bit takes between 1 and 62.5 million iron atoms on a normal hard disk. This application tries to estimate a medium weight for the input file, based on a value of `(62.5 + 1) / 2` = 31.75 million iron atoms per bit.

## Usage

    cc -o fileweight fileweight.c
    ./fileweight some-file

## License

Licensed under the terms of the [WTFPL v2](http://wtfpl.net/txt/copying).
