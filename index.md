## Title: Markdown Communication  
---
### Overview:
Markdown represents a lightweight text formatting language to help with written communication published through a browser.  I have used it often in Jupyter notebook environments.  There are many different options to leverage within the Markdown language.  

[GitHub Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#tables)

---
### Adding and image
> GitHub Image provided with tutorial

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

> Another image example

![Digital Bull and Bear trading](https://g.foolcdn.com/image/?url=https%3A%2F%2Fg.foolcdn.com%2Feditorial%2Fimages%2F656679%2Fdigital-bull-vs-bear.jpg&w=700&op=resize)

---
### Add a code snippet
There are times when the readme or other text documents need to support communicate code details in conjunction with the written text information in the file.  Markdown has a nice feature to all this text to come across just as it would be typed for code execution.  This is done using three single quotes at the begining and end of the code section to designate that the text should not be converted to markdown.

> git initialization example for the command line in a working director to allow version control tracking
```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```

> Python recursive code example
```
def Factorial(num):
    if num < 2:
        return 1
    else:
        return Factorial(num-1)*num
```
