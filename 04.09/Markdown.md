## Markdown

**Markdown** is a lightweight markup language with plain text formatting syntax, which converts text into an html-page. It was created in 2004 by John Gruber in collaboration with Aaron Schwartz, to enable people "to write using an easy-to-read and easy-to-write plain text format, optionally convert it to structurally valid XHTML (or HTML)".

Markdown-files have .md or .markdown extensions.

#### 1. Formatting in Markdown

Headings in Markdown are marked with \#:

\#                
\#\#             
...  
\#\#\#\#\#\#    

Cursive: \* or \_ \(without spaces\) at the beginning and the end of the fragment:

```
*stars* or _stars_
```

_stars_ or _stars_

To make the text bold: \*\* or \_\_ \(no spaces\):

```
**две звезды** or __два нижних подчеркивания__
```

**две звезды** or **два нижних подчеркивания**

To cross out text: ~~ \(no spaces\):

```
~~две тильды~~
```

~~две тильды~~

###### Lists:

```
1. первый элемент
2. второй элемент
3. третий элемент
4. четвертый элемент
1. пятый элемент
```

1. первый элемент
2. второй элемент
3. третий элемент
4. четвертый элемент
5. пятый элемент

Non-enumerations:

```
+ первый элемент
- второй элемент
+ третий элемент
  - четвертый элемент
  * пятый элемент
```

* первый элемент
* второй элемент
* третий элемент
  * четвертый элемент
  * пятый элемент

#### 2. Objects

###### Links

```
<https://www.markdownguide.org>  
https://www.markdownguide.org  

<eee@mail.ru>  
eee@mail.ru
```

[https://www.markdownguide.org](https://www.markdownguide.org)  
[https://www.markdownguide.org](https://www.markdownguide.org)

[eee@mail.ru](mailto:eee@mail.ru)  
eee@mail.ru

Hyperlinks:

```
[text](https://www.markdownguide.org)
```

[text](https://www.markdownguide.org)

To add a comment:

```
[text](https://www.markdownguide.org "this will help")
```

[text](https://www.markdownguide.org "this will help")

###### Pictures

To insert a picture:

!\[\]\(a link to the picture\)

For example:

```
![](http://3.bp.blogspot.com/-_DLc3qDxsNA/VenIznBsK7I/AAAAAAAAB0A/GHjI_97B364/s1600/TheFunk.jpg)
```

![](http://3.bp.blogspot.com/-_DLc3qDxsNA/VenIznBsK7I/AAAAAAAAB0A/GHjI_97B364/s1600/TheFunk.jpg)

###### Tables

```
1|2|3
---|:---:|---:
да|нет|не знаю
не знаю|нет|да
нет|не знаю|да
нет|да|не знаю
да|не знаю|нет
не знаю|да|нет
```

| 1 | 2 | 3 |
| :--- | :---: | ---: |
| да | нет | не знаю |
| не знаю | нет | да |
| нет | не знаю | да |
| нет | да | не знаю |
| да | не знаю | нет |
| не знаю | да | нет |

#### 3. Where can I use Markdown?

* Jupyter Notebook
* GitHub
* Telegram
* Tumblr
* R, Python ...

#### 4. Some references

[The fullest notation](https://www.markdownguide.org)  
[Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet) \(сжатый конспект\)  
[Help on github](https://help.github.com/categories/writing-on-github/) 
