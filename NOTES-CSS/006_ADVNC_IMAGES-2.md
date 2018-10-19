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



