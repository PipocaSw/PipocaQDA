[Back to Index](index.md)

# Sources

[_Sources_](terminology.md#source) are the raw material of a research project. Source management is a central function of QDA software. Because sources originate in the real world, their management poses some key problems, such as:

- they can be stored in a wide variety of data formats (some common examples include PDF, Microsoft Word, epub, textual, JPEG, Mp3)
- they may be subject to arbitrary revisions
- their access may be restricted to privileged users

## Functions

### Create/Edit/Delete

- The user must be able to perform these standard operations. For this purpose creating a source means creating a source object within a project - the source data itself is often created externally. Likewise editing a source means editing the attributes of the source object, not the content of the souce.

- The previous point notwithstanding, it would be useful if the software could provide the facility to create and edit simple source documents, for example rich text, to allow such sources to be created without leaving PipocaQDA. The best way to provide this feature may be to integrate it into the [tagger](tagger.md).

- Because fragments are subsets of sources, it is important to maintain internal data integrity by deleting any such fragments when deleting a source.

- For organisational puposes, sources are arranged in a hierarchical folder structure. The source management module should allow folders to be collapsed/expanded, and sources to be moved around the folder structure.

- It should be possible cut/copy/paste sources to replicate a source or collection of sources, including between different projects.

- It should be possible to import/export collections of sources to a comma-separated variable (CSV) file to facilitate mass creation or editing.

- As sources may have arbitrary attributes, a flexible system for editing them is required.

### Open Tagger

The source management must provide the facility to open a source object in the [tagger](tagger.md).
