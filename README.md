The dataset contains 52 filings from the US SEC EDGAR database. The named entity tags are hand annotated. 

The named entities are classified into 7 classes: Person, Court, Business, Government, Location, Legislation/Act, Miscellaneous (and the class "Outside" for non-named entities).
The "all.csv" contains the annotated filings, with 1 token on each line, followed by the named entity tag. The token and named entity tag is separated by a tab.

The "edgar_4.csv" contains the same data as "all.csv", but there are only 4 named entity classes: Person, Organization, Location and Miscellaneous. (Court, Business and Government combined into Organization, and Legislation/Act and Miscellaneous combined into Miscellaneous)




------------------------------------------------------------------------------------------------------------

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
