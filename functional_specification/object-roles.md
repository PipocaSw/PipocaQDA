[Back to Index](index.md)

# Role

The role object is part of a role-base access control ([RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)) system of user authorisation.

## User-defined fields

- Name
- Description

## Automatic fields

- Unique identifier

## Access control

- Permissions(s) - N:N relationship

## Predefined entries

The role table contains pre-defined entries to cover many common roles:

- Project owner/super-user (Allowed to to anything. Also useful for single-user projects)
- Project administrator (Allowed to do administrative tasks such as create users, change source classifications, but not deal with actual research data)
- Source administrator (Allowed to work with sources)
- Quality administrator (Allowed to work with qualities)
- Tagger (allowed to perform tagging)
- Query administrator (Allowed to write queries)
- Analyst (Allowed to execute queries)
- Reader (Allowed to view but not modify a project)