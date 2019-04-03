<a name="top"></a>
# Markdown Syntax for github documentation
A Collection of Markdown syntax and HTML syntax with examples for writing documentation here on github.

This guide/tutorial/cheatsheet is created in Markdown and HTML.

## Table of content

* [Images](/Image/README.md#top)
* [Links](/Link.md#top)
* [Texts](/Text.md#top)
* [Bullet Lists](/BulletList.md#top)
* [Number Lists](/NumberList.md#top)

## collapsible Section !test!
<details><summary>
  
### Collapsible field</summary>
HTML syntax
```
<details><summary>Collapsible field</summary>

Text inside goes here

</details>

```
###### Example
<details><summary>Collapsible field</summary>

Text inside goes here

</details>
</details>


---
<details><summary>
  
### Text box</summary>
Using tables to create boxed text
Markdown syntax
```
| Boxed text |
|:-:|

||
|:-:|
| Boxed text |
||
```
###### Example
| Boxed text |
|:-:|

||
|:-:|
| Boxed text |
||

</details>

---
<details><summary>
  
### Quotes</summary>
Markdown syntax
```
> quote
>> more quote
```
###### Example
> quote
>> more quote
</details>

---
<details><summary>
  
### Typography</summary>
Markdown syntax  
```**This text is _extremely_ important**```  
###### Example  
**This text is _extremely_ important**  
Markdown syntax  
```_This text is **extremely** important_```  
###### Example  
_This text is **extremely** important_  
Markdown syntax  
```
~~Strike this text~~
```
###### Example
~~Strike this text~~

</details>

---
<details><summary>
  
### Abbreviation</summary>
Markdown syntax  
```
[Abbr](\# "Abbreviation")  
[HTML](\# "Hypertext Markup Language")  
```
###### Example
[Abbr](\# "Abbreviation")  
[HTML](\# "Hypertext Markup Language")  

</details>

---
<details><summary>
  
### Code blocks with syntax identifyer</summary>
```csharp
public void Method(string argh[])
{
  ComeOn();
  bool temp = true;
  string text = "";
  if(temp){
    return text = "Hello";
  }
  
}
```
</details>
