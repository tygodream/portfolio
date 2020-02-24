Needed:
- installed asciidoctor-pdf

To build the PDF:
- asciidoctor-pdf portfolio.adoc -a pdf-style=template/default-theme.yml

All images are stored in `img` folder.
Please make add new images only in `png` format - these are the original files.
From these `png` files smaller `jpeg` are created.

However the quality in all cases rests in the `png` files.
`jpeg` files might be lost, or downsampled to really low quality.
