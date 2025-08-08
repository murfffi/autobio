# Notes

Extract images from PDF with:

```sh
mkdir images
find . -iname '*.pdf' -exec pdfimages -all '{}' 'images/{}' \;
```
