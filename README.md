# Tissue Engineering Patent Analysis

[![DOI](https://zenodo.org/badge/178113823.svg)](https://zenodo.org/badge/latestdoi/178113823)

## Data Source

Patent data related to tissue engineering is obtained from The Lens, an online patent search service, on Sept 28th 2018 using the following search string:

`abstract:("tissue engineering") OR abstract:("engineered tissue") OR abstract:"organoid" OR abstract:"organoids" OR abstract:"bioprinting" OR abstract:"bio-printing" OR abstract:("tissue constructs") OR abstract:("tissue construct") OR abstract:("in vitro tissue") OR abstract:("in-vitro tissue") OR abstract:("invitro tissue")`

[Lens.org Search](https://www.lens.org/lens/search)

The search results are then downloaded as a CSV file, named `lens_data.csv` in this folder.

## Analysis

The data is then analyzed using topic modelling, as demonstrated in the Jupyter notebook available in this repository.

## LICENSE
The MIT License (MIT)

Copyright (c) 2019 UBC BioFoundry

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

