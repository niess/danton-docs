# API documentation for the DANTON library
( **D**ec**A**yi**N**g **T**aus fr**O**m **N**eutrinos )

## Description

This is an HTML documentation of the [DANTON][DANTON] library API. The [latest
build](https://niess.github.io/danton-docs) is available from GitHub pages.
The documentation is automatically generated from a
[Docurium](https://github.com/niess/docurium) fork.

## Usage

Clone the present repository, e.g. as:
```bash
cd danton && git clone https://github.com/niess/danton-docs.git docs
```
Then one can navigate the local content by directing a browser to the
[docs/index.html](docs/index.html) file. Note that with some browsers, e.g.
chrome, you'll need to explicitly serve the file using a local HTTP server.
For example, using Python:
```bash
cd docs/docs
python -m SimpleHTTPServer 8000
```
Then direct your browser to localhost:8000.

## License

The DANTON library is under the **GNU LGPLv3** license. See the provided
[LICENSE](LICENSE) and [COPYING.LESSER](COPYING.LESSER) files.

[DANTON]: https://github.com/niess/danton
