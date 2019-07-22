# UK Arms Export Data

A list of all controlled goods approved or refused for export from the UK since January 2008.

The data is also available via a searchable application on the [Campaign Against Arms Trade](http://www.caat.org.uk/resources/export-licences) website.

Source data from the [Strategic Export Controls database](https://www.exportcontroldb.berr.gov.uk/eng/fox) of the UK Department for Business, Innovation and Skills.


## Included Files

-   *items.csv* - Items approved, revoked or refused for export to specific countries
    -   `known_revoked` column indicates that the licence was later revoked even though the date of revocation is not known
    -   `military` indicates whether the items are considered military or not, though this is not always known
-   *values.csv* - Values in GBP, and rating codes of goods approved for export to specific countries
-   *incorporation-destinations.csv* - Final destination countries for items incorporated into overseas equipment for onward export
-   *trade-sources.csv* - Source countries of items transiting the UK from a source country to a destination country
-   *refusal-criteria.csv* - Reasons given for the refusal of licence applications
-   *ratings.csv* - Explanations of rating codes, and whether they are considered "military" or "dual-use"
-   *footnotes-region.csv* - Footnotes applied to regions in the source documents
-   *footnotes-licence-item.csv* - Footnotes applied to items in licences in the source documents


## Cross referencing

Several files contain a column named "licence_id" which is unique for each licence. This allows them to be cross-referenced.


## Caveats

Due to ambiguity in the source documents from which these data were compiled, the following columns may include some inaccuracies.

-   Refusal criteria may contain some false-positive matches.
-   Source and destination countries may contain some false-positive matches.
-   Low price values may be inaccurate by one or two pounds.


## Feedback

Contact [data@caat.org.uk](mailto:data@caat.org.uk) with any comments, questions or requests for specific data or alternative formats.

