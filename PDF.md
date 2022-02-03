## Concat all first pages of multiple PDFs
```gs -dFirstPage=1 -dLastPage=1 -dNOPAUSE -dBATCH -sDEVICE=pdfwrite -sOutputFile=out.pdf *.pdf```
