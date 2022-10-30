# Markdown

Markdown is a lightweight markup language with plain text formatting syntax created by [John Gruber](https://daringfireball.net). By its very nature, being a plain text file, it is designed to add future-proofing to any set of documents while still maintaining basic text and table formatting options. In addition, Markdown may be exported to HTML and many other formats using a number of various Markdown editors. Markdown is often used to format readme files, for writing books, blogs, and messages, or to simply create rich text using plain text in a Markdown editor.

## Markdown Editors

Below is a list of recommended Markdown editors, their cost, and my reasoning for each recommendation.

* [Typora](https://typora.io) $15 (no subscriptions) - By far my favorite Markdown editor. The best at handling Markdown tables, importing webpages - with a simple drag and drop - and a great list of export options.
* [Visual Studio Code](https://code.visualstudio.com) FREE - Another favorite of mine. Sync your local files with GitHub. Huge list of available Markdown plugins!
* [Obsidian](https://obsidian.md) FREE - Yet another Fav. The best for preserving roleplaying game rulesets and running tabletop adventures. Lots of great RPG-style plugins. The best for replacing campaign tracking websites and apps. For more information, visit [Josh Plunket’s YouTube Channel](https://www.youtube.com/channel/UCoW2sPmrevk9eiJKcQXeHUQ) to learn more about using Obsidian for your roleplaying game campaign management.
* [iA Writer](https://ia.net/writer) $50 (no subscriptions) - A costly option, but very streamlined and Obsidian-like without the plugins. One of the best for keeping your documents future-proofed. Great list of export options.

# Markdown Syntax

Nearly all Markdown editors support basic syntax. There are minor variations and discrepancies between Markdown processors.

## Headings

To create a heading, add number signs (`#`) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level three (`<h3>`), use three number signs (e.g., `### My Header`).

| Markdown                 | Rendered Output |
| ------------------------ | --------------- |
| `# Heading level 1`      | Heading level 1 |
| `## Heading level 2`     | Heading level 2 |
| `### Heading level 3`    | Heading level 3 |
| `#### Heading level 4`   | Heading level 4 |
| `##### Heading level 5`  | Heading level 5 |
| `###### Heading level 6` | Heading level 6 |

## Bold

To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

| Markdown                     | Rendered Output            |
| ---------------------------- | -------------------------- |
| `I just love **bold text**.` | I just love **bold text**. |

## Italic

To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

| Markdown                               | Rendered Output                      |
| -------------------------------------- | ------------------------------------ |
| `Italicized text is the *cat's meow*.` | Italicized text is the *cat’s meow*. |

## Bold and Italic

To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase. To bold and italicize the middle of a word for emphasis, add three asterisks without spaces around the letters.

| Markdown                               | Rendered Output                      |
| -------------------------------------- | ------------------------------------ |
| `This text is ***really important***.` | This text is ***really important***. |

## Blockquotes

To create a blockquote, add a `>` in front of a paragraph.

```
> Dorothy followed her through many of the beautiful rooms in her castle.
```

The rendered output looks like this:

> Dorothy followed her through many of the beautiful rooms in her castle.

### Blockquotes with Multiple Paragraphs

Blockquotes can contain multiple paragraphs. Add a `>` on the blank lines between the paragraphs.

```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

The rendered output looks like this:

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Nested Blockquotes

Blockquotes can be nested. Add a `>>` in front of the paragraph you want to nest.

```
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```

The rendered output looks like this:

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Blockquotes with Other Elements

Blockquotes can contain other Markdown formatted elements. Not all elements can be used — you’ll need to experiment to see which ones work.

```
> #### The quarterly results look great!
>
> * Revenue was off the chart.
> * Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
```

The rendered output looks like this:

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
> *Everything* is going according to **plan**.

## Ordered Lists

To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

```
1. First Item
2. Second Item
3. Third Item
```

The rendered output looks like this:

1. First Item
2. Second Item
3. Third Item

## Unordered Lists

To create an unordered list, add dashes (`-`), asterisks (`*`), or plus signs (`+`) in front of line items. Indent one or more items to create a nested list.

```
* First Item
* Second Item
* Third Item
```

The rendered output looks like this:

* First Item
* Second Item
* Third Item

#### Starting Unordered List Items With Numbers

If you need to start an unordered list item with a number followed by a period, you can use a backslash (`\`) to escape the period.

```
* 1968\. A great year!- I think 1969 was second best.
```

The rendered output looks like this:

* 1968\. A great year!- I think 1969 was second best.

## Adding Elements in Lists

To add another element to a list while preserving the continuity of the list, indent the element four spaces or one tab, as shown in the following examples.

 **Tip:** If things don't appear the way you expect, double-check that you've indented the elements in the list four spaces or one tab.

### Paragraphs

```
* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.
```

The rendered output looks like this:

- This is the first list item.

- Here’s the second list item.

  I need to add another paragraph below the second list item.

- And here’s the third list item.

### Blockquotes

```
* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.
```

The rendered output looks like this:

- This is the first list item.

- Here’s the second list item.

  > A blockquote would look great below the second list item.

- And here’s the third list item.

### Code Blocks

[Code blocks](https://www.markdownguide.org/basic-syntax#code-blocks) are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

```
1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.
```

The rendered output looks like this:

1. Open the file.

2. Find the following code block on line 21:

   ```
    <html>
      <head>
        <title>Test</title>
      </head>
   ```

3. Update the title to match the name of your website.

### Images

```
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3. Close the file.
```

### Lists

You can nest an unordered list in an ordered list or vice versa.

```
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item
```

The rendered output looks like this:

1. First item
2. Second item
3. Third item
   - Indented item
   - Indented item
4. Fourth item

## Code

To denote a word or phrase as code, enclose it in backticks (``).

```
At the command prompt, type `nano`.
```

The rendered output looks like this:

At the command prompt, type `nano`.

### Escaping Backticks

If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks (````).

```
`Use `code` in your Markdown file.`
```

The rendered output looks like this:

`Use `code` in your Markdown file.`

## Horizontal Rules

To create a horizontal rule, use three or more asterisks (`***`), dashes (`---`), or underscores (`___`) on a line by themselves.

```
***
---
_________________
```

The rendered output of all three looks identical:

------

## Links

To create a link, enclose the link text in brackets (e.g., `[Duck Duck Go]`) and then follow it immediately with the URL in parentheses (e.g., `(https://duckduckgo.com)`).

```
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
```

The rendered output looks like this:

My favorite search engine is [Duck Duck Go](https://duckduckgo.com/).

### Adding Titles

You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in quotation marks after the URL.

```
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").
```

The rendered output looks like this:

My favorite search engine is [Duck Duck Go](https://duckduckgo.com/).

### URLs and Email Addresses

To quickly turn a URL or email address into a link, enclose it in angle brackets.

```
<https://www.srd.wiki>
<fake@example.com>
```

The rendered output looks like this:

[https://www.srd.wiki](https://www.srd.wiki)
[fake@example.com](mailto:fake@example.com)

### Formatting Links

To emphasize links, add asterisks before and after the brackets and parentheses. To denote links as code, add backticks in the brackets.

```
I love supporting the **[EFF](https://eff.org)**.
This is our *[Markdown Guide](https://srd.wiki/markdown)*.
```

The rendered output looks like this:

I love supporting the **[EFF](https://eff.org/)**.
This is our *[Markdown Guide](https://srd.wiki/markdown)*.

### Reference-style Links

Reference-style links are a special kind of link that make URLs easier to display and read in Markdown. Reference-style links are constructed in two parts: the part you keep in line with your text and the part you store somewhere else in the file to keep the text easy to read.

#### Formatting the First Part of the Link

The first part of a reference-style link is formatted with two sets of brackets. The first set of brackets surrounds the text that should appear linked. The second set of brackets displays a label used to point to the link you’re storing elsewhere in your document.

Although not required, you can include a space between the first and second sets of brackets. The label in the second set of brackets is not case-sensitive and can include letters, numbers, spaces, or punctuation.

This means the following example formats are roughly equivalent to the first part of the link:

- `[hobbit-hole][1]`
- `[hobbit-hole] [1]`

#### Formatting the Second Part of the Link

The second part of a reference-style link is formatted with the following attributes:

1. The label, in brackets, followed immediately by a colon and at least one space (e.g., `[label]: `).
2. The URL for the link, which you can optionally enclose in angle brackets.
3. The optional title for the link, which you can enclose in double quotes, single quotes, or parentheses.

This means the following example formats are all roughly equivalent for the second part of the link:

- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)`

You can place this second part of the link anywhere in your Markdown document. Some people place them immediately after the paragraph in which they appear, while other people place them at the end of the document (like endnotes or footnotes).

#### An Example Putting the Parts Together

Say you add a URL as a standard URL link to a paragraph, and it looks like this in Markdown:

```
In a hole in the ground, there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.
```

Though it may point to interesting additional information, the URL as displayed really doesn’t add much to the existing raw text other than making it harder to read. To fix that, you could format the URL like this instead:

```
In a hole in the ground, there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
```

In both instances above, the rendered output would be identical:

> In a hole in the ground, there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle), and that means comfort.

and the HTML for the link would be:

```
<a href="https://en.wikipedia.org/wiki/Hobbit#Lifestyle" title="Hobbit lifestyles">hobbit-hole</a>
```

## Images

To add an image, add an exclamation mark (`!`), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title in quotation marks after the path or URL.

```
![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")
```

**Note:** To resize or add a caption to an image, see those sections below.



### Linking Images

To add a link to an image, enclose the Markdown for the image in brackets and then add the link in parentheses.

```
[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
```

## Escaping Characters

To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (`\`) in front of the character.

```
\* Without the backslash, this would be a bullet in an unordered list.
```

The rendered output looks like this:

\* Without the backslash, this would be a bullet in an unordered list.

### Characters You Can Escape

You can use a backslash to escape the following characters.

| Character | Name                                           |
| --------- | ---------------------------------------------- |
| \         | backslash                                      |
| `         | backtick (see also escaping backticks in code) |
| *         | asterisk                                       |
| _         | underscore                                     |
| { }       | curly braces                                   |
| [ ]       | brackets                                       |
| < >       | angle brackets                                 |
| ( )       | parentheses                                    |
| #         | pound sign                                     |
| +         | plus sign                                      |
| -         | minus sign (hyphen)                            |
| .         | dot                                            |
| !         | exclamation mark                               |
| \|        | pipe (see also escaping pipe in tables)        |

## HTML

Many Markdown applications allow you to use HTML tags in Markdown-formatted text. This is helpful if you prefer certain HTML tags to Markdown syntax. For example, some people find it easier to use HTML tags for images. Using HTML is also helpful when you need to change the attributes of an element, like specifying the color of text or changing the width of an image.

To use HTML, place the tags in the text of your Markdown-formatted file.

```
This **word** is bold. This <em>word</em> is italic.
```

The rendered output looks like this:

This **word** is bold. This *word* is italic.

# Hacks

Workarounds for things not officially supported by Markdown. The majority of people using Markdown will find that the basic and extended syntax elements cover their needs. But chances are that if you use Markdown long enough, you’ll inevitably discover that it doesn’t support something you need. This page provides tips and tricks for working around Markdown’s limitations.

 **Tip:** These hacks aren't guaranteed to work in your Markdown application. If you need to use these hacks frequently, you should consider writing using something other than Markdown. 

## Underline

Underlined text is not something you typically see in web writing, probably because the underlined text is nearly synonymous with links. However, if you’re writing a paper or a report, you may need the ability to underline words and phrases. Few applications provide support for underlining text, but Markdown doesn’t natively support underlining. If your Markdown processor supports HTML, you can use the `<ins>` HTML tag to underline text in your document.

```
Some of these words <ins>will be underlined</ins>.
```

The rendered output looks like this:

Some of these words will be underlined.

## Indent (Tab)

Tabs and whitespace have a special meaning in Markdown. You can use trailing whitespace to create line breaks, and you can use tabs to create code blocks. But what if you need to indent a paragraph the old-fashioned way, using the tab key? Markdown doesn’t provide an easy way of doing that.

Your best bet might be to use a Markdown editor that supports indentation. This is common in applications that are more oriented toward desktop publishing.

Another option, if your Markdown processor supports HTML, is to use the HTML entity for non-breaking space (` `). This should probably be your option of last resort, as it can get awkward. Basically, every ` ` in your Markdown source will be replaced with a space in the rendered output. So if you stick four instances of ` `before a paragraph, the paragraph will look like it’s indented four spaces.

```
&nbsp;&nbsp;&nbsp;&nbsp;This is the first sentence of my indented paragraph.
```

The rendered output looks like this:

  This is the first sentence of my indented paragraph.

## Center

Having the ability to center text is a necessity when writing a paper or a report. Unfortunately, Markdown doesn’t have any concept of text alignment (one possible exception is when using tables. The good news is that there’s an HTML tag you can use: `<center>`. If your Markdown processor supports HTML, you can place these tags around whatever text you want to center align.

```
<center>This text is centered.</center>
```

The rendered output looks like this:

This text is centered.

The `<center>` HTML tag is technically supported but officially deprecated, which means it works for now, but you’re not supposed to be using it. Unfortunately, there’s no pure HTML alternative. You could try using one of the CSS alternatives. Not all Markdown applications provide CSS support, but if the one you’re using does, here’s an alternative to the `<center>` tag:

```
<p style="text-align:center">Center this text</p>
```

If this is supported by your Markdown application, the output looks like this:

Center this text

## Color

Markdown doesn’t allow you to change the color of text, but if your Markdown processor supports [HTML](https://www.markdownguide.org/basic-syntax/#html), you can use the `<font>` HTML tag. The `color` attribute allows you to specify the font color using a color’s name or the hexadecimal `#RRGGBB` code.

```
<font color="red">This text is red!</font>
```

The rendered output looks like this:

This text is red!

The `<font>` HTML tag is technically supported but officially deprecated, which means it works for now, but you’re not supposed to be using it. Unfortunately, there’s no pure HTML alternative. You could try using one of the CSS alternatives. Not all Markdown applications provide CSS support, but if the one you’re using does, here’s an alternative to the `<font>` tag:

```
<p style="color:blue">Make this text blue.</p>
```

If this is supported by your Markdown application, the output looks like this:

Make this text blue.

## Comments

Some people need the ability to write sentences in their Markdown files that *will not* appear in the rendered output. These comments are essentially hidden text. The text is viewable by the author of the document, but it’s not printed on the webpage or PDF. Markdown doesn’t natively support comments, but several enterprising individuals have devised a solution.

To add a comment, place text inside brackets followed by a colon, a space, and a pound sign (e.g., `[comment]: #`). You should put blank lines before and after a comment.

```
Here's a paragraph that will be visible.

[This is a comment that will be hidden.]: # 

And here's another paragraph that's visible.
```

The rendered output looks like this:

Here’s a paragraph that will be visible.

And here’s another paragraph that’s visible.

 **Tip:** This tip comes from [Stack Overflow](https://stackoverflow.com/questions/4823468/comments-in-markdown). It's been peer-reviewed and used by thousands of people!

## Admonitions

Admonitions are frequently used in documentation to call attention to warnings, notes, and tips. Markdown doesn’t provide a special syntax for admonitions, and most Markdown applications don’t provide support for admonitions (one exception is [MkDocs](https://www.markdownguide.org/tools/mkdocs/)).

However, if you need to add admonitions, you might be able to use blockquotes with emojis and emphasis to create something that looks similar to the admonitions you see on other websites.

```
> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.
```

The rendered output looks like this:

> ⚠️ **Warning:** Do not push the big red button.

> 📝 **Note:** Sunrises are beautiful.

> 💡 **Tip:** Remember to appreciate the little things in life.

## Image Size

The Markdown syntax for images doesn’t allow you to specify the width and height of images. If you need to resize an image and your Markdown processor supports HTML, you can use the `img` HTML tag with the `width` and `height` attributes to set the dimensions of an image in pixels.

```
<img src="image.png" width="200" height="100">
```

The rendered output will contain the image resized to the dimensions you specified.

## Image Captions

Markdown doesn’t natively support image captions, but there are two possible workarounds. If your Markdown application supports [HTML](https://www.markdownguide.org/basic-syntax/#html), you can use the `figure` and `figcaption` HTML tags to add a caption for your image.

```
<figure>
    <img src="/assets/images/albuquerque.jpg"
         alt="Albuquerque, New Mexico">
    <figcaption>A single-track trail outside of Albuquerque, New Mexico.</figcaption>
</figure>
```

 **Tip:** If your Markdown application supports CSS, you can use CSS to style the appearance of the caption.

If your Markdown application doesn’t support HTML, you could try placing the caption directly below the image and using emphasis.

```
![Albuquerque, New Mexico](/assets/images/albuquerque.jpg)
*A single-track trail outside of Albuquerque, New Mexico.*
```

## Link Targets

Some people like creating links that open in new tabs or windows. The Markdown syntax for links doesn’t allow you to specify the `target` attribute, but if your Markdown processor supports HTML, you can use HTML to create these links.

```
<a href="https://www.srd.wiki/markdown" target="_blank">Learn Markdown!</a>
```

The rendered output looks like this:

[Learn Markdown!](https://www.srd.wiki/markdown)

## Symbols

Markdown doesn’t provide a special syntax for symbols. However, in most cases, you can copy and paste whatever symbol you want to use into your Markdown document. For example, if you need to display Pi (π), just find the symbol on a webpage and copy and paste it into your document. The symbol should appear as expected in the rendered output.

Alternatively, if your Markdown application supports HTML, you can use the HTML entity for whatever symbol you want to use. For example, if you want to display the copyright sign (©), you can copy and paste the HTML entity for copyright (`©`) into your Markdown document.

Here’s a partial list of HTML entities for symbols:

- Copyright (©) — `©`
- Registered trademark (®) — `®`
- Trademark (™) — `™`
- Euro (€) — `€`
- Left arrow (←) — `←`
- Up arrow (↑) — `↑`
- Right arrow (→) — `→`
- Down arrow (↓) — `↓`
- Degree (°) — `°`
- Pi (π) — `π`

For a complete list of available HTML entities, refer to Wikipedia’s page on HTML entities.

## Table Formatting

Markdown tables are notoriously finicky. You can’t use many Markdown syntax elements to format the text in table cells. But there are workarounds for at least two common table issues: Line breaks and lists.

### Line Breaks Within Table Cells

You can separate paragraphs within a table cell by using one or more `<br>` HTML tags.

```
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| Paragraph   | First paragraph. <br><br> Second paragraph. |
```

The rendered output looks like this:

| Syntax    | Description                          |
| --------- | ------------------------------------ |
| Header    | Title                                |
| Paragraph | First paragraph.   Second paragraph. |

### Lists Within Table Cells

You can add a list within a table cell by using HTML tags. This option is not always supported.

```
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| List        | Here's a list! <ul><li>Item one.</li><li>Item two.</li></ul> |
```

The rendered output looks like this:

| Syntax | Description                       |
| ------ | --------------------------------- |
| Header | Title                             |
| List   | Here's a list! Item one.Item two. |

## Table of Contents

Some Markdown applications can automatically generate a table of contents (also referred to as a *TOC*) from your headings, but this isn’t a feature provided by all Markdown applications. However, if your Markdown application supports heading IDs, you can create a table of contents for your Markdown file using a list and some links.

```
#### Table of Contents

* First Item
* Second Item
* Third Item
```

The rendered output looks like this:

#### Table of Contents

- First Item
* Second Item
* Third Item

## Videos

If your Markdown application supports HTML, you should be able to embed a video in your Markdown file by copying and pasting the HTML code provided by a video website like YouTube or Vimeo. If your Markdown application doesn’t support HTML, you can’t embed a video, but you can come close by adding an image and a link to the video. You could do this with practically any video on any video service.
