# anywidgetinstruments.github.io

Landing page of the AnywidgetInstruments organization, published at
<https://anywidgetinstruments.github.io/>. The documentation of each project is
published by its own repository under a path of this site.

The site is built with MkDocs Material and deployed by the Docs workflow, as
the other sites of the family. Its images come from the visual identity in
[AnywidgetInstruments/.github](https://github.com/AnywidgetInstruments/.github/tree/main/brand),
fetched at build time (`docs/brand/` is not committed). To build it locally:

```bash
git clone --depth 1 https://github.com/AnywidgetInstruments/.github /tmp/awi-brand
cp -r /tmp/awi-brand/brand docs/brand
pip install "mkdocs>=1.6,<2" "mkdocs-material>=9.5"
mkdocs serve
```
