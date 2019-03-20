# ConceptualDictionary
A conceptual dictionary groups words by concept or semantic relation

Multi Locale dictinary for use by machines.

Each Concept has a Concept UUID version 4 (or higher), that can double as file name

When there is content in the file, it must be in UTF-8 format

Content, when present, must be organized by lines (cr or crlf as line terminator)

Empty lines are ignored

Any line that does not start with p or s will be ignored. This can be used for comments or for future extension

If the line is a comment, it is recomended to use # or ! sign to indicate so, though it is not required in the current format

Each file can have 0 or more lines

Each entry must have eactly 3 types of information, separated by tab charecter

First informattion in each entry must state, if the entry is primary entry or secondry entry using 'p' or 's'

Second information must have a ISO 639-1 language code or a locale code

Second informattion must state, if the entry is primary entry or secondry entry using 'p' or 's'

Thrid information must have exactly one data in the line

all data must be lower case

Example:

d94058b1-a99a-4077-8825-1d46026855e9

# this file is for defining colors, to mean human visual perception

en  p color

en  s colors

en_US p color

en_GB p colour

en_GB s colours

ta  p நிறம்

https://www.wikidata.org/w/api.php?action=wbgetentities&ids=Q1075

https://www.wikidata.org/w/api.php?action=wbgetentities&ids=Q1075&format=json

https://github.com/inventaire/entities-search-engine

https://en.wikipedia.org/w/api.php?format=json&action=query&prop=extracts&exlimit=max&explaintext&exintro&titles=adobe_Inc&redirects=

https://www.wikidata.org/w/api.php?action=wbsearchentities&format=json&language=en&uselang=en&type=item&search=active%20service

https://github.com/maxlath/wikidata-cli
