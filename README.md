# How to write in Markdown, How to write Readme

<h2>What is Markdown?</h2>
<ol style="list-style-type: lower-latin;">
    <li>
        Markdown is a ightweight markup language that is used to format plain text documents.
    </li>
    <li>
        With the goal of providing a simple and human-readable way to format text that can be easily converted to HTML and other formats. Markdown is often used for writing documentation, readme files, and formatting text on the web.
    </li>
</ol>


<h2>Table of Content</h2>
<ol style="list-style-type: decimal-leading-zero;">
    <li><a href="#headings">Headings</a></li>
    <li><a href="#text-style">Text Style</a></li>
    <li><a href="#lists">Lists</a></li>
    <li><a href="#nested-lists">Nested Lists</a></li>
    <li><a href="#links">Links</a></li>
    <li><a href="#relative-links">Relative Links and Images</a></li>
    <li><a href="#code-and-syntax">Code and Syntax Highlighting</a></li>
    <li><a href="#quoting-text">Quoting Text</a></li>
    <li><a href="#color-model">Color model</a></li>
</ol>




<h2 id="headings">01. Headings</h2>
<p>You can create headings by using the "#" symbol, with one "#" for the highest level heading and up to six "#" symbols for lower-level headings.</p>

```markdown
    # H1
    ## H2
    ### H3
    #### H4
    ##### H5
    ###### H6
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="text-style">02. Text Style</h2>

```markdown
    Italics → _underscore_ or *Asterisk*
    Bold → __underscores__ or **Asterisk**
    Italics → and Bold **_Asterisk&Underscores_** | **Asterisk _Underscores_**
    Strikethrough → ~~Scratch this.~~
    Subscript → <sub>Subscript</sub>
    Superscript → <sup>Superscript</sup>
```
Italics → _underscore_ or *Asterisk*<br>
Bold → __underscores__ or **Asterisk**<br>
Italics and Bold → **_Asterisk&Underscores_** | **Asterisk _Underscores_**<br>
Strikethrough → ~~Scratch this.~~<br>
Subscript → <sub>Subscript</sub><br>
Superscript → <sup>Superscript</sup>

<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="lists">03. Lists</h2>

Unordered List with  `-` , `*`, or `+`.

```markdown
- John Smith
* Johan
+ Jefferson
```
- John Smith
* Johan
+ Jefferson

Ordered List with Numbers

```markdown
1. John Smith
1. Johan
1. Jefferson
```
1. John Smith
1. Johan
1. Jefferson

<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="nested-lists">04. Nested Lists</h2>

You can create a nested list by indenting one or more list items below another item.

```markdown
1. First List
  - First nested list [Press Space two times]
    - Second nested list [Press space four times]
```
1. First List
  - First nested list [Press Space two times]
    - Second nested list [Press space four times]

If you want to add a nested list under list number, for example, `200. List`, you will need to use 4 spaces. So, for the nested list, it needs minimum of 5 spaces to create it.
```markdown
200. List
     - asd
```
200. List
     - five [5 spaces]
       - seven [7 spaces]

<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="links">05. Links</h2>

```markdown
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[I'm a relative reference to other repository file](/../../../../(github-username)/(repositoryname)/blob/main/(file))

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
```

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[I'm a relative reference to other repository file](/../../../../jeffersonfed/jeffersonfed/blob/main/README.md)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="relative-links">06. Relative Links and Images</h2>
You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

Inline-style: 

```md
[alt-text](directory file / links)
EX:
    [Example 1](package.json)
    ![Example 2 Image](assets/pikachu.jpg)
```
[Example 1](package.json)

![Example 2 Image](assets/pikachu.png)

<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="code-and-syntax">07. Code and Syntax Highlighting</h2>
Code blocks are part of the Markdown, but syntax highlighting isn't.

```markdown
Inline `code` has `back-ticks around` it.
```
Inline `code` has `back-ticks around` it. 

<hr>
Blocks of code are either fenced by lines with three back-ticks ```, or are indented with four spaces. I recommend only using the fenced code blocks -- they're easier and only they support syntax highlighting.

<pre>
```js
var x = "jeffersonfed";
alert(x);
```
 
```python
x = "jeffersonfed"
print x
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```
</pre>

```js
var x = "jeffersonfed";
alert(x);
```
 
```python
x = "jeffersonfed"
print x
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```


<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="quoting-text">08. Quoting Text</h2>

You can quote text with `>`

```markdown
> This is quote text
```
> This is quote text

<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="color-model">09. Color Model</h2>

```markdown
The background color is `#00000` and the text color is `#fffff`
```

The background color is `#00000` and the text color is `#fffff`

<!-- 
====== Line ====== 
-->

 [hr-style]: https://capsule-render.vercel.app/api?type=rect&color=gradient&height=1.5