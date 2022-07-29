# MARKDOWN(.md) FILES CHEAT SHEET

### Markdown: is a simplified version of the markup language. Compared to the popular HTML language it is easier for humans to read

## .md files are files which contains important information about your software or repo, sometimes relating to the installation process. You can identify them by their name: ``` readme.md ```  Here is a cheat sheet to most of the stuff you need to make a nicely formatted README.md file 🙂<sub>[*more about md files](https://www.ionos.com/digitalguide/websites/web-development/what-is-a-md-file/)</sub>

### Here's a link to the [Daring Fireball](https://daringfireball.net/projects/markdown/syntax#backslash) if you want to read more or know more 

##### NB : you can write your .md files in HTML and they would exactly the same, what you read is the alternate to HTML but will contain some html

# Text-formating

<p>

## Headings
To create a heading, Add the ``` # ``` symbol before your heading text. The number of # you use will determine the size of the heading. limit is 6
```
## heading 2

### heading 3

```

> ## heading 2
> ### heading 3

## Others:

```
 bold => **this is a bold Text1** or __this is a bold text2__ 
 italic => *this text is italized2* or _this text is italized1_
 strikethrough => ~~this was a mistake~~
 subscript => <sub> this is a subscript text </sub>
 superscript => <sup> this is a superscript text </sup>
 Bold and nested italic => **This text is _extremely_ important**
 All bold and italic => ***All this text is important***
```
> **this is a bold Text1** or __this is a bold text2__

> *this text is italized1* or _this text is italized2_

> ~~this was a mistake~~

> <sub> this is a subscript text </sub>

> <sup> this is a superscript text </sup>

> **This text is _extremely_ important**

> ***All this text is important***

#  Quotes 

you can quote a text with ``` > ```

```
> this is a quote
```
> this is a quote

## Quoting codes

use `` for inline and for multiline use ``` you can also use it for inline<br/>exapmle:

this is an inline \` quote \`<br/>

this is an inline ` quote `


\```

this<br/> 
is <br/>
a <br/>
multiline<br/>
quote <br/>

\```

```
this 
is 
a 
multiline
quote
```


</p>


# Links

you can create links by wraping the display text in the [] and the link it self in () <br/>
example:
this is the link to the [GitHub Docs](https://docs.github.com/en)

```
this is the link to the [Github Docs](https://docs.github.com/en/)
```

# Images

<details><summary>Images</summary><p>

you can display images by  wrapping the alt-text in ![] and the link to the image to be displayed in ()<br/>
example:

```
![markdown file image](https://cdn.iconscout.com/icon/free/png-128/markdown-3550792-2970377.png)
```

![markdown file image](https://cdn.iconscout.com/icon/free/png-128/markdown-3550792-2970377.png)
</p>
</details>

<details><summary>Relative image links</summary><p>

## When the image link is in your files

|  Context	    | Relative Link|
|---|---|
| In a .md file on the same branch |	/assets/images/electrocat.png |
| In a .md file on another branch | /../main/assets/images/electrocat.png |
| In issues, pull requests and comments of the repository | ../blob/main/assets/images/electrocat.png?raw=true |
| In a .md file in another repository | /../../../../github/docs/blob/main/assets/images/electrocat.png|
| In issues, pull requests and comments of another repository |	../../../github/docs/blob/main/assets/images/electrocat.png?raw=true |
</p>
</details>

---

# LISTS

<details><summary>Unordered/ordered links</summary><p>
You can make an unordered list by preceding one or more lines of text with - or *.<br/>
example:

```
- HTML
- CSS
- JAVASCRIPT
```

- HTML
- CSS
- JAVASCRIPT

for an ordered list you use numbers

```
1. C
2. C++
3. C#
```

1. C
2. C++
3. C#

</p>
</details>

<details><summary>Nested Lists</summary><p>

## Nested Lists

you can create a nested list by using indenting one or more lists<br/>
example:

```
1. First list item
   - First nested list item
     - Second nested list item
```

1. First list item
   - First nested list item
     - Second nested list item

</p>
</details>

<details><summary>Task Lists</summary><p>

## Task lists

To create a task list, preface list items with a hyphen and space followed by [ ]. To mark a task as complete, use [x].
```
- [x] HTML
- [ ] CSS
- [ ] Javascript
````
- [x] HTML
- [ ] CSS
- [ ] Javascript

</p>
</details>

# Mentioning people and teams

use the @ with their user name or team name<br/>
example:

```
@CookedPotato-1428
```

@CookedPotato-1428

# Using emoji

you can an imoji by typing ` :EMOJICODE: ` <br/>
example:
```
thumbs up :+1:
```
thumbs up :+1:

# Footnotes<sup>taken directly from [GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) because i was having issues rendering the footnotes<sup>

You can add footnotes to your content by using this bracket syntax:
```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.

```
the footnote will render like this :
<img src="https://docs.github.com/assets/cb-6343/images/site/rendered-footnote.png" height="230" width="400" />
e
irrespective of where you put your derefenced footnote, it will always appear at the bottom


# Hiding contents

you hide contents just like how you comment in HTML
```
<!-- this wont show in the rendered Markdown-->
```

# Ignoring Markdown Formatting

to ignore the formating symbols use \ before the symbol<br/>
example:

```
Let's learn about \*Markdown files\* 

```
Let's learn about \*Markdown files\*

# Paragraphs and lines

to create a paragraph just leave a whole line before you text 

to create line spanning over the whole line use \___ or \----

```
---
```
---

# Tables

<details><summary>Creating</summary><p>

to create a table do the following

```
| item | price|
|---|---|
| apple | 0.8c  |
| pens  | 0.5c  |
|  notebook | 0.9c  |

```


| item | price|
|---|---|
| apple | 0.8c  |
| pens  | 0.5c  |
|  notebook | 0.9c  |

</p>
</details>

<details><summary>Alignment</summary><p>

## Alignment
 
 use : to denote the alignment 
 
 ```
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| deliciously  | cooked         | Potatoes      |
```

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| deliciously  | cooked         | Potatoes      |

</p>
</details>

# Creating collapsed sections 

use this syntax:

```
<details>
<summary> section </summary>
<p> hello </p>
</details>
```

<details>
<summary> section </summary>
<p> hello </p>
</details>

# Creating Code blocks

when creating code blocks addd the language name after the intial quotes to give it syntax highlighting <br/>
example:
````
```typescript
const newFunction =(name: string):string=>{
    return " hello there " + name ;
};
```
````

```typescript
const Hello = (name:string):string =>{
    return " hello there " + name ;
};
```

---
---

## Congrats you have made it to the end

### if you want more( which there is alot more, trust me i mean alot, you can draw 3d stuff here ) go the the [GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) for more info with the ` README.md ` for github as context or [Daring Fireball](https://daringfireball.net/projects/markdown/syntax#backslash) for every syntax relating to ` .md ` files
