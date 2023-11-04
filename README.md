<div align="center">

[![](https://komarev.com/ghpvc/?username=jeffersonfed&label=Profile%20Visits&color=blue&style=plastic)](#top)
[![Sponsor](https://img.shields.io/badge/SPONSOR-30363D?style=plastic&logo=GitHub-Sponsors&logoColor=#white)](https://ko-fi.com/jeffersonfed)

</div>

# How to write in Markdown

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
    <li><a href="#quoting-text">Blockquotes</a></li>
    <li><a href="#footnotes">Footnotes</a></li>
    <li><a href="#inline-html">Inline HTML</a></li>
    <li><a href="#horizontal-rule">Horizontal Rule</a></li>
    <li><a href="#line-breaks">Line Breaks</a></li>
    <li><a href="#embed">Embed Videos</a></li>
</ol>
    <h2>Playing around with markdown and html elements Reference</h2>
<ol style="list-style-type: decimal-leading-zero;">
    <li><a href="#drop-down">Drop Down using Details Tag</a></li>

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

<h2 id="quoting-text">08. Blockquotes</h2>

You can quote text with `>`

```markdown
> This is quote text

> First Line
> Second Line
```
> This is quote text

> First Line
> Second Line

<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="footnotes">09. Footnotes</h2>

```markdown
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
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.


<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="tables">10. Tables</h2>

```markdown
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="inline-html">11. Inline HTML</h2>

```html
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
```
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="horizontal-rule">12. Horizontal Rule</h2>

```markdown
Three or more...

---

Hyphens

***

Asterisks

___

Underscores
```
Three or more...

---

Hyphens

***

Asterisks

___

Underscores

<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="line-breaks">13. Line Breaks</h2>

```markdown
Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.
```

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

<h2 align = "center";>
	
![<hr />][hr-style]<br />
</h2>

<h2 id="embed">14. Embed Videos</h2>
They can't be added directly but you can add an image with a link to the video like this:

```markdown
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
```
or in markdown
```markdown
[![alt-text](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
```

<h2 align = "center";>
	
![<hr />](https://capsule-render.vercel.app/api?type=rect&color=gradient&height=8)<br />

Playing around with markdown and html elements Reference
</h2>


<h2 id="drop-down">01. Drop down using Details Tag</h2>

<details>
<summary>
<b>Frameworks, Platforms and Libraries</b>
</summary>
<br />

| | | | | |
| - | - | - | - | - |
| Alpine.js     | [ ![Alpine JS][alpinejs-badge] ][alpinejs-link] | |  Astro  | [ ![Astro][astro-badge] ][astro-link] 
| Bootstrap | [ ![Bootstrap][bootstrap-badge] ][bootstrap-link] | | Font Awesome     | [ ![Font Awesome][fontawesome-badge] ][fontawesome-link] |
| Github Pages     | [ ![Github Pages][githubpages-badge] ][githubpages-link] | | Jekyll | [ ![Jekyll][jekyll-badge] ][jekyll-link] |
| JQuery | [ ![JQuery][jquery-badge] ][jquery-link] | | Next.js | [ ![NextJS][nextjs-badge] ][nextjs-link] |
| Node.js | [ ![NodeJS][nodejs-badge] ][nodejs-link] | | NPM | [ ![NPM][npm-badge] ][npm-link] |
| PNPM | [ ![PNPM][pnpm-badge] ][pnpm-link] | | React.js | [ ![React][react-badge] ][react-link] |
| React Router | [ ![React Router][reactrouter-badge] ][reactrouter-link] | | Redux | [ ![Redux][redux-badge] ][redux-link] |
| SASS | [ ![SASS][sass-badge] ][sass-link] | | Tailwind CSS | [ ![Tailwind][tailwind-badge] ][tailwind-link] |
| Vite | [ ![Vite][vite-badge] ][vite-link] | | Vue.js | [ ![Vue][vue-badge] ][vue-link] |
| Yarn | [ ![Yarn][yarn-badge] ][yarn-link] |
</details>

<details>
<summary>
<b>Example 2</b>
</summary>


<table>
<tbody>

<tr>
  <td>
  <details>
  <summary>
  <code>Hosting/Saas</code>
  </summary>
  
  ```
  Netlify              :: Desc
  Vercel               :: Desc
  ```

  </details>
  </td>
  <td>

  [ ![Netlify][netlify-badge] ][netlify-link]
  [ ![Vercel][vercel-badge] ][vercel-link]
  </td>
</tr>
<tr>
  <td>
  <details>
  <summary>
  <code>Version Control</code>
  </summary>
  
  ```
  Git               :: Desc
  Github            :: Desc
  ```

  </details>
  </td>
  <td>

  [ ![Git][git-badge] ][git-link]
  [ ![Github][github-badge] ][github-link]

  </td>
</tr>
</tbody>
</table>
</details>

<details>
<summary>
<i>Press me</i>
</summary>
<br />

> Yey, you pressed it

`ex` Ex 1, Ex 2, Ex 3

- html details tag

</details>

<h2 align = "center";>
	
![<hr />](https://capsule-render.vercel.app/api?type=rect&color=gradient&height=8)<br />
</h2>



<!-- 
====== Line ====== 
-->

 [hr-style]: https://capsule-render.vercel.app/api?type=rect&color=gradient&height=1.5



 <!-- ------------------------------------ -->
<!-- 
====== Tech Stack ====== 
-->
<!-- Wakatime -->
[wakatime-badge]: https://img.shields.io/badge/WakaTime-000000?style=for-the-badge&logo=WakaTime&logoColor=white
[wakatime-link]: https://wakatime.com

<!-- Github Action -->
[githubaction-badge]: https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white
[githubaction-link]: https://github.com/features/actions

<!-- MYSQL -->
[mysql-badge]: https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white
[mysql-link]: https://www.mysql.com

<!-- After Effects -->
[aftereffects-badge]: https://img.shields.io/badge/After%20Effects-31A8FF?style=for-the-badge&logo=Adobe%20after%20effects&logoColor=black
[aftereffects-link]: https://www.adobe.com/products/aftereffects/campaign/pricing.html?sdid=L3XTTPNV&mv=search&mv2=paidsearch&ef_id=Cj0KCQjwy4KqBhD0ARIsAEbCt6gopXRRt3qDcExi234ozoP4GIX_5K2nlahEFBOD9y5sYYCbj7qnHzAaAkOBEALw_wcB%3AG%3As&s_kwcid=AL%213085%213%21636707352609%21e%21%21g%21%21after+effects%21703952805%2138400810418&gclid=Cj0KCQjwy4KqBhD0ARIsAEbCt6gopXRRt3qDcExi234ozoP4GIX_5K2nlahEFBOD9y5sYYCbj7qnHzAaAkOBEALw_wcB

<!-- Canva -->
[canva-badge]: https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white
[canva-link]: https://www.canva.com

<!-- AlpineJS -->
[alpinejs-badge]: https://img.shields.io/badge/Alpine%20JS-black?style=for-the-badge&logo=alpinedotjs&logoColor=8BC0D0
[alpinejs-link]: https://alpinejs.dev

<!-- Astro -->
[astro-badge]: https://img.shields.io/badge/Astro-0C1222?style=for-the-badge&logo=astro&logoColor=FDFDFE
[astro-link]: https://astro.build

<!-- Bootstrap -->
[bootstrap-badge]: https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white
[bootstrap-link]: https://getbootstrap.com

<!-- Font Awesome -->
[fontawesome-badge]: https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white
[fontawesome-link]: https://fontawesome.com

<!-- Github Pages -->
[githubpages-badge]: https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=GitHub%20Pages&logoColor=white
[githubpages-link]: https://pages.github.com

<!-- Jekyll -->
[jekyll-badge]: https://img.shields.io/badge/Jekyll-CC0000?style=for-the-badge&logo=Jekyll&logoColor=white
[jekyll-link]: https://jekyllrb.com

<!-- Jquery -->
[jquery-badge]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[jquery-link]: https://jquery.com

<!-- NextJS -->
[nextjs-badge]: https://img.shields.io/badge/next%20js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[nextjs-link]: https://img.shields.io/badge/next%20js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white

<!-- NodeJS -->
[nodejs-badge]: https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white
[nodejs-link]: https://nodejs.org/en

<!-- NPM -->
[npm-badge]: https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white
[npm-link]: https://www.npmjs.com

<!-- PNPM -->
[pnpm-badge]: https://img.shields.io/badge/pnpm-yellow?style=for-the-badge&logo=pnpm&logoColor=white
[pnpm-link]: https://pnpm.io

<!-- React -->
[react-badge]: https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB
[react-link]: https://react.dev

<!-- React Router -->
[reactrouter-badge]: https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white
[reactrouter-link]: https://reactrouter.com/en/main

<!-- Redux -->
[redux-badge]: https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white
[redux-link]: https://redux.js.org

<!-- SASS -->
[sass-badge]: https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white
[sass-link]: https://sass-lang.com

<!-- Tailwind CSS -->
[tailwind-badge]: https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white
[tailwind-link]: https://tailwindcss.com

<!-- Vite -->
[vite-badge]: https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E
[vite-link]: https://vitejs.dev

<!-- Vue JS -->
[vue-badge]: https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D
[vue-link]: https://vuejs.org

<!-- Yarn -->
[yarn-badge]: https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white
[yarn-link]: https://yarnpkg.com

<!-- Netlify -->
[netlify-badge]: https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7
[netlify-link]: https://www.netlify.com

<!-- Vercel -->
[vercel-badge]: https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white
[vercel-link]: https://vercel.com/dashboard

<!-- Eclipse -->
[eclipse-badge]: https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=whit
[eclipse-link]: https://eclipseide.org

<!-- VS Code --> 
[vscode-badge]: https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white
[vscode-link]: https://code.visualstudio.com

<!-- Eslint -->
[eslint-badge]: https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white
[eslint-link]: https://eslint.org

<!-- Prettier -->
[prettier-badge]: https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E
[prettier-link]: https://prettier.io

<!-- C -->
[c-badge]: https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white
[c-link]: https://www.w3schools.com/c/c_intro.php

<!-- CSS3 -->
[css-badge]: https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white
[css-link]: https://www.w3schools.com/css/css_intro.asp

<!-- HTML5 -->
[html-badge]: https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white
[html-link]: https://www.w3schools.com/html/

<!-- Java --> 
[java-badge]: https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white
[java-link]: https://www.java.com/en/

<!-- Javascript -->
[javascript-badge]: https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E
[javascript-link]: https://www.javascript.com

<!-- LaTeX -->
[latex-badge]: https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white
[latex-link]: https://www.latex-project.org

<!-- Markdown -->
[markdown-badge]: https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white
[markdown-link]: https://learnmarkdown.com

<!-- Shell Script-->
[shell-badge]: https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white
[shell-link]: https://www.shellscript.sh

<!-- Solidity -->
[solidity-badge]: https://img.shields.io/badge/Solidity-black?style=for-the-badge&logo=solidity&logoColor=e6e6e6
[solidity-link]: https://soliditylang.org

<!-- Typescript -->
[typescript-badge]: https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white
[typescript-link]: https://www.typescriptlang.org

<!-- Git -->
[git-badge]: https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white
[git-link]: https://git-scm.com

<!-- Github -->
[github-badge]: https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white
[github-link]: https://github.com