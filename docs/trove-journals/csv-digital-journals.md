---
title: CSV formatted list of journals available from Trove in digital form
description: This file provides metadata of 7,269 periodicals that are available from Trove's journal zone in digital form. This includes both 'digitised' periodicals, and born-digital periodicals submitted through Electronic Legal Deposit.
repo_url: https://github.com/GLAM-Workbench/trove-journals
repo_name: trove-journals
zenodo_concept_id: 3545215
tags:
  - CSV dataset
  - metadata
hide:
  - toc
---

**Harvested: 5 August 2021**

This file provides metadata of 7,269 periodicals that are available from Trove's journal zone in digital form. This includes both 'digitised' periodicals, and born-digital periodicals submitted through Electronic Legal Deposit. Note that this list contains 7,318 records as there are some duplicates where multiple Trove work records point to the same digitised periodicals. The duplicates have been left in as they include different metadata, and can be easily removed with Pandas. 

[Download the CSV file](https://github.com/GLAM-Workbench/trove-journals/blob/master/digital-journals.csv){ .md-button .md-button--primary }

This file includes the following columns:

| Column | Description |
|--------|-------------|
`title` | the title of the periodical
`contributor` | information about creator or publisher
`issued` | publication date, or date range
`format` | the type of publication, all entries should include 'Periodical', but may include other types such as 'Government publication'
`trove_id` | the 'nla.obj' part of the fulltext_url, a unique identifier for the digital periodical
`trove_url` | url of the periodical's metadata record in Trove
`fulltext_url` | the url of the landing page of the digital version of the periodical
`fulltext_url_type` | the type of digital periodical, one of 'digitised', 'edeposit', or 'other'

### Other options

* Explore using a [**searchable database running on Glitch**](https://trove-digital-periodicals.glitch.me/data/trove-digital-journals)

### Related resources

* [Create a list of Trove's digitised journals](create-list-digitised-journals.md)

--8<-- "help.md"

## Cite as

{{ zenodo_citation() }}


