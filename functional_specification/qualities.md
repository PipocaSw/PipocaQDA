[Back to Index](index.md)

# Qualities

[_Qualities_](terminology.md#quality) are managed through a distinct sub-section of the application. This might be implemented as a pop-up window, or a tab on a project window.

## Functions

### Create/Edit/Delete

The user must be able to perform these standard operations on qualities in a project.

Because fragments are assocated with qualities, it is important to maintain internal data integrity by deleting any such fragments when deleting a quality.

Qualities are arranged hierarchically, which has important implications for the quality management module. First, the user should be able to collapse/expand a quality to hide/show all its subqualities. Second, the user should be able to move a quality within the hierarchy.

It should be possible cut/copy/paste qualities to replicate a quality or collection of qualities, including between different projects.

It should be possible to import/export collections of qualities to a comma-separated variable (CSV) file to facilitate mass creation or editing.