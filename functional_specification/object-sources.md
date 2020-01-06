[Back to Index](index.md)

# Sources

A _source_ is a single item of research data that forms part of a _project_. Typical examples include an interview transcript, photograph or newspaper article.

Because sources originate in the real world, they may be stored in a many different data formats (some common examples include PDF, Microsoft Word, epub, plain text, JPEG, MP3, and others)

A source may have multiple revisions. These can be as simple as draft and final versions of a report. They can potentially also be snapshots at different times of websites or social media feeds.

As sources can include confidential information received from key informants in a research project, it may be necessary to restrict access through user privilege enforcement and, potentially, encryption.

For administrative purposes, sources are arranged into a hierarchical structure of folders.

Sources can have arbitrary attributes with values, requiring an Entity-Attribute-Value ([EAV](https://en.wikipedia.org/wiki/Entity–attribute–value_model)) model to store.

## User-defined fields

- Name
- Description
- Owner
- Folder
- Data type (MIME?)
- Data
- Encryption information

## Automatic fields

- Unique identifier
- Created date/time/user
- Updated date/time/user

## Methods

- Create
- Open by name, identifier, folder or sibling identifier
- Update [__NB Unclear how revisions should work__]
- Revise
- Close
- Delete

## Validation

- Current user has required privileges
- Attempt to delete source with existing fragments
