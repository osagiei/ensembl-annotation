# ensembl-annotation

## Running perltidy
Before commiting to this repository please run the command below to ensure the Perl source files are formatted correctly.
```
cd /path/to/ensembl-annotation/
find . -name '*.p[l|m]' -exec perltidy -pro=perltidyrc  -b {} \;
```
