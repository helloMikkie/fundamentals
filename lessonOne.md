# lesson One
```html
<section class="slide_1">
</section>
<section class="slide_2"></section>
</section>
<section class="slide_3"></section>
</section>
<section class="slide_4"></section>
</section>
<section class="slide_5"></section>
</section>
```
```css
body {
  font-family: Montserrat;
  font-size: 16px;
  color:  #097496;
}
header{
  position:  fixed;
  top: 20px;
  left:  20px;
}
h1{
  font-size:  32px;
  font-weight:  600;
  margin:10px 0;
  letter-spacing:  -0.02em;
}
a {
  text-decoration:  none;
  margin-right:  5px;
  color:  #097496;
}
a:hover{
  color:  #666666;
}
section {
  width:  100%;
  height:  100vh;
  background-attachment:  fixed;
  background-size:  cover;
  background-position:  center;
}

.info {
  width: 40px;
  position:  fixed;
  bottom:  30px;
  left: calc(50% - 20px);
}

.slide_1 {
  background-image:  url(the-pen.svg);
    background-color:  #ffffff;

}
.slide_2 {
  background-image:  url(is-mightier.svg);
   background-color:  #000000;
}
.slide_3 {
  background-image:  url(than.svg);
  background-color:  #ffffff;
}
.slide_4 {
  background-image:  url(the-sword.svg);
   background-color:  #000000;
}
.slide_5 {
  background-image:  url(end.svg);
   background-color:  #097496;;
}

@media (max-width: 600px) {
  section {
    background-attachment: scroll;
    height: 60vw;
  }
}

```
