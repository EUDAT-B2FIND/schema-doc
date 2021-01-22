# schema-doc
Documentation of B2FIND Metadata Schema
The B2FIND Metadata schema can be found online under the following link:
https://eudat-b2find.github.io/schema-doc/index.html 

## build sphinx-doc
Clone schema-doc from EUDAT-B2FIND github:
```bash
git clone https://github.com/EUDAT-B2FIND/schema-doc.git
cd schema-doc
```
Build docs:
```bash
rm -rf _build # optional for clean build
make html
```
Docs are built in folder `~/schema-doc/_build` and can be opened with:
```bash
firefox _build/html/index.html
```     