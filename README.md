<div align="center">
<img src="https://elzero.org/wp-content/themes/elzero/imgs/logo.png" alt='source' width="200"/>

# Elzero Web School

[HTML Course](https://www.youtube.com/playlist?list=PLDoPjvoNmBAw_t_XWUFbBX-c9MafPk9ji)
</div>

## lesson_00

Html Usage
- Front End
- Back End
- Report

-------------------------

## lesson_05

```
<!DOCTYPE html>
```
This is not an html tag 
but it used to tell browser to render in standard mode
not quirks mode

-------------------------

## lesson_07

h1 - h6

It prefered that h1 must written only once
    to be friendly with search engine
```
<h1>Book Store</h1>
```
don't change hierarchy for example but h2 in h3

-------------------------

## lesson_10

We use paragraph to make new line between elements
it separete text in new lines because it's a block 

-------------------------

## Assignments

```
<hr>
```
We use that to make lines between elements like Divider() in flutter

-------------------------

## lesson_11

b => bold text
```
<b>Book Store</b>
```

strong => important text
```
<strong>Book Store</strong>
```

i => italic font
```
<i>Book Store</i>
```

em => emphasized text do what italic do
```
<em>Book Store</em>
```

mark => mark text or higlight it
```
<mark>Book Store</mark>
```

u => underline text
```
<u>Book Store</u>
```

small => make a smaller text
```
<small>Book Store</small>
```

del => deleted text search engine dosen't like text change and the site become not trusted 
        so we but old text in del tag or we can use it with discounted price
```
<del>Book Store</del>
<p><del>100</del> 80</p>
```

ins => to tell user that text in new
```
<p><ins>100</ins> 80</p>
```

sub => subscript we use it like 2 in H2O
```
<p>H<sub>2</sub>O</p>
```

sup => superscript we use it like 10^2
```
<p>10<sup>2</sup></p>
```

-------------------------

## lesson_12

```
<a href="#URL" target="_blank" title="#title" >#Text</a>
```

URl: url u want to go to
    - u can feed it with complete url
    - certin page in this website like about.html
    - go to certin element by its id like #id
    - go to email by type mailto:test@test.test

title: tooltip when u hover the link
Text: apperaing text to user

```
target="_blank" 
```
if exist the url will open in new page

-------------------------

## lesson_13

```
<img src="book.png" alt="">
```

Alt text will show when image not exsist

-------------------------

## lesson_14

### ul: unorded list
```li```: list item

### ol: oreded list
-    reversed: reverse list order
-    start: define where numbering start from
     - we can define value in li element to start count from instead of defining start in ol element
            
-    type: type of numbering alphapet or number or romanic

### dl: Description list
```dt```: Term
```dd```: Term description

-------------------------

## lesson_15

### Table

don't use table attrbutes

```table``` : table element
```caption```: caption for table appear top of table

```thead```: table header
```tbody```: table body
```tfoot```: table foot

```th```: table head cell
```td```: table cell
```tr```: table row

-------------------------

## lesson_16

```
<span></span>
```
```span```: used to hold words in paragraph to style it

```
<br>
```
``br``: break make new line

```
<hr>
```
```hr```: horizontal rule used to make  lines

-------------------------

## lesson_17

```
<div></div>
```
```div```: is used as a container in page
don't use div to hold a text use ```<p>``` insted

-------------------------

## lesson_18

Entities used if u want to show reserved word in your text

```&lt;p&gt;``` to show ```<pr>```

and there is more and more

<a href="https://www.freeformatter.com/html-entities.html">See more Here</a>

-------------------------

## lesson_19

Semantic Elements : u can consider it like div but with a charctarestic name

```
<header>
<nav>
<section>
<main>
<footer>
```

-------------------------

## lesson_22

```
<audio>
```
audio used to play sounds
u can use source i

useful atterb
- ```controls```: to show audio controls
- ```autoplay```: auto play audio but this dosen't support in some browser
- ```loop```: loop audio
- ```muted```: mute audio

u can use  ```<source>``` in audio element instead of src
u can use many source with diffrent type and the browser will choose the MMETYPE it support
u can leave msg will show if the browser dosen't support any type

-------------------------

## lesson_23

```
<video>
```

have same attrb as audio also have a
```poster``` to show image until video laod

you can user ```<track>``` to add subtitles like that

```
<video controls>
<track srv="abc_en.vtt" kind="subtitles srclang="en" label="English">
</video>
```

-------------------------

## lesson_24_32

### Input & Form

```<form></form>```
- to make froms in your website
- put all related inputs in it

- action
  - the page data will be sent to
  - if it empty or dosen't exsist data will be sent to current page

- ```target="_blank"``` to send data  in new page
  
- method
  - ```method="POST"``` send data but quiery param dosen't show in url
  - ```method="GET"``` send data but quiery param show in url

```<label></label>```

- to give somthing a label
- ```for="##"``` connect label with element by id

--- 

```<input>```

- type
  - ```type="text" ``` for most inputs
  - ```type="search" ``` like text but add a clear button to field
  - ```type="file" ``` to uplaod files
  - ```type="url" ``` to input urls
  - ```type="date" ``` to input date
  - ```type="time" ``` to input time
  - ```type="datetime" ``` to input date and time
  - ```type="url" ``` to input urls
  - ```type="password" ``` for password field
  - ```type="email" ``` for email field
  - ```type="submit" ``` to submit data from from
  - ```type="reset" ``` to reset data in from
  - ```type="color" ``` to select color and get hash value of it
  - ```type="range" ``` like slider
    - U can define min max step
  - ```type="number" ``` to input number only
    - U can define min max step
  - ```type="list" ``` to input urls
    - like select but searchable
    - ```
        <input type="list" name="prog" list="proglang">
                <datalist id="proglang">
                    <option value="c#">
                    <option value="c++">
                    <option value="c">
                </datalist>
        ```

---

- required
  - to mark your input as required

- hidden
  - to hide certin input but can be shown in inspector

- value
  - to put a default value
  - if you use it with input with ```type="submit" ``` the button name will change

- palceholder
  - like lable put inside the filed

- disabled
  - the input greyed out and data won't be send 

- readonly
  - non changing input but u can copy it and will be send

- autofocus
  - autofocus certin input

- minlength
  - to specify minimnum length of char for example password 

- maxlength
  - to specify max length of char for example bio 

- novalidate
  - to ignore validation

---

```
<select></select>
```
to select from multipule options
- ```multipule``` user can select multipule options by click ctrl and select

```
<select id="nation">
        <option value="EG">EGYPT</option>
        <option value="UK">UNITED KINGDOM/option>
        <option value="Ch">CHINES</option>
</select>
```

```
<option value="EG">EGYPT</option>
```
- ```selected``` to select the current option
- ```value``` the value which will be sent
- u can add option tag inside ```<optgroup></optgroup>```
  - to classify your option and add ```label``` param to optgroup to name the collection

all inputs are self closed tag except ```<textarea></textarea>```

-------------------------

## lesson_33

```
<q>This quote</q>
```
  - write quote between quotation
  - inline element

```
<blockquote>This blockquote</blockquote>
```
  - write quote with magin and some default style
  - block element

```
<wbr>
```
line break opportunity
  - break text

```
<bdi>
```
bidirectional isolation
  - isolate elemet from page direction
  - it useful when write mixed lang text

```
<p> <bdi>سلام</bdi> hello 2</p>
<p> سلام hello 2</p>
```

-------------------------

## lesson_33

```
<code></code>
```
- to handle code and u can customize how it will be formatted

```
<pre></pre>
```
- pre formatted text all u write will display the same

```
<ifram></iframe>
```
- is used to include page from out source any url
- or from html page
