[Back to Index](index.md)

# Tagger

- The _tagger_ is a module of the application that allows the user to define [fragments](terminology.md#fragment) and tag/untag them with one or more [qualities](terminology.md#quality).

- Researchers typically find tagging to be time-consuming, repetitive and error-prone. For this reason, the user experience of the tagger needs to be as smooth as possible.

- From the perspective of the application, the user interface requirements of the tagger present a very distinct problem. While a satisfactory solution is possible using standard tools such as Django, a full implementation will require lower level control over the user interface, for example by writing Javascript code to run in the browser, or moving away from a browser based model to a native application.

- The process of tagging/untagging should proceed as follows:

  - The user selects a fragment or collection of fragments. A number of selection selection methods should be provided:
    - Mouse swipe, with selection extension and multiple selections using Shift/Control keys.
    - Facility to select a word, sentence or paragraph, perhaps with multiple mouse clicks, or a different modifier key.
    - Based on the result of a text search or regular expression.
    - Ability to edit a selection, for example extending or reducing it with the mouse, again with word, sentence and paragraph jumps available.
  - Once a selection is made, a context menu should be includes options to tag the selection:
    - immediately based on recently used qualities.
    - any quality, via a series of nested menus reflecting the hierarchy of qualities.
    - create a new quality ‘on the fly’. This is sometimes referred to as ‘in vivo’ coding.
    - open a pop-up window where a fuller selection can be made. This could allow multiple qualities to be tagged simultaneously, or qualities currently associated with all or a part of the selection to by associated with all or none of the selection.

- All tagging operations must be possible to Undo/Redo.

- Tagged fragments should be easy to visualise, for example by their colour. However, as it is common for fragments with different qualities to overlap, it is not as simple as changing the text colour to reflect any qualities. Some solutions to this problem include:

  - Using coloured underlining to indicate tagging, with multiple underlines possible. This is only practical for a small number of overlapping tagged fragments.
  - Using a panel to the side of the source to present the vertical extent of tagged fragments using a coloured vertical lines that represents the qualities. Hovering the mouse over a vertical line should cause the text (or image section, etc.) to change to the relevant colour so the exact extent of the fragment can be seen.
