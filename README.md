# Learning Markdown

This is Normal Text

This is one way to write *Italic* text

This is another way to write _Italic_ text

This is a **Bold** text

This is another __Bold__ text

I dont want this to be really \*\*bold\*\* but rather have the asterix symbols around the letter bold

Single # followed by a space and text makes the text  
# HEADING 1

6 ###### followed by s space and text makes the text
###### HEADING 6

This is how you embed an image from your repo
![Link an image.](/thisisa/folder/inmy/repository/sam.png)

This is how you link aother file from your repo

[This is a file on my repo](/textfiles/README.md)

This is how you create Lists

Numbered lists have the prefix with a number, followed by a '.' and a space and then the text(ex: 1. Text 2. Another text) The number needn't be sequential. 
GML will autoatically take care of numbering them sequentially when you save it.

1. one
1. two
2. three
   
For unordered list prefix with a * or -
* First
  * Nested
* Second
* Third


- One
- Two
  - three
 
    
Tables

Column1|Column2
-|-
Row1-Col1|Row1-Col2
Row2-Col2|Row2-Col2

Syntax Highlighting using language prefix

```python
list = []
dict = {"name": "sam", "number": 123}
```

```javascript
var first = 1;
var second = 2;
var sum = first + second;
```

References to Pull Requests 

https://github.com/sam-nash/test/pull/4


desktop/desktop#3602


References to commits

8304e9c271a5e5ab4fda797304cd7bcca7158c87

Blockquotes are created using the greater than (>) character.
> This is a quote

This is how you <br /> break a line
