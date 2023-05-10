<img src="./top.svg">

# Markdown Basics for the uninitiated 
### What is it?
Markdown is a lightweight markup language that allows users to create richly formatted text using a simple syntax. 
<br>

### Why should I use Markdown?
Markdown can be used in a variety of contexts, including writing documentation, creating blog posts, formatting messages on social media platforms, and even creating slide presentations. 
<br>
Many popular platforms and tools, such as GitHub, Reddit, and Slack, support Markdown natively, making it a versatile and widely used language for creating and sharing formatted text online.

***

# All about README.md file markup
<h2><b>Important information that the user should read before continuing</b></h2>

### What is a readme file?
A README is a file that contains important information about a software project, usually placed in the root directory of the project. It typically includes details about what the project does, how to install and run it, its dependencies, and how to contribute to it.
<br><br>
Overall, a well-written README is an essential component of any software project, and can play a critical role in helping users and contributors understand, use, and contribute to the project.

***

# Table of contents
1. [Horizontal line](#horizontal-line)
2. [Title/Headings](#titleheadings)
3. [Text](#text)
   * 3.1. plain text
   * 3.2. One line Code block
   * 3.3. Multiline Code block
   * 3.4. Text Highlighting
   * 3.5. Line wrapping
   * 3.6. Italics
   * 3.7. Bold
   * 3.8. Bold and italic
   * 3.9. Strikethrough
4. [Insert tables](#Insert-tables)
5. [Lists](#Lists)
    * 5.1. Marked
    * 5.2. Numbered
6. [Hidden menu](#Hidden-menu)
7. [Links](#Links)
    * 7.1. Text hyperlink
    * 7.2. Image link
8. [Useful links](#Useful-links)
    * 8.1. Shields
    * 8.2. Emoji

## Horizontal line

A horizontal line (separating line) can be obtained in three ways:

- *** using three consecutive asterisks
- --- using three consecutive hyphens
- ___ using three consecutive underscores

they all display the same horizontal line  effect
***

[Back to Table of Contents](#table-of-contents)

## Title/Headings

```
there are 6 levels of title
# First level title
## second level title
### third level title
#### fourth level title
##### fifth level title
###### sixth level title
```
# 1st level title
## 2nd level title
### 3rd level title
#### 4th level title
##### 5th level title 
###### 6th level title

***
Another method of making headings is by adding either a = or - to make a first or second level heading

heading 1
=

heading 2
-

[Back to Table of Contents](#table-of-contents)

***
# Text

- PLain text<br><br>
It looks like this, usual text is displayed.

- One Line code block<br>
`it looks like this `
Wrap the text with a pair of ` like this:
```
`hello world`
``` 


- Multi line code block<br>
```
Start with three `
and then end with three `
```
- Text Highlighting<br><br>
Often we feel the need to place code fragments, it is desirable not only to keep indents, but also highlight with color, for this you need to specify the programming language after the first three quotes

```python
#Simple binary search algorithm i made a while ago
import random 
import statistics
import time
start = 1
end = 50

number=random.randint(start, end)
print("The correct number is ",number)
guess=0
time.sleep(2)
while(guess!=number):
    mean=list(int(i) for i in range(int(start),int(end+1)))
    guess=int(statistics.mean(mean))
    
    print(guess)
    if guess<number:
        start=guess+1
    elif guess>number:
        end=guess-1
     
print("Found and verified the number {0} with the guess {1}".format(number,guess))
```

- Line Wrapping 


Perhaps this is not usual and not familiar, but when you press the "Enter" button, your text will still be displayed in one line, and in order for your transfer to work, you need to add two spaces at the end of the line

Or just add an empty string, i.e. press "Enter" 2 times. In this case, the transfer effect will be achieved, but line spacing will be larger.

- Italics

place text in between * or _ *like this* <br>
`*hello* or  _world_`

- Bold

Place text in between double * or _ __like this__
`__hello__ or **world**`

- Bold and Italics

place text in between triple * or _ ___like this___

`___hello__ or ***world***`

- Strikethrough
place text in between double '~' to ~~strikethrough~~
like this `~~sample text~~`

[Back to Table of Contents](#table-of-contents)

***
## Insert tables

We can create a simple table like this
```
|S.no|Name|Description|
|----|----|------|
|1| Greeenboi| coolguy|
|2| you| Very cool person|
```
|S.no|Name|Description|
|----|----|------|
|1| Greeenboi| coolguy|
|2| you| Very cool person|

[Back to Table of Contents](#table-of-contents)
***

## Lists

There are two tyes of lists; Ordered and unordered