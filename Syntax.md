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

## Relative Links

It navigates the reader to a different page from the rendered .md file.

e.g. You can navigate to example.md file on clicking [example_folder](example_folder/example.md).

## Images

You can add an image by placing `!` infront of image text inside `[ ]` followed by url of the image inside `( )`.

![F-22 Raptor](https://images4.alphacoders.com/414/thumb-1920-41416.jpg)

Above is an example of rendering an image from absolute link.

![Rafale](example_folder/Rafale.jpeg)

Above is an example of rendering an image from relative link.

## Links

### Unordered List

Use -, * or + for the bullets.

- One
* Two
+ Three

### Ordered List
Use numbers to create a ordered list.

1. One
2. Two
3. Three

### Nested List

It is created by indenting one or more list items below another item.

- Top list item.
  * Second nested list item.
    + Third nested list item.

## Task List

Use hyphen and space followed by `[ ]` before list item to create a task list.

- [ ] Uncheck task list.
- [x] Task list is completed :tada: 

## Mentioning

We can mention a person or a team in github using `@` symbol.

## PR Reference

You can refer to a pull request using `#` symbol followed by PR number or PR title.

## emoji

We can add emojis using :emoji_code:

e.g. - This PR LGTM :thumbsup:, it's ready to be merged :shipit:

## Comments

We can hide content from the rendered markdown by placing the content in HTML comment.

`<!-- The comment will not appear in the rendered markdown. -->`

<!-- The comment will not appear in the rendered markdown. -->

## Escape markdown formatting

We can escape markdown formatting using `\` by placing it before markdown character.

let's rename \*our-new-project\* to \*our-old-project\*.

## Footnotes

we can create footnotes using bracket syntax.

Here is a simple footnote[^1].

A footnote can have multiple lines[^2].

You can also use words, to fit your writing style more closely[^note].

[^1]: My Reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
    
