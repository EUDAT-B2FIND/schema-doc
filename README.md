# schema-doc
Documentation of B2FIND Metadata Schema

## build sphinx-doc
Clone schema-doc from EUDAT-B2FIND github:
```bash
git clone https://github.com/EUDAT-B2FIND/schema-doc.git
cd schema-doc
```
Build docs:
```bash
cd docs
rm -rf _build # optional for clean build
make html
```
Docs are built in folder `~/schema-doc/docs/_build` and can be opened with:
```bash
firefox _build/html/index.html
```     