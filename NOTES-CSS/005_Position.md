## Position
- `position` property does lot more, other than `display` property does (inline, block, inline-block)
- can change actual position of elemnt.
- Z-index : position elemt along z-axis.
- default values : `static`
- Other values : `fixed`, `absolute`, `relative`, `sticky` -- > by adding these valies we take element from normal document flow.
- can be applied to any element, no matter if its inline or block.
- **position Context** : 
- **stacking context** :

***

### Feature
1. Document flow > normal html > one elememt after anothor.
- default value of `position` is `static`. 
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/position/1.JPG)

2. change default behaviour - use other value of `position` property.
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/position/2.JPG)

3. Change the position, but how ? 
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/position/3.JPG)

- `positioning context` : eg: top : 30 --> 30px from current pos of elememt(default), or from view port, or from html tag, or from body, or from it parent, etc ?
- z- index, top, left,etc would work only for non-static value.

***

### A. Fixed
1.  create stable nav bar:
- main-header { position:fixed, width:100%, box-sizing:border-boxing, margin : 10px }
- top:0, left:0, right: 0 --> base is viewport.
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/position/4.JPG)

2. Adding image in background behind the content.
- header tag > image tag
note : both are fixed position
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/position/5.JPG)
- opposite order : image > header
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/position/6.JPG)

- fixed will over static : keep image (fixed) first then  all three anchor (static) --> image will shown.




