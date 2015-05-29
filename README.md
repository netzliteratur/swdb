# swdb
A software database, linking file types to supporting programs. File types are
tagged with PRONOM's unique id (PUID)
(http://apps.nationalarchives.gov.uk/PRONOM/Default.aspx), tags are
identical to PREMIS v2.2 (http://www.loc.gov/standards/premis/), except swYear, swSupportedFormats and swSupportedFormat.
# Workflow
A corpus of example files is processed with FIDO (http://openpreservation.org/technology/products/fido/) to determine the PUID. In a second step the files are rendered/opened/processed/edited on different operating systems with the listed software products. If it succeeds, the quality is rated. For more information see the comment section in swdb.xml

As swdb pursues a generalized approach, the lowest quality value
determines the quality value of identical file types in identical environments.

