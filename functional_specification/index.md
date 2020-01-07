# Index

# Introduction

This document provides a functional specification for the PipocaQDA software. Its purpose is to guide the formulation of an implementation specification. It specifies what users of the software must be able to do without necessarily providing a precise description of how they will be able to do it.

To help make the code eaily re-usable, as well as to allow the use of different underlying data storage technologies, the project should comprise separate data layer and application layer. The interface between these two layers should be clearly specified in an API.

Reflecting this design choice, this functional specification document has separate sections for the data and application layers.

## Data Layer

The data layer presents the underlying objects of qualitative data analysis, allowing operations such as creation, modification and reporting to be performed. It does not specify the form in which that data is ultimately stored.

The data layer comprises a series of objects and operations that can be performed on them. Most of the objects can be represented in a relational database structure, in some cases using an Entity-Attribute-Value ([EAV](https://en.wikipedia.org/wiki/Entity–attribute–value_model)) model for project-specific attributes. The one exception to this generalisation is the _fragment_.

### Objects

- [Project](object-project.md)
- [Qualities](object-qualities.md)
- [Sources](object-sources.md)
- [Fragments](object-fragments.md)
- [Queries](object-queries.md)
- [Users](object-users.md)

## Application Layer

### Modules

- [Project](module-project.md)
- [Qualities](module-qualities.md)
- [Sources](module-sources.md)
- [Tagger](module-tagger.md)
- [Queries](module-query.md)

## Appendices

- [Terminology](terminology.md)
