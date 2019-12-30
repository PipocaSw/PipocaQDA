[Back to Index](index.md)

# Project

The project is the highest level object handled by PipocaQDA. All other objects belong to exactly one project. Together with its child objects, a project object describes a single research project.

## User-defined fields

- Name
- Description
- Owner
- Copyright status
- Default regional information (language, date/time format)
- Default privacy settings

## Automatic fields

- Created date/time/user
- Updated date/time/user

## Methods

- Create
- Open
- Update
- Close
- Delete

## Validation

- Current user has required privileges

## User-defined fields

- Name
- Description
- Owner
- Optional parent quality identifier

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