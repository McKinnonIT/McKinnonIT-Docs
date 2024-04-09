# Markdown Guide
Markdown is a lightweight markup language with plain-text formatting syntax. It is designed to be easy to read and easy to write, making it a popular choice for creating content for the web. In this guide, we'll cover everything you need to know to get started with Markdown, from basic syntax to more advanced techniques. Whether you're a beginner or an experienced user looking to refresh your skills, this guide will provide you with the knowledge and tools you need to effectively use Markdown in your documentation and projects.

## Headings
In Markdown, you can create headings by using hash symbols (#). The number of hash symbols indicates the level of the heading, with one hash symbol representing the highest level of heading and six hash symbols representing the lowest level. For example:

``` md title="Headings Markdown Code"
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
!!! abstract "Heading Example"

    # H1
    ## H2
    ### H3
    #### H4
    ##### H5
    ###### H6

## Formatting Text
Markdown offers simple and intuitive syntax for formatting text in various styles. You can easily make your text **bold**, *italic*, or even ~~strikethrough~~ with just a few characters. Enclosing your text in double asterisks (`**`) or underscores (`__`) creates **bold** text, while single asterisks (`*`) or underscores (`_`) render text in *italics*. To strike through text, simply use double tildes (`~~`). Additionally, inline code can be highlighted by enclosing it in backticks (\`). For hyperlinks, enclose the link text in square brackets followed by the URL in parentheses. Images can be included by preceding the alt text with an exclamation mark, followed by the image URL in parentheses. Markdown's straightforward syntax for text formatting allows for clear and concise communication in your documents.

``` md title="Bold Markdown Code"
**Bold Text**
__Bold Text__
```
!!! abstract "Bold Example"

    **Bold Text**

``` md title="Italic Markdown Code"
*Italic Text*
_Italic Text_
```
### Italic Example
>*Italic Text*

``` md title="Strikethrough Markdown Code"
~~Strikethrough Text~~
```
### Strikethrough Example
>~~Strikethrough Text~~

``` md title="Inline Code Markdown Code"
`Inline Code`
```
### Inline Code Example
>`Inline Code`

``` md title="Link Markdown Code"
[Link Text](https://example.com)
```
### Link Example
>[Link Text](https://example.com)

``` md title="Image Markdown Code"
![Image Alt Text](image.jpg)
```
### Image Example
>![Image Alt Text](image.jpg)

``` md title="Blockquote Text Markdown Code"
> Blockquote Text
```
### Blockquote Example
> Blockquote Text

## Tables

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

Adding a pipe `|` in a cell :

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | \|

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  |  \| 
```

Left, right and center aligned table

Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell

```
Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell
```

`code()`

    Markup :  `code()`

```javascript
    var specificLanguage_code = 
    {
        "data": {
            "lookedUpPlatform": 1,
            "query": "Kasabian+Test+Transmission",
            "lookedUpItem": {
                "name": "Test Transmission",
                "artist": "Kasabian",
                "album": "Kasabian",
                "picture": null,
                "link": "http://open.spotify.com/track/5jhJur5n4fasblLSCOcrTp"
            }
        }
    }
```

    Markup : ```javascript
             ```

* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2

~~~
 Markup : * Bullet list
              * Nested bullet
                  * Sub-nested bullet etc
          * Bullet list item 2

-OR-

 Markup : - Bullet list
              - Nested bullet
                  - Sub-nested bullet etc
          - Bullet list item 2 
~~~

1. A numbered list
    1. A nested numbered list
    2. Which is numbered
2. Which is numbered

~~~
 Markup : 1. A numbered list
              1. A nested numbered list
              2. Which is numbered
          2. Which is numbered
~~~

- [ ] An uncompleted task
- [x] A completed task

~~~
 Markup : - [ ] An uncompleted task
          - [x] A completed task
~~~

- [ ] An uncompleted task
    - [ ] A subtask

~~~
 Markup : - [ ] An uncompleted task
              - [ ] A subtask
~~~

> Blockquote
>> Nested blockquote

    Markup :  > Blockquote
              >> Nested Blockquote

_Horizontal line :_
- - - -

    Markup :  - - - -

_Image with alt :_

![picture alt](http://via.placeholder.com/200x150 "Title is optional")

    Markup : ![picture alt](http://via.placeholder.com/200x150 "Title is optional")

Foldable text:

<details>
  <summary>Title 1</summary>
  <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
</details>
<details>
  <summary>Title 2</summary>
  <p>Content 2 Content 2 Content 2 Content 2 Content 2</p>
</details>

    Markup : <details>
               <summary>Title 1</summary>
               <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
             </details>

```html
<h3>HTML</h3>
<p> Some HTML code here </p>
```

Link to a specific part of the page:

[Go To TOP](#TOP)
   
    Markup : [text goes here](#section_name)
              section_title<a name="section_name"></a>    

Hotkey:

<kbd>⌘F</kbd>

<kbd>⇧⌘F</kbd>

    Markup : <kbd>⌘F</kbd>

Hotkey list:

| Key | Symbol |
| --- | --- |
| Option | ⌥ |
| Control | ⌃ |
| Command | ⌘ |
| Shift | ⇧ |
| Caps Lock | ⇪ |
| Tab | ⇥ |
| Esc | ⎋ |
| Power | ⌽ |
| Return | ↩ |
| Delete | ⌫ |
| Up | ↑ |
| Down | ↓ |
| Left | ← |
| Right | → |

Emoji:

:exclamation: Use emoji icons to enhance text. :+1:  Look up emoji codes at [emoji-cheat-sheet.com](http://emoji-cheat-sheet.com/)

    Markup : Code appears between colons :EMOJICODE:
