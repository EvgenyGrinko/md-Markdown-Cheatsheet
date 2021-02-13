CTRL + SHIFT + V - to watch markdown preview in the VS Code
<br/>
# Markdown rules:

- Bold text: wrap the text with double asterisk (`**`) or underscore (`__`) to make it **bold** `**example text**` or `__another example__`

- Italic text: wrap it with singular asterisk (`*`) or underscore (`_`) to make it *italic* `*example text*` or `_another example_`

- Link: wrap it with square brackets ([]) with preceeding parenthesis which wrap some link (https://lala.la) to make it looks like link: [example link](https://example.lenk).<br/>Example: `[link text](https://actual link)`

- Headers: can be created with hash (`#`). <br/>Example:(`# This is an <h1> tag`)
# This is an `<h1>` tag
## This is an `<h2>` tag
###### This is an `<h6>` tag

- Lists: 
    * Unordered - with singular asterick (`* list item`)
    1. Ordered - with numbers (`1. ordered item`)

- Blockquotes: with singular angular bracket (`>`): 
    > Example blockqoute. <br/>Another one
    
- Not for Github: Colors: could be added with ```style``` attribute:<br/>Example: `<span style="color:rgb(0, 180, 100);">html-webpack-plugin</span>`<br/>
Result: <span style="color:rgb(0, 180, 100);">html-webpack-plugin</span></br>
- Highlight text by wrapping it with backticks (\`\`)<br/>Example: `any text`<br/>
- Code snippets: Format: \`\`\`language code \`\`\`<br/>
Example:<br/> \`\`\`js <br/>const date = new Date('2021-02-13T09:22:37.713Z');<br/> console.log(date.getFullYear());<br/>\`\`\`<br/>
Result: </br>
```js
const date = new Date('2021-02-13T09:22:37.713Z');
console.log(date.getFullYear());
```
>Note: always add a line break before and after lines of code</br>
- Colors highlight: - use the __diff__ language tag to generate some colored text:

Example:<br/>
\`\`\`diff<br/>
\- text in red<br/>
\+ text in green<br/>
\! text in orange<br/>
\# text in gray<br/>
\@@ text in purple (and bold)@@<br/>
\`\`\`<br/>
Result: 

```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
> Note: it adds it as a new line starting with either - + ! # or starts and ends with @@<br/>
- Images: Format: `![Alt Text](url)`. <br/>Example: `![GitHub Logo](/images/logo.png)`
![Random Logo](/images/test-logo.png)


