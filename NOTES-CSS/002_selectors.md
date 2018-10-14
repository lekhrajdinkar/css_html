# CSS Selector

## Types:
1. **universal** --> * {} = `all tags`.
- set to all element, overrides browser default, overrides inheritance.
2. **element** --> h1 {} = `h1 tag only`
3. **classes** --> .s1{} = `<h1 class=s1>, <p class=s1>, etc`
- reusable.
4. **id** --> #s2{} = `<h1 id=s2>`
- can be used only once as id is unique in html.
5. **Attributes** --> [disabled] {} = <button disabled>, any other disable element.
6. **Combinator** --> multiple selector.
- eg : `#id1 h1 {}`

![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/001.jpg)
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/002.jpg)
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/003.jpg)

***
## Grouping rule:
```
selector1,selector1 {
  //common declaration
}
```
***
## Specifity
1. scenario : 
```
<h1 class=s1> text </h1>

main.css:
   h1{ color : red } h1 { color : green}
// h1{ color : green} h1 { color : red } // change order
  .s1 { color : blue }

which color : ?
```
2. cascading mean multiple style can be applied on element which leads to conflict and resolve it provides **specifity**
3. preference/priority of selector
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/004.jpg)

4. Inheritance : parent has lowest priority.
- eg : body is parent of h1
```
body{ color : black}

<body><h1 style="color:green"> </h1></body> 
```
5. _more specific will win._
- eg : 
```
#id1 h1 {} //1 win
h1 {} //2
```

***
## COMBINATOR
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/005.jpg)
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/006.jpg)
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/007.jpg)
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/008.jpg)
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/009.jpg)
