# pdf2word
How to use A.I. to extract Persian texts from PDF

![screenshot](/sources/textpdf_to_text.png)


## Python Packages
- [Google Tesseract](https://github.com/tesseract-ocr/tesseract)
- [A Python wrapper for Google Tesseract](https://github.com/madmaze/pytesseract)
- [tqdm](https://github.com/tqdm/tqdm)
- [Pillow](https://github.com/python-pillow/Pillow)
- [pdf2image](https://github.com/Belval/pdf2image)
- [python-docx](https://github.com/python-openxml/python-docx)


## Installation:
``` bash
pip install -r requirements.txt
```

## Usage
Run `PDF 2 Word.ipynb`

``` python
pdf_to_word('./samples/sample-pdf-text.pdf', './samples/', 'fas')
```

## Supported versions/Pre-requisites.

| Python        |
| -------------:|
| 3.6           |
| 3.7           |
| 3.8           |

## License

Copyright (C) 2019, [Hooshvare Team](https://hooshvare.com/)
Licensed under the MIT license, see LICENSE file for details.