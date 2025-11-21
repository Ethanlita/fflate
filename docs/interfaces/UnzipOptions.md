[**fflate**](../README.md)

***

# Interface: UnzipOptions

Options for expanding a ZIP archive

## Extended by

- [`AsyncUnzipOptions`](AsyncUnzipOptions.md)

## Properties

### decodeFilename?

> `optional` **decodeFilename?**: [`FilenameDecoder`](../type-aliases/FilenameDecoder.md)

A custom decoder for filenames when UTF-8 flag is not set.
By default, Latin-1 (ISO-8859-1) encoding is used.
You can provide a custom decoder to handle other encodings like GBK, Shift-JIS, etc.

***

### filter?

> `optional` **filter?**: [`UnzipFileFilter`](../type-aliases/UnzipFileFilter.md)

A filter function to extract only certain files from a ZIP archive
