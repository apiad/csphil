# Design document

> This document describes the main design choices about topics, content, structure, and layout.

## Formats

Ultimately, I intend this ebook to be formatted in two ways, as a online website, and as PDF/epub file.

The content is writen in Markdown with additional LaTeX formatting where necessary. There is a [makefile](../makefile) that builds the content into the different formats (wip).

## Workflow

Regarding workflow, I follow a fairly simple model:

1. **Brainstorm**: in which I dump all possible ideas regarding a given topic, flat, on a Markdown file. Here quantity trumps quality, the purpose being covering as much ground as possible.

2. **Outline**: in which I select, reorder, and refine the ideas that came of the brainstorm. The end result is a structured outline with sections, subsections, and main claims.

3. **Content**: in which I expand every single claim in the outline to one, two, or as many paragraphs as necessary. Here again quantity trumps quality, the purpose being saying everything that can be said about each claim.

4. **Clarity**: in which I rewrite each paragraph, simplifying and cutting down all unnecessary stuff, to make the writing as clear as possible. Here almost all the text is rewriten.

5. **Polish**: in which I rewrite again, but this time just trying to pick the most important bits and make them as engaging as possible. Remove bland adjectives and make everything sound more vibrant.

To apply this workflow to a book, I use a two-level structure. At the top level we will have a [brainstorm.md file](brainstorm.md) where all top-level ideas coexist. This file will link to individual .md files that expand on a given idea, and which will ultimately become chapters.

The brainstorm file serves as an unstructured index to the rest of the content. It is not intended to be included in the final book, rather it is there to guide the writing process.

The individual chapter files will eventually become part of the book, once they graduate to phase 3 (content).