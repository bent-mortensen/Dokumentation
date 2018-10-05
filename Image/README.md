<a name="top"></a>
# Image markdown
[Back](https://github.com/bent-mortensen/Dokumentation#top "Back to main page.")

## Table of content 
1. [Full image link](#fullimagelink)
2. [Short image link 1](#shortimagelink1)
3. [Short image link 2](#shortimagelink2) <-- This can create a reference to an image, to use again and again. 
4. [HTML image link](#htmlimagelink) <-- This can control the size of the image, width and height.

<a name="fullimagelink"></a>
## Full image link

Markdown syntax
```
![Alt Text](https://github.com/bent-mortensen/Dokumentation/blob/master/Image/User-Story-Card.png "MouseOver Hover Title Text")
```
Example  

![Alt Text](https://github.com/bent-mortensen/Dokumentation/blob/master/Image/User-Story-Card.png "MouseOver Hover Title Text")

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

This will create an Reference, than can be placed without having the image link attached every time.

Place the reference in the bottom of the markdown document to use it every where.

Markdown syntax
```
![alt text][logo]

[logo]: https://github.com/bent-mortensen/Dokumentation/blob/master/Image/User-Story-Card.png "MouseOver Hover Title Text"
```
<details><summary>Example</summary>
  
![alt text][logo]

</details>

[logo]: https://github.com/bent-mortensen/Dokumentation/blob/master/Image/User-Story-Card.png "MouseOver Hover Title Text"

[To the Top](#top)
------------------

<a name="htmlimagelink"></a>
## HTML image link

Markdown syntax
```
<img src="https://github.com/bent-mortensen/Dokumentation/blob/master/Image/User-Story-Card.png" width="300" height="100"></img>
```
Example  

<img src="https://github.com/bent-mortensen/Dokumentation/blob/master/Image/User-Story-Card.png" width="300" height="100"></img>

[To the Top](#top)
------------------
