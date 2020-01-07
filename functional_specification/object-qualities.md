[Back to Index](index.md)

# Qualities

A _quality_ is something that a researcher associates with _fragments_ of research data in the process of performing qualitative analysis. Users of other qualitative research software may know a quality as a _node_ or a _code_. We have chosen the term _quality_ for its clear connection with qualitative research, and the fact that it is not already used to refer to many other things.

Depending on the research methodology being employed, the qualities used in a project can be defined by the methodology, predetermined but depending on the particular subject of the research, or defined and refined in the course of the research. Moreover, these multiple ways of defining qualities are often combined within a single research project.

A second feature of qualities is that they form a hierarchy. That is, a quality can have sub-qualities, and multiple qualities can be treated as a group, even if that group cannot properly be considered a quality.

[Finally, qualities may relate to one another in arbitrary ways.]

Qualities can have arbitrary attributes with values, requiring an Entity-Attribute-Value ([EAV](https://en.wikipedia.org/wiki/Entity–attribute–value_model)) model to store.

## User-defined fields

- Name
- Description
- Owner
- Optional parent quality identifier
- EAV attribute-values

## Automatic fields

- Unique identifier
- Created date/time/user
- Updated date/time/user

## Methods

- Create
- Open by name, identifier, parent or sibling identifier
- Update
- Close
- Delete

## Validation

- Current user has required privileges
- Attempt to delete quality that is assigned to fragments
