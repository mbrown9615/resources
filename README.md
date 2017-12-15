# resources 
In case they're helpful.

## *Topics*  
* [Code Editors/IDEs](#code-editors)
* [Code Environments](#code-environments)
* [CSS](#css)
* [Design](#design)
* [Git](#git)
* [HTML](#html)
* [JavaScript](#javascript)
* [Pay to learn](#pay-to-learn)
* [Markdown](#markdown)  
* [Node](#node)
* [Practice Problems](#practice-problems)  
* [React](#react)  
* [SVG](#svg)
* [Terminal](#terminal)

### Code Editors
#### [VS Code](https://code.visualstudio.com/)
* [JavaScript in VS Code](https://code.visualstudio.com/docs/languages/javascript#_automatic-type-acquisition)
* [Chrome Debugger for VS Code](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)

##### Display Preview of Markdown
To switch between views, press ⇧⌘V in the editor. You can view the preview side-by-side (⌘KV). ([Source](https://code.visualstudio.com/docs/languages/markdown#_markdown-preview))

##### Open New Terminal With Keyboard
`Ctrl` + `Shift` + `~`

### Code Environments
https://repl.it (Online REPL, compiler, and IDE)

### CSS
#### Flexbox
http://geddski.teachable.com/p/flexbox-zombies  
http://flexbox.help/

#### Fonts
https://fonts.google.com/

### Design
#### Gettting inspiration/ideas
https://www.awwwards.com/

### HTML
#### Color code helps
https://html-color-codes.info/
https://html-color-codes.info/colors-from-image/ - Upload an image and get a color code by clicking on any part of it.

### Git
#### Commands
##### Change URL of remote 
<pre>git remote set url <em>https://url-of-repo</em></pre>

### JavaScript
#### 'this' in JavaScript
http://yehudakatz.com/2011/08/11/understanding-javascript-function-invocation-and-this/

### Pay to learn
Resources that cost money (but may sometimes make content available for free). Sometimes paid courses are significantly higher quality than what's available for free. (Sometimes not.)

https://egghead.io/


### Markdown  
https://www.markdowntutorial.com/   
http://en.wikipedia.org/wiki/Markdown#Example  
http://spec.commonmark.org/dingus/  
http://johnmacfarlane.net/babelmark2/faq.html  
http://idratherbewriting.com/2013/06/04/exploring-markdown-in-collaborative-authoring-to-publishing-workflows/  
https://www.markdownguide.org  

### Node
[Anatomy of an HTTP Transaction](https://nodejs.org/en/docs/guides/anatomy-of-an-http-transaction/#anatomy-of-an-http-transaction)

### Practice Problems
[Codewars](https://codewars.com/) - "Achieve code mastery through challenge"  
[CodeFights](https://codefights.com/) - Interview Practice, Challenges, Arcade, Head-to-Head, Company Bots, Tournaments

### React
#### Development Environment
##### Find what process is running the dev server at a specific port:
If the dev server is running on port 3000:
```
lsof -i :3000
```
This will produce some information like this: 
```
COMMAND    PID         USER   FD   TYPE  SIZE/OFF NODE NAME
Google    7257 jamescarlson   93u  IPv4       0t0  TCP localhost:55054->localhost:hbci (ESTABLISHED)
node      9614 jamescarlson   14u  IPv4       0t0  TCP *:hbci (LISTEN)
node      9614 jamescarlson   31u  IPv4       0t0  TCP localhost:hbci->localhost:55054 (ESTABLISHED)
```
Find the process ID in the PID column for COMMAND of "node". To kill that process, type `kill -9` and then the PID (in the example above, `9614`). 

<pre>
kill -9 <i>PID</i>
</pre>

### SVG Images
http://svgpocketguide.com/book/

### Terminal 
http://osxdaily.com/2013/02/05/improve-terminal-appearance-mac-os-x/
