# 激情燃烧的岁月

省建一公司文集

## Build HTML on Arch Linux

```
sudo pacman -S asciidoctor
cd docs
asciidoctor -a data-uri book.adoc
firefox book.html
```

## Build PDF on Arch Linux

```
sudo yay asciidoctor-pdf
asciidoctor-pdf book.adoc
```

Note:

Font files in folder ./docs/themes are downloaded from:
from [fonts of asciidoctor-pdf](https://github.com/asciidoctor/asciidoctor-pdf/tree/main/data/fonts)
and [Noto Sans Variable Fonts for CJK](https://github.com/googlefonts/noto-cjk/tree/main/Sans#ttf).

See [Create a CJK Theme](https://docs.asciidoctor.org/pdf-converter/2.0/theme/cjk/)
for details.
