---
title: Adding Title Records
...

*Note: This document is in development.*

This guide describes how to decide whether or not an edition should be included in [*At the Circulating Library*](https://www.victorianresearch.org/atcl/) (ATCL). The guide assumes you already have an edition in hand which you think might belong in ATCL.

# Inclusion criteria

The ATCL database includes books which have all of the following characteristics:

- Prose fiction including collections of stories. No poetry and no plays.
- Intended audience is adult and young adult readers. No works addressed exclusively to children under the age of 13.
- First editions published in the British Isles (England, Ireland, Scotland, Wales, and the Channel Islands).
- Publication date between 1837 and 1901.
- Minimum length of 90 printed pages including illustrations, introductions, prefaces.

We use the word "novel" to refer to these prose fiction works even though a small percentage of them are not novels (e.g., short story collections).

# Steps to add a new title

New titles are added to the database using the steps listed below.
The description of the steps is intended for people who are adding records by going through the *English Catalogue of Books* to find overlooked titles.

1. Identify a candidate book which may need to be added though the *English Catalogue of Books* or other source.
2. Ensure that the publication location is in the British isles. If you are using the *English Catalogue of Books* look at the publisher on the right-hand side of the page. If the name of the publisher is listed (e.g., Bentley, Blackwood), you can safely assume that it is a British Isles publishers.  However, if you see the name of a city outside the British Isles (e.g., "New York", "Detroit"), skip the title.
3. Check the [ATCL database](https://www.victorianresearch.org/atcl) to see if the candidate book is already present.
    - If the title is in the ATCL then the candidate book does not need to be entered.
    - If the title is not in the ATCL continue to the next step.
4. Collect the following pieces of information about the title using the collection form, [`atcl-new-records-collection-form.csv`](atcl-new-records-collection-form.csv):
    - `source` and `source_page`: If you are locating titles using the *English Catalogue of Books* put "ECB" for `source` and indicate the page you are working on in the `source_page` column.
    - `author_last_name`: Enter the author's last name (or anonymous).
    - `title_main` and `title_sub`: Enter the main title and subtitle as they appear on the book's title page (if you have access to a digital surrogate) or as they appear on the relevant line in the *English Catalogue of Books*.
      Use [Chicago Style title capitalization](#chicago-style-title-capitalization).
      Generally, the main title is the part of the title before the first period, colon, or semi-colon.
      Do not include author information (e.g., "by a lady") or format information (e.g., "in three volumes") in the title fields.
      If a title does not have a subtitle, enter *NULL* (all caps).
    - `publisher_name`: Enter the publisher's name. If you are using the *English Catalogue of Books*, the name appears on the right-hand side of the line.
    - `transcription_format_and_price`: If you are using the *English Catalogue of Books* transcribe the format and price information. The format is indicated by a term like "8vo" or "12mo" or "3v. cr. 8o". The price is given in shillings and pence (e.g., "4s 6d"). Transcribe everything. Examples: "post 8vo, 7s 6d", "12mo, 7s 6d", "3v. cr. 8o, 25s 6d".
    - `additional_notes`: Add any notes which might be useful here. If you think the book might not count as prose fiction you could indicate your thinking here. Translator and illustrator information can go here.

# Important note about new editions (new edit., 2nd, 3rd, etc.)

Include novels marked "new edit." (or 2nd, 3rd, etc) in your spreadsheet if the novel is not already in the ATCL. (Background: if a new edition comes out very quickly after a first edition, the English Catalogue sometimes will not mention the first edition.)

# Chicago Style Title Capitalization

Capitalize the first word of the title, the last word of the title, and all important words.
Do not capitalize "a", "an", "the", "and", "but", "for", "at", "by", "to", "etc".

# Frequently Asked Questions

## Is it a novel?

- It might be! Try looking for a copy of the book at Google Books or the Internet Archive. In this case, it doesn't matter if the edition is a different one. A glance at a page or two will tell you if it is likely a novel.
- If in doubt, add it to your list.
