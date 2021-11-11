# Markdown

## Inference

>[Markdown: Syntax](https://daringfireball.net/projects/markdown/syntax)

>[GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

>[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

>[Markdown記法 チートシート](https://qiita.com/Qiita/items/c686397e4a0f4f11683d)

>[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

---

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
```

> citation

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
* list
```
* list

---

## OrderedList
```markdown
1. orderlist
```
1. orderlist

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

 - [ ] task1
 - [x] task2

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