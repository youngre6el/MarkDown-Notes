# Markdown Notes
Markdown is used to write readmes and I will be using it to take notes on programming. 

Markdown, in comparison to HTML, is much easier to read and write. 

---

## Sections
- [Headers](#headers)
- [Quotes](#quotes)
- [Emphasis](#emphasis)
- [Horizontal Rule](#horizontal-rule)
- [Lists](#lists)
- [Links](#links)
- [Images](#images)
- [Code](#code)
- [Tables](tables)
- [Custom HTML](#custom-html)
- [Custom CSS](#custom-css)
- [Additional Resources](additional-resources)


---
 ## Headers
Headers are defined by the '#' symbol. One '#' for H1, two for H2, ect. 

> **TODO**. Create H1,H2,..H5
# Header 1
## Header 2
### Header 3
#### Header 4


---

## QUOTES

Quotes are defined by the '>' symbol.

<!--
    Example

    > This is an example quote

-->

> **TODO**. Create a quote

> "It is better to burn out than to fade away" - Kurt Cobain

You can combine a header with a quote.

<!--
    Example

    > # H1 Quote
-->

>**TODO**. Create an H2 quote.

> ## This is an H2 quote.

---

## Emphasis

Add emphasis with asteriks '*' and underscores '_'

Two before and after a section of text makes it bold. 

<!--

    Example
    **hey**
    __hey__

-->

**Bold Text**

__Bold Text with underline__

Using only one '*', '_', before and after makes it Italic. 

*hey*

_hey_

## Horizontal Rule

Can use any of the three to create a horizontal line

---
___
***


## Lists

Create unordered lists using '_', '*', '+'

- Thing one 
- Thing two
- Thing Three

You can use indent to create sublists

- Thing one
    - sub thing one
        - sub sub thing one


Create Ordered Lists using number prefix. 

1. First thing
2. Second thing 
3. Third thing 

---
## Links

Create a link by surrounding it with angle bracket. 

<!--

    Example

    <http://www.twitter.com>

-->

Create a Luink with text by surrouding text with brackets, [], and link immediately following with parenthesis ()

<!--

    Example

    [Re6el's Twitter Page](twitter.com/larevolutionn)


-->

> **TODO**. Create a Link with no text

<http://www.twitter.com>


> **TODO**. Create a Link with text

[Re6el's Twitter Page](http://twitter.com/larevolutionn)

What if you need to update your link. And you need to update it at many different locations. 

Like in programming, you can create a variable for a link. Therefore, you will only need to update the 1 variable that you used for the link. 

<!--
    Example

    [1]: http://twitter.com

-->

[Key]: http://twitter.com/larevolutionn

Now you can use the reference style link by using your text inside the brackets followed by the link 'key' inside of bracket.

[Re6el's Twitter Page][Key]

---

## Images

Defining images is similar to defining a link, except you prefix it with '!'.

<!--
    Example
    ![Picture of Itachi](https://staticg.sportskeeda.com/editor/2022/01/b0755-16425315464091-1920.jpg)

-->

You can use references with images as well. 

[itachi]: https://staticg.sportskeeda.com/editor/2022/01/b0755-16425315464091-1920.jpg

![Picture of Itachi][Itachi]

## Code

You can do inline code with `backticks` (``)

Here is some code inline `var item = {}`

You can do blocks of code by surrouding it with 3 bacticks (`` ``` ``` ``)


<!--

    Example

```
    var num = 0;
    var num2 = 0;

    ```

-->

``` 
    var num = 0;
    var num2 = 0;
```

The above does not give language specific highlighting. You can specify the programming language immediately following the opening 3 brackets. You should see a difference in highlighting. 

<!--

    Example

```javascript
    var num = 0;
    var num2 = 0;

    ```

-->


```javascript 
    var num = 0;
    var num2 = 0;
```


```html
    <div>
        <p>This is an html example</p>
    </div>
```

---
## Tables 

Tables are useful for displaying rows and columns of data. Column headers can be defined in between pipes (|). Headers are separated from table content with a row of dashes (-) (still seoerated by pipes), there must be at least 3 dashes between each header. The row data follows beneath (still seperated by pipes)


<!--
    Example

    | Header 1   | Header 2  | Header 3   |
    |-----       |-----      |-----       |
    | Row 1 Col 1| Row 1 Col2| Row 1 Col 3|   

-->


| Header 1   | Header 2  | Header 3   |
|-----       |-----      |-----       |
| Col 1      | Col2      | Col 3      |
| Col 1      | Col2      | Col 3      |
| Col 1      | Col2      | Col 3      |
| Col 1      | Col2      | Col 3      |

You can also align (Center, left, right) the text in a column by using colons (:) in the line breaks between headers and rows. No colon means the default **left alignmnet**. Colons on each side signifies **center alignment**. Trailing colon means **right alignment**. 


<!--
| Header 1   | Header 2  | Header 3   |
|-----       |:-----:    |-----:      |
| Col 1      | Col2      | Col 3      |
| Col 1      | Col2      | Col 3      |
| Col 1      | Col2      | Col 3      |
| Col 1      | Col2      | Col 3      |


-->

| Header 1   | Header 2  | Header 3|
| -----       |:-----: | ----: |
| Left align | Centered  | Right align |
| Left align | Centered  | Right align |
| Left align | Centered  | Right align |
| Left align | Centered  | Right align |


## Custom HTML

Since MarkDown gets automatically converterd to HTML, you can add raw HTML directly to your markdown. 

```html
<p>Sample HTML Div</p>
```

Creates this

<p>Sample HTML Div</p>

<h1>HTML Header</h1>

---

## Custom CSS

You can also add custom CSS to your MarkDown to add additional styling to your document. You can also include CSS by including a style tag. 

```html
    <style>
        body {
            color:red;
        }
    </style>
```

<!--

JUST SOME FORMATTING 

-->
<style>

    h2 {
        color: pink

    }
</style>
---



