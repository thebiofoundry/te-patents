# Tissue Engineering Patent Analysis

## Data Source

Patent data related to tissue engineering is obtained from The Lens, an online patent search service, on Sept 28th 2018 using the following search string:

`abstract:("tissue engineering") OR abstract:("engineered tissue") OR abstract:"organoid" OR abstract:"organoids" OR abstract:"bioprinting" OR abstract:"bio-printing" OR abstract:("tissue constructs") OR abstract:("tissue construct") OR abstract:("in vitro tissue") OR abstract:("in-vitro tissue") OR abstract:("invitro tissue")`

[Lens.org Search](https://www.lens.org/lens/search)

The search results are then downloaded as a CSV file, named `lens_data.csv` in this folder.

## Analysis

The data is then analyzed using topic modelling, as demonstrated in the Jupyter notebook available in this repository.