# merge-pdf

This is a simple CLI PDF merger.
It was rather quickly thrown together when I needed one and basically is the "Merge PDF" example from ![lopdf](https://github.com/J-F-Liu/lopdf) slightly adapted and with a simple CLI.

This was more of a try to get a little familiar with rust and is mostly "public" so I can quickly find it if I ever need it again.
It basically does the same thing as e.g. pdfunite from poppler-utils which I didn't know of at that time.

Build and install it like any simple rust package with cargo.

## Usage

```sh
merge-pdf 1.pdf 2.pdf ...
```

You can optionally specify the output file name using `-o filename`, if omitted the default is `merged.pdf`.
