# CSS Test EPUB

These are EPUBs generated with help from Claude to test out CSS parsing capabilities in CrossPoint Reader for XTEInk devices.

## Building

Clone this repo. Then, from the root directory, run:

```bash
cd general-test-epub && rm -f ../general-test.epub && zip -0 ../general-test.epub mimetype && zip -r9 ../general-test.epub META-INF OEBPS && cd ../
```

or for the very large CSS test EPUB:

```bash 
cd very-large-css-epub && rm -f ../very-large-css.epub && zip -0 ../very-large-css.epub mimetype && zip -r9 ../very-large-css.epub META-INF OEBPS && cd ../
```

