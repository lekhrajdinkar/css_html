### Images and Background

#### 1. background property.
- shorthand : background: url("freedom.jpg"); 
- Actual : background-image:  url("freedom.jpg"); 

**by PX**

1. `background-size: 200px;` 
- it will repeat image, `width` - 200px , `length` - as per aspect ratio.
- background-repeat: no-repeat/repeat-x/repeat-y
```
#product-overview {    
    background-image:  url("freedom.jpg");  background-size: 200px; 
    width:100%; height: 520px;
    background-repeat: no-repeat/repeat-x/repeat-y
}
```
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/img/1.JPG)

**by %**

2. `background-size: 300px 200px;` --> define both length and width --> this will distort img
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/img/2.JPG)

3 `background-size: 50%` --> width as 50% of container/parent.
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/img/3.JPG)

4. `background-size: 50% 50%` --> both. this will distort img.

5. `background-size: 50% 100%`  --> Keep length 100% to fix it.

6. `background-size: auto 50%`  --> define length as 50% , width : as per aspect ratio

7. `background-size: 100%` --> width as 100% of container/parent amd height will be as per ratio, but it will cropped from bottom to main aspect ratio.

7.1. `background-size: 100% 100%` --> width and lenght as 100% of container/parent --> ii wont crop and fit image (distort)
![img](https://github.com/lekhrajdinkar/css_html/blob/master/NOTES-CSS/assets/img/4.JPG)

***



