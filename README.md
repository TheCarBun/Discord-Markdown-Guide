![](https://imgur.com/ufy3LrI.png)

# Contents:


- [Organizational Text Formatting](#organizational-text-formatting)
  - [Headers](#headers)
  - [Masked Links](#masked-links)
  - [Lists](#lists)
    - [Unordered Lists](#unordered-lists)
    - [Ordered Lists](#ordered-lists)

- [Text Formatting](#text-formatting)
  - [Italics](#italics)
  - [Bold](#bold)
  - [Bold Italics](#bold-italics)
  - [Underline](#underline)
  - [Italic Underline](#italic-underline)
  - [Bold Underline](#bold-underline)
  - [Bold Italic Underline](#bold-italic-underline)
  - [Strikethrough](#strikethrough)
  - [Spoiler Tags](#spoiler-tags)
  
- [Extras :](#extras)
  - [Code Blocks](#code-blocks)
  - [Block Quotes](#block-quotes)
  - [Anti-Markdown](#anti-markdown)
  - [Syntax Highlighting](#syntax-highlighting)

<br><br><br>

# Organizational Text Formatting

## Headers

To create a header, you need to include a specific number of the hash/pound sign character (#). Use (#) for a big header, (##) for a smaller header, or (###) for an even smaller header as the first character(s) in a new line.

# H1
## H2
### H3

```
# H1
## H2
### H3
```

## Masked Links

You can use masked links to make text a clickable or pressable hyperlink. To do so, you need to include the text you want displayed in brackets and then the URL in parentheses. 
<br>
For example:

This is a [masked link](www.google.com)
```
This is a [masked link](use your link here)
```

If you don't wish to embed a link, you can wrap the link with `<>` to remove the embed for that specific link.
<br>
For example:
<br>
```
<www.google.com>
```

## Lists

### Unordered lists
You can create a bulleted list using either (-) or (\*) in the beginning of each line. You can indent your list by adding a space before (-) or (\*) at the beginning of each line.
<br>For example:<br>
This is an unordered list:
* list item 1
* list item 2
  * sub list item 1
  * sub list item 2
* list item 3

```
This is an unordered list:
* list item 1
* list item 2
  * sub list item 1
  * sub list item 2
* list item 3
```

### Ordered Lists

To create an ordered list, add line items with numbers followed by periods. The numbers don't have to be in numerical order, but the list will always start with the first number. You can indent your list by adding a space before the number at the beginning of each line.

<br>For example:<br>
This is an ordered list:
1. list item 1
2. list item 2
    1. sub list item 1
    2. sub list item 2
3. list item 3

```
This is an ordered list:
1. list item 1
2. list item 2
    1. sub list item 1
    2. sub list item 2
3. list item 3
```


# Text Formatting

## Italics
Use `*` or `_` at the start and end of characters you want to make *italic*.
<br>
For example:
<br>
This text is in *italics*	
```
This text is in *italics*
```
 or
 ```
 This text is in _italics_
```

## Bold
Use `**` at the start and end of the characters you want to **bold**.
<br>
For example:
<br>
This is a **Bold** text	
```
This is a **Bold** text
```

## Bold Italics
Use `***` at the start and end of the characters you want to set to ***bold italics***
<br>
For example:
<br>
This text is ***Bold and Italic*** 
```
This text is ***Bold and Italic***
``` 


## Underline
Use `__`(two underscores) to __underline__ texts.
<br>
For example:
<br>
<img src="https://imgur.com/167SvSk.png" height=100px>
```
This text will be __underlined__
```

## Italic Underline
Use `__*` at the start and `*__` at the end of the characters you want to __*italic and underline*__.
<br>
For example:
<br>
<img src="https://imgur.com/sFNoURz.png" height=100px> 
```
This text will be __*italic and underlined*__
```

## Bold Underline
Use `__**` at the start and `**__` at the end of the characters you want to __**bold and underline**__.
<br>
For example:
<br>
<img src="https://imgur.com/9VGeTs3.png" height=100px> 
```
This text will be __**bold and underlined**__
```

## Bold Italic Underline
Use `__***` at the start and `***__` at the end of the characters you want to __***bold, italic and underline***__.
<br>
For example:
<br>
<img src="https://imgur.com/gGDmZ5b.png" height=100px> 
```
This text will be __***bold, italic and underlined***__
```

## Strikethrough
Use `~~` at the start and end of the characters you want to ~~strikethrough~~.
<br>
For example:
<br>
This text will be ~~strikethrough~~ 
```
This text will be ~~strikethrough~~
```

## Spoiler Tags
Use `||` around your text or use `/spoiler` to get spoiler text.
<br>
For example:
<br>
<img src="https://imgur.com/hc91xGF.png" height=100px> 
```
This text will be in ||spoilers||
```

<br><br><br>

# Extras

## Code Blocks
Use backticks( \` ) at the start and end of texts to turn them into code blocks.

* Single line Code Block
<br>
`This is a single line code block with single backticks`
```
`This is a single line code block with single backticks`
```

* Multi line Code Block
```
Use three backticks
to get a multi line
code block 
```

```
```Use three backticks
to get a multi line
code block ```
```


## Block Quotes
Use `>` with a space to get block quotes
> This is a block quote
```
> This is a block quote
```
You can also have multi line block quotes
> This is <br>
> a multiline <br>
> block quote

```
> This is 
> a multiline 
> block quote
```

## Anti-Markdown
Don't want to use markdown? You can put a backslash `/` in front of your statement, or put your message in a code block , and it'll escape the markdown formatting. You'll see those asterisks as you'd like!

## Syntax Highlighting
You can spice up your code blocks by adding a programming language in your code block.
<br>For example:<br>
Here `py` stands for Python
<img src="https://imgur.com/Fzjbd6l.png" height=400px>

```
```py
@requires_authorization(roles=["ADMIN"])
def somefunc(param1='', param2=0):
    r'''A docstring'''
    if param1 > param2: # interesting
        print 'Gre\'ater'
    return (param2 - param1 + 1 + 0b10l) or None

class SomeClass:
    pass
>>> message = '''interpreter   
... prompt'''```
```
You can find more about this [here](https://discord-syntax-highlighting.vercel.app/).

---


Now you're a **Discord text markdown expert**. Get out there and highlight your statements!

## Acknowledgements

* [Discord Markdown 101](https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline-)
* [Discord Syntax Highlighting](https://discord-syntax-highlighting.vercel.app/)
