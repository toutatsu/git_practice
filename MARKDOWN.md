# Markdown

## Inference

>[Markdown: Syntax](https://daringfireball.net/projects/markdown/syntax)

>[GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

>[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

>[Markdown記法 チートシート](https://qiita.com/Qiita/items/c686397e4a0f4f11683d)

>[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

---

## Horizontal Rules
```markdown
- - -
***
*   *   *   *   *
___
_ _ _ _ _ _

```
- - -
***
*   *   *   *   *
___
_ _ _ _ _ _



## Source Code Block

````
```(language)
some code
```
````


```c
#include<stdio.h>
int main(void){
    print("Hello World!");
}
```

```python
import sys
print("Hello World!")
```

---

## Bold
```markdown
**bold**
```
**bold**

---

## Italic
```markdown
*italic*
```
*italic*

---

## Citation
```markdown
> citation
>>citation2
>>>citation3
>>>>>>>>>>>>>>>>>citation∞
```
> citation
>>citation2
>>>citation3
>>>>>>>>>>>>>>>>>citation∞

---

## Hyperlink
```markdown
[hyperlink](https://github.com/)
```

[hyperlink](https://github.com/)

---

## Image
```markdown
![github](https://avatars.githubusercontent.com/u/9919?s=280&v=4)
```
![github](https://avatars.githubusercontent.com/u/9919?s=280&v=4)

---

## List
```markdown
* list1
    + list1-1
- list2
```
* list1
    + list1-1
- list2

---

## OrderedList
```markdown
1. orderlist1
    2. orderlist1-1  
2. orderlist2 
```
1. orderlist1
    2. orderlist1-2  
2. orderlist2 

---

## Header
```markdown
# Header1
## Header2
### Header3
#### Header4
##### Header5
###### Header6
```
# Header1
## Header2
### Header3
#### Header4
##### Header5
###### Header6

---

## Strike
```
~~Strike~~
```
~~Strike~~

---

## Details
<details><summary>sample code</summary><div>

```rb
puts 'Hello, World'
```
    
</div></details>

---

## CheckBox
```
- [ ] Checkbox
- [x] Checked
```

- [ ] Checkbox
- [x] Checked

---

| Left align | Right align | Center align |
|:-----------|------------:|:------------:|
| This       | This        | This         |
| column     | column      | column       |
| will       | will        | will         |
| be         | be          | be           |
| left       | right       | center       |
| aligned    | aligned     | aligned      |

---

## Escape
```
\#Escape
```
\#Escape

---

##HTML
```html
<dl>
  <dt>Name</dt>
  <dd>Definition</dd>
</dl> 
```
<dl>
  <dt>Name</dt>
  <dd>Definition</dd>
</dl> 

---

## $$\LaTeX$$

$$
e^{i\pi}+1=0\\

\alpha\\

\underline{underline}\\
\underline{\underline{doubleunderline}}\\

$$


| \tiny | \scriptsize | \footnotesize | \normalsize | \large | \LARGE | \huge | \HUGE |
|:-----:|:-----------:|:-------------:|:-----------:|:------:|:------:|:-----:|:-----:|
|$$\tiny ABC$$|$$\scriptsize ABC$$|$$\footnotesize ABC$$|$$\normalsize ABC$$|$$\large ABC$$|$$\LARGE ABC$$|$$\huge ABC$$|$$\Huge ABC$$|


---
