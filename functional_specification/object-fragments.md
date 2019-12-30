[Back to Index](index.md)

# Fragments

A Fragment is a simple subset of a Source. By “simple” we mean simple enough to be easily specified, so that more complex subsets of a Source can be defined as the union of multiple Fragments. Some examples of a Fragment would be a chunk of text defined by the start- and end-point of a textual Source, the rectangle defined by the top-left and bottom-right coordinates within an image or an interval of a video or audio. More complex examples could be envisioned, such as all sentences containing a given keyword. If the Source is dynamic, then by definition any Fragment of that Source is also dynamic.

Specifying fragments poses a tricky problem. Specifications need to be capable of handling different kinds of sources and fragments, including kinds that are are beyond we can currently foresee. We propose therefore that fragments be specified in a simple textual format who interpretation depends on the source kind and can be extended in the future.

Some indicative examples:

offset:1,5 | The subsection of a textual source from the first to the fifth character
offset:100,300,600,700 | A square section of an image enclosed by x coordinates 100 to 300 and y coordinates 600 to 700
sentence.contains:frog | All sentences that contain the word “frog”

## User-defined fields

- Definition
- Owner

## Automatic fields

- Unique identifier
- Created date/time/user
- Updated date/time/user

## Methods

- Create
- Content - return the content of the source fragment
- Tag - Assign a quality to a fragment
- Untag - Unassign a quality to a fragment
- Qualities - Retrieve all qualities assigned to a fragment

## Validation

- Current user has required privileges
- Attempt to delete quality that is assigned to fragments