## Images and Background - part 2

### A. Add Logo

```
<a class="container">
    <img src="img.jpg" class="s1"> //200*200px img
</a>

.container{ h : 50px;  w : 50px ; display : inline-block}

.s1{ h : 100% ;  w : 100% } //100% of conatner which is 50px
```

1. container element for img is anchor (inline type) --> set container dimension to 50px 50px, but image is 200*200px, still full pixel image will shown

2. Make container `inline-block`, ythen it image size will reduce to 50px.

***

### B. Adding customer images

```
image container style:

  .testimonial__image-container {
    width: 65%;
    display: inline-block;
    vertical-align: middle;
    box-shadow: 3px 3px 5px 3px rgba(0,0,0,0.3);
  }

image style:

  .testimonial__image {
    width: 100%;
    vertical-align: top;
  }
```
1. Adjust image width:
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/img2/01.jpg) 

2. image (80% width ) + info (20% width) , with proper verticle alignment.
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/img2/02.jpg) 

3. Add shadow
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/img2/03.jpg) 

*** 

### LINEAR GRADIENT
`background-color: linear-gradient()` //css functions

- linear-gradient(red blue rgba()...) // can use multiple colors in any of 3 format.
- linear-gradient( 45deg red blue ...) //rotate ny amgle.
- linear-gradient( 180deg red transparent)
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/img2/04.jpg) 
- linear-gradient( 180deg red 70% blue 30% )
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/img2/05.jpg) 
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/img2/06.jpg) 

***

### RADIAL GRADIENT

***
