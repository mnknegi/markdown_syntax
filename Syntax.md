# Markdown Syntax

This repo contains the basic markdown syntax.

## Heading

To create a heading, add hash signs (#) in front of a sentance. The number of hash signs you use will determine the level of heading. Below is the descending order of heading levels.

> `#` > `##` >  `###` > `####` > `#####` > `######`


### Table of heading levels

| Markdown | Heading level              | Rendered Output            |
| -------- | -------------------------- | -------------------------- |
| #        |     # Heading level 1      | <h1> Heading level 1 </h1> |
| ##       |     # Heading level 2      | <h2> Heading level 2 </h2> |
| ###      |     # Heading level 3      | <h3> Heading level 3 </h3> |
| ####     |     # Heading level 4      | <h4> Heading level 4 </h4> |
| #####    |     # Heading level 5      | <h5> Heading level 5 </h5> |
| ######   |     # Heading level 6      | <h6> Heading level 6 </h6> |

## Text Styling

You can style your text using bold, italic, underline, superscript, subscript, strikethrough etc on your .md file.

### Table of Styling symbols

| Markdown              | Style level            | Rendered Output                                                 |
| --------------------- | ---------------------- | --------------------------------------------------------------- |
| `** **` or `__ __`    | Bold                   | <b> Text in bold </b>                                           |
| `* *` or `_ _`        | Italic                 | <I> Text in italic </I>                                         |
| `*** ***`             | Bold and italic        | <b><i> Text in bold and italic </i></b>                         |
| `_ _` inside `** **`  | Bold and nested italic | <b> Bold and nested <i> italic </i></b>                         |
| `<sub> </sub>`        | Subscript              | H<sub> 2 </sub>SO<sub> 4 </sub>                                 |
| `<sup> </sup>`        | Superscript            | (a + b)<sup> 2 </sup> = a<sup> 2 </sup> + b<sup> 2 </sup> + 2ab |
| `~ ~` or `~~ ~~`      | Strikethrough          | ~~strikethrough~~ |

## Quote

### Text 

Place `>` before a phrase to make it a quote. 
> This is a quote.

### Code

* To quote something inside a sentence use backticks.

```
A quick `brown fox` jumps over a `lazy dog`.

```
***Output:*** 

A quick `brown fox` jumps over a `lazy dog`.

* To create a distinct block use triple backtricks e.g.

` ``` `

Two roads diverged in a wood, and I—

I took the one less traveled by,

And that has made all the difference.
                       - Robert Frost
                                             
` ``` `

***Output:*** 

```
Two roads diverged in a wood, and I—
I took the one less traveled by,
And that has made all the difference.
                       - Robert Frost
```

## Links

A link is use to redirect to some webpage on click over it. A link has two components, a link text and a url. Link text is written inside `[ ]` followed by a url wrapped inside `( )`.

e.g. You can open markdown_syntax repo from [here](https://github.com/mnknegi/markdown_syntax).


