This was adapted from the template [here](https://github.com/sb2nov/resume), with some modifications to design, the code, and ability to get up and running. [Preview](#preview) here.

# Usage

There are 5 distinct components: header, sections, entry type 1 (title, subheading, date(s), location), entry type 2 (title, date(s)), and entry type 3 (single list no bullet, with a bold prefix). 

You can also modify the colour scheme (primary, secondary, accent, and link colours).

# Header

Change the variables at the top of the document, and then modify the order you want to present your info in the `\headertype{}{}{}{}{}{}` argument at the beginning of the document. You can choose `\doublecol` or `\singlecol`. They look like this:

![](/assets/singlecolheader.svg)
![](/assets/doublecolheader.svg)

Single column probably handles longer links better. Full previews at the [preview](#preview) section.

# Section

`\section{<icon>}{Text}`

<icon> can be anything; fontawesome icons are great.


# Entry

Preceed it by `\resumeEntryStart` and end it with `\resumeEntryEnd`.

## Entry type 1

`\resumeEntryTSDL{Title}{Date(s)}{Subheading}{Location}`

## Entry type 2

`\resumeEntryTD{Title}{Date(s)}`

## Entry type 3

`\resumeEntryS{Bold}{RegularText}`

# Entry Details

Preceed it by `\resumeItemListStart` and end it with `\resumeItemListEnd`. Each item is a `\resumeItem`.

# Preview

## Double Column

![](/assets/doublecolfull.svg)

## Single Column

![](/assets/singlecolfull.svg)

# Credits

Original template from [here](https://github.com/sb2nov/resume).
Template text from [here](https://resumake.io/).