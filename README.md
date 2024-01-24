# astro-thesis

A personal thesis template that mimics Astronomy&Astrophysics citation design.


The citation file `aa_url.bst` was taken from [yangcht's repository](https://github.com/yangcht/AA-bibstyle-with-hyperlink), and it does its job well, but the `inproceedings` function is modified.

The template contains dummy text with a reasonable structure, and a sample Figure, Table and code Listing.

My customizations can be summarized as:
* `\intent` command to provide margin comments, that can be deactivated by `\visibleintentfalse`
* Figure and table captions at 90% of the textwidth
* Line 1300 of the `aa_url.bst` file, deleteing the `adsurl make.href.hyperref` call to prevent errors with my bib file.

## Licensing

Sample figures include data from the [OGLE project](https://ogle.astrouw.edu.pl/main/OGLEIV/mosaic.html).

