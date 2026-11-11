# Dataset notes

`MIT_AI_ARTICLES.csv` is the user-supplied dataset used in the notebook. It contains 314 rows and 10 original columns. Two columns are CSV export indices, leaving eight article metadata/content fields. Dates span 20 December 2023 to 19 August 2025.

Article URLs point to MIT News. The supplied files do not document the collection method, collection date, sampling criteria, or redistribution license. No scraping script is included. The article bodies are stored in the CSV but are not scored by this analysis.

`paper_link` contains the literal placeholder `Not provided / no paper was made` in some rows; this is not represented as a null value. Zero nulls therefore does not imply complete bibliographic metadata.

Before publishing the full CSV, establish its redistribution terms. If it cannot be shared, omit it from the public repository and retain this file to explain the schema and required local location. No license for third-party article content is granted by this project.

| Field | Meaning |
| --- | --- |
| title | Article headline |
| author | Byline |
| publication_date | Display publication date |
| datetime | Timestamp with UTC offset |
| summary | Article summary |
| body | Full article text; not scored |
| paper_link | Research paper URL or placeholder |
| url | Source article URL |
