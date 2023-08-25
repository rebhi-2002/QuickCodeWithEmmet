# Table of Contents

- [Table of Contents](#table-of-contents)
  - [Learn Emmet Tutorial:](#learn-emmet-tutorial)
  - [How to Type HTML and CSS Faster with Emmet](#how-to-type-html-and-css-faster-with-emmet)
  - [First: HTML Emmet:](#first-html-emmet)
    - [\[01\] `!`](#01-)
    - [\[02\] `h1.title`](#02-h1title)
    - [\[03\] `.title`](#03-title)
    - [\[04\] `p#top`](#04-ptop)
    - [\[05\] `#first`](#05-first)
    - [\[06\] `input.class1.class2.class3#search`](#06-inputclass1class2class3search)
    - [\[07\] `h1{Learn Emmet}`](#07-h1learn-emmet)
    - [\[08\] `div>ul>li`](#08-divulli)
    - [\[09\] `div>ul>li*9`](#09-divulli9)
    - [\[10\] `div>ul>li{Item}*5`](#10-divulliitem5)
    - [\[11\] `div>ul>li{Item $}*5`](#11-divulliitem-5)
    - [\[12\] `ul>li#item${Item $}*5`](#12-ulliitemitem-5)
    - [\[13\] `div#first+div#second`](#13-divfirstdivsecond)
    - [\[14\] `div>h1+p+p`](#14-divh1pp)
    - [\[15\] `div>h1+ul>li>a`](#15-divh1ullia)
    - [\[16\] `div>h1+ul>li>a+p`](#16-divh1ulliap)
    - [\[17\] `div>h1+ul>li>a^p`](#17-divh1ulliap)
    - [\[18\] `div>h1+ul>li>a^^p`](#18-divh1ulliap)
    - [\[19\] `div>h1+(ul>li>a)+p`](#19-divh1ulliap)
    - [\[20\] `div>(header>ul>li*2>a)+footer>p`](#20-divheaderulli2afooterp)
    - [\[21\] `div>(section.section$>h1.heading$+p*2)*5`](#21-divsectionsectionh1headingp25)
    - [\[22\] `p[title]`](#22-ptitle)
    - [\[23\] `p[title=hi]`](#23-ptitlehi)
    - [\[24\] `a[href=https://example.com/$]*5`](#24-ahrefhttpsexamplecom5)
    - [\[25\] `img[title]`](#25-imgtitle)
    - [\[26\] `lorem`](#26-lorem)
    - [\[27\] `lorem10`](#27-lorem10)
    - [\[28\] `div>(p>lorem10)*3`](#28-divplorem103)
  - [Second: CSS Emmet:](#second-css-emmet)
    - [\[01\] `c:red`](#01-cred)
    - [\[02\] `c#0`](#02-c0)
    - [\[03\] `c#f`](#03-cf)
    - [\[04\] `c#2a`](#04-c2a)
    - [\[05\] `bg#0`](#05-bg0)
    - [\[06\] `bg:white`](#06-bgwhite)
    - [\[07\] `m10`](#07-m10)
    - [\[08\] `m10em`](#08-m10em)
    - [\[09\] `mt10`](#09-mt10)
    - [\[10\] `mr10`](#10-mr10)
    - [\[11\] `ml10`](#11-ml10)
    - [\[12\] `mb10`](#12-mb10)
    - [\[13\] `p10`](#13-p10)
    - [\[14\] `t10`](#14-t10)
    - [\[15\] `b10`](#15-b10)
    - [\[16\] `l10`](#16-l10)
    - [\[17\] `r10`](#17-r10)
    - [\[18\] `db`](#18-db)
    - [\[19\] `di`](#19-di)
    - [\[20\] `dib`](#20-dib)
    - [\[21\] `dn`](#21-dn)
    - [\[22\] `dg`](#22-dg)
    - [\[23\] `df`](#23-df)
    - [\[24\] `aic`](#24-aic)
    - [\[25\] `jcc`](#25-jcc)
    - [\[26\] `aifs`](#26-aifs)
    - [\[27\] `jcsb`](#27-jcsb)
    - [\[28\] `w100`](#28-w100)
    - [\[29\] `h100`](#29-h100)
    - [\[30\] `tac`](#30-tac)
    - [\[31\] `taj`](#31-taj)
  - [References:](#references)

## Learn Emmet Tutorial:

======================

## How to Type HTML and CSS Faster with Emmet

## First: HTML Emmet:

### [01] `!`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>How to Type HTML and CSS Faster with Emmet</title>
  </head>
  <body>
    |
  </body>
</html>
```

### [02] `h1.title`

```html
<h1 class="title">|</h1>
```

### [03] `.title`

```html
<div class="title">|</div>
```

### [04] `p#top`

```html
<p id="top">|</p>
```

### [05] `#first`

```html
<div id="first">|</div>
```

### [06] `input.class1.class2.class3#search`

```html
<input type="text" class="class1 class2 class3" id="search" />
```

### [07] `h1{Learn Emmet}`

```html
<h1>Learn Emmet</h1>
```

### [08] `div>ul>li`

```html
<div>
  <ul>
    <li>|</li>
  </ul>
</div>
```

### [09] `div>ul>li*9`

```html
<div>
  <ul>
    <li>|</li>
    <li>|</li>
    <li>|</li>
    <li>|</li>
    <li>|</li>
    <li>|</li>
    <li>|</li>
    <li>|</li>
    <li>|</li>
  </ul>
</div>
```

### [10] `div>ul>li{Item}*5`

```html
<div>
  <ul>
    <li>Item</li>
    <li>Item</li>
    <li>Item</li>
    <li>Item</li>
    <li>Item</li>
  </ul>
</div>
```

### [11] `div>ul>li{Item $}*5`

```html
<div>
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
    <li>Item 4</li>
    <li>Item 5</li>
  </ul>
</div>
```

### [12] `ul>li#item${Item $}*5`

```html
<ul>
  <li id="item1">Item 1</li>
  <li id="item2">Item 2</li>
  <li id="item3">Item 3</li>
  <li id="item4">Item 4</li>
  <li id="item5">Item 5</li>
</ul>
```

### [13] `div#first+div#second`

```html
<div id="first">|</div>
<div id="second">|</div>
```

### [14] `div>h1+p+p`

```html
<div>
  <h1>|</h1>
  <p>|</p>
  <p>|</p>
</div>
```

### [15] `div>h1+ul>li>a`

```html
<div>
  <h1>|</h1>
  <ul>
    <li>
      <a href="|">|</a>
    </li>
  </ul>
</div>
```

### [16] `div>h1+ul>li>a+p`

```html
<div>
  <h1>|</h1>
  <ul>
    <li>
      <a href="|">|</a>
      <p>|</p>
    </li>
  </ul>
</div>
```

### [17] `div>h1+ul>li>a^p`

```html
<div>
  <h1>|</h1>
  <ul>
    <li><a href="|">|</a></li>
    <p>|</p>
  </ul>
</div>
```

### [18] `div>h1+ul>li>a^^p`

```html
<div>
  <h1>|</h1>
  <ul>
    <li><a href="|">|</a></li>
  </ul>
  <p>|</p>
</div>
```

### [19] `div>h1+(ul>li>a)+p`

```html
<div>
  <h1>|</h1>
  <ul>
    <li><a href="|">|</a></li>
  </ul>
  <p>|</p>
</div>
```

### [20] `div>(header>ul>li*2>a)+footer>p`

```html
<div>
  <header>
    <ul>
      <li><a href="|">|</a></li>
      <li><a href="|">|</a></li>
    </ul>
  </header>
  <footer>
    <p>|</p>
  </footer>
</div>
```

### [21] `div>(section.section$>h1.heading$+p*2)*5`

```html
<div>
  <section class="section1">
    <h1 class="heading1">|</h1>
    <p>|</p>
    <p>|</p>
  </section>
  <section class="section2">
    <h1 class="heading2">|</h1>
    <p>|</p>
    <p>|</p>
  </section>
  <section class="section3">
    <h1 class="heading3">|</h1>
    <p>|</p>
    <p>|</p>
  </section>
  <section class="section4">
    <h1 class="heading4">|</h1>
    <p>|</p>
    <p>|</p>
  </section>
  <section class="section5">
    <h1 class="heading5">|</h1>
    <p>|</p>
    <p>|</p>
  </section>
</div>
```

### [22] `p[title]`

```html
<p title="|">|</p>
```

### [23] `p[title=hi]`

```html
<p title="hi">|</p>
```

### [24] `a[href=https://example.com/$]*5`

```html
<a href="https://example.com/1">|</a>
<a href="https://example.com/2">|</a>
<a href="https://example.com/3">|</a>
<a href="https://example.com/4">|</a>
<a href="https://example.com/5">|</a>
```

### [25] `img[title]`

```html
<img src="|" alt="|" title="|" />
```

### [26] `lorem`

```html
Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias dicta rem
temporibus consectetur beatae commodi vero impedit tempora. Nihil harum porro
enim expedita eos, ratione distinctio iusto quasi repellendus. Veniam?
```

### [27] `lorem10`

```html
Lorem ipsum dolor, sit amet consectetur adipisicing elit. Placeat, optio.
```

### [28] `div>(p>lorem10)*3`

```html
<div>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam, possimus.
  </p>
  <p>
    Facilis qui, deleniti impedit animi aperiam incidunt quasi quibusdam
    ducimus.
  </p>
  <p>
    Sunt, cupiditate? Ea itaque, dolorum consequatur delectus voluptatibus
    temporibus saepe!
  </p>
</div>
```

<br />

---

<br />

## Second: CSS Emmet:

### [01] `c:red`

```css
color: red;
```

### [02] `c#0`

```css
color: #000;
```

### [03] `c#f`

```css
color: #fff;
```

### [04] `c#2a`

```css
color: #2a2a2a;
```

### [05] `bg#0`

```css
background: #000;
```

### [06] `bg:white`

```css
background: white;
```

### [07] `m10`

```css
margin: 10px;
```

### [08] `m10em`

```css
margin: 10em;
```

### [09] `mt10`

```css
margin-top: 10px;
```

### [10] `mr10`

```css
margin-right: 10px;
```

### [11] `ml10`

```css
margin-left: 10px;
```

### [12] `mb10`

```css
margin-bottom: 10px;
```

### [13] `p10`

```css
padding: 10px;
```

### [14] `t10`

```css
top: 10px;
```

### [15] `b10`

```css
bottom: 10px;
```

### [16] `l10`

```css
left: 10px;
```

### [17] `r10`

```css
right: 10px;
```

### [18] `db`

```css
display: block;
```

### [19] `di`

```css
display: inline;
```

### [20] `dib`

```css
display: inline-block;
```

### [21] `dn`

```css
display: none;
```

### [22] `dg`

```css
display: grid;
```

### [23] `df`

```css
display: flex;
```

### [24] `aic`

```css
align-items: center;
```

### [25] `jcc`

```css
justify-content: center;
```

### [26] `aifs`

```css
align-items: flex-start;
```

### [27] `jcsb`

```css
justify-content: space-between;
```

### [28] `w100`

```css
width: 100px;
```

### [29] `h100`

```css
height: 100px;
```

### [30] `tac`

```css
text-align: center;
```

### [31] `taj`

```css
text-align: justify;
```

## References:

============

**Efficient Writing of HTML & CSS With Faster Emmet:**

1. [_Cheat Sheet PDF Download_](https://github.com/rebhi-2002/QuickCodeWithEmmet/blob/main/cheatsheet-a5.pdf)
2. [_Emmet Cheat Sheet_](https://docs.emmet.io/cheat-sheet/)
3. [_Write HTML & CSS Faster with Emmet: Cheat Codes_](https://www.freecodecamp.org/news/write-html-css-faster-with-emmet-cheat-codes/)
4. [_Emmet in Visual Studio Code_](https://code.visualstudio.com/docs/editor/emmet)

**How to Write and Format Basic Syntax Code in Markdown:**

1. [_Markdown Cheat Sheet_](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
2. [_Getting Started with Writing and Formatting on GitHub_](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
3. [_Markdown Guide: Basic Syntax_](https://www.markdownguide.org/basic-syntax/)
4. [_How to Format Code in Markdown_](https://www.freecodecamp.org/news/how-to-format-code-in-markdown/)
5. [_Markdown in Visual Studio Code_](https://code.visualstudio.com/docs/languages/markdown/)

<!-- # QuickCodeWithEmmet
Enhance Your HTML &amp; CSS Workflow with Efficient Emmet Code Writing -->
