<a name="top"></a>
# Image markdown
## Table of content 
1. [Full image link](#fullimagelink)
2. [Short image link 1](#shortimagelink1)
3. [Short image link 2](#shortimagelink2) <-- This can create a reference to an image, to again and again. 
4. [HTML image link](#htmlimagelink) <-- This can control the size of the image, width and height.

<a name="fullimagelink"></a>
## Full image link

Markdown syntax
```
![Alt Text](https://avatars2.githubusercontent.com/u/32063274?s=96&v=4 "MouseOver Hover Title Text")
```
Example  
![Alt Text](https://avatars2.githubusercontent.com/u/32063274?s=96&v=4 "MouseOver Hover Title Text")

[To the Top](#top)
------------------

<a name="shortimagelink1"></a>
## Short image link 1

Markdown syntax
```
![Alt Text](/Image/User-Story-Card.png)
```
Example  
![Alt Text](/Image/User-Story-Card.png)  
[To the Top](#top)
---

<a name="shortimagelink2"></a>
## Short image link 2

This will create an Reference, than can be placed without have the image link attached every time.

Place the reference in the bottom of the markdown document to use it every where.

Markdown syntax
```
![alt text][logo]

[logo]: https://avatars2.githubusercontent.com/u/32063274?s=96&v=4 "MouseOver Hover Title Text"
```
Example  
![alt text][logo]

[logo]: https://avatars2.githubusercontent.com/u/32063274?s=96&v=4 "MouseOver Hover Title Text"


[To the Top](#top)
------------------

<a name="htmlimagelink"></a>
## HTML image link

Markdown syntax
```
<img src="https://avatars2.githubusercontent.com/u/32063274?s=96&v=4" width="300" height="100"></img>
```
Example  
<img src="https://avatars2.githubusercontent.com/u/32063274?s=96&v=4" width="300" height="100"></img>

[To the Top](#top)
------------------
