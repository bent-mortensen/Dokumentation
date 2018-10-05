<a name="top"></a>
# Markdown Syntax for github documentation
A Collection of Markdown syntax and examples for writing documentation here on github.

This guide/tutorial/cheatsheet is created in markdown.

## Table of content

* [Images](/Image/README.md#top)
* [Links](/Link.md#top)
* [Texts](/Text.md#top)
* [Bullet Lists](/BulletList.md#top)
* [Number Lists](/NumberList.md#top)

## for work
* [user story 1](https://github.com/bent-mortensen/Dokumentation/blob/master/UserStories/user-story-1.md)
* user...

[INSIDE](\#inside "Inside")  

## collapsible markdown?
<details><summary>SHOW/HIDE</summary>
  
  text
    text

</details>

<details><summary>SHOW/HIDE</summary>
<a name="inside"></a>  
#### yes, even hidden code blocks!

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
> quete
>> more

syntax  
```**This text is _extremely_ important**```  
example  
**This text is _extremely_ important**  
syntax  
```_This text is **extremely** important_```  
example  
_This text is **extremely** important_  


</details>

## Text alignment
Markdown is always left-aligned 

## tables
| Boxed text |
|:-:|

||
|:-:|
| Boxed text |
||



## Abbreviation
[Abbr](\# "Abbreviation")  
[HTML](\# "Hypertext Markup Language")  
