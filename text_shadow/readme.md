## Enhancing Text with _CSS Text Shadow_ Effects

The CSS `text-shadow` property is used to apply a shadow effect to text. It adds a shadow behind the text, creating a visual effect that can enhance the text's readability or aesthetics. It's a great way to enhance the visual appeal of your text and make it stand out. The text-shadow property accepts a comma-separated list of values that define the offset, blur radius, and color of the shadow. Here's the basic syntax:

```javascript
selector {
  text-shadow: horizontal-offset vertical-offset blur-radius color;
}
```


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/mkchwg47vquen2oflr5e.jpeg)

**_horizontal-offset:_** This value determines the horizontal distance of the shadow from the text. Positive values move the shadow to the right, while negative values move it to the left.

_**vertical-offset:**_ This value determines the vertical distance of the shadow from the text. Positive values move the shadow downward, while negative values move it upward.

**_blur-radius:_** This value defines the amount of blurring applied to the shadow. A larger value results in a more spread out and softer shadow.

_**color:**_ This value specifies the color of the shadow. You can use color names, hexadecimal codes, RGB values, or any other valid color representation.

Here are some examples

```javascript

<p class="example1">Codewithvayola</p>
p {

font-size: 40px;
font-family: "Helvetica Neue", arial, sans-serif;
}
.example1 {

text-shadow: 2px;
}
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ozewyma1l45xe5lcbalh.jpeg)

Here I gave only one value `text-shadow: 2px;` which is typically used to define the **horizontal offset of the shadow.** 

```javascript

<p class="example1">Codewithvayola</p>
p {

font-size: 40px;
font-family: "Helvetica Neue", arial, sans-serif;
}
.example1 {

text-shadow: 2px 2px;
}
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/cdl2e9iulyqfxngd110m.jpeg)

Here I gave two values `text-shadow: 2px 2px;` 2px for the **horizontal offset** and 2px for the **vertical offset**.

```javascript

<p class="example1">Codewithvayola</p>
p {

font-size: 40px;
font-family: "Helvetica Neue", arial, sans-serif;
}
.example1 {

text-shadow: 2px 2px 5px;
}
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/zorw9e2ru63eelqthehw.jpeg)

Will create a text shadow effect for the selected element with the following characteristics:

**Horizontal offset**: 2 pixels to the right.
**Vertical offset**: 2 pixels down.
**Blur radius**: 5 pixels.
Shadow color: The default shadow color, which is typically black.
This means that the text will appear with a shadow that is offset 2 pixels to the right and 2 pixels down from the original text position. The shadow will be blurred with a radius of 5 pixels, creating a softer and more spread-out shadow effect. The shadow color will be the default, usually black.
```javascript

<p class="example1">Codewithvayola</p>
p {

font-size: 40px;
font-family: "Helvetica Neue", arial, sans-serif;
}
.example1 {

text-shadow: 2px 2px 5px yellow;
}
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rskxxddw147hurszdjqs.jpeg)

Will create a text shadow effect for the selected element with the following characteristics:

**Horizontal offset**: 2 pixels to the right.
**Vertical offset**: 2 pixels down.
**Blur radius**: 5 pixels.
**Shadow color**: Yellow.
This means that the text will appear with a shadow that is offset 2 pixels to the right and 2 pixels down from the original text position. The shadow will be blurred with a radius of 5 pixels, creating a softer and more spread-out shadow effect. The shadow color will be yellow.


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/7vjr61bnt6ifdef6jtcb.jpeg)

[Visit for source code](https://codepen.io/vayolapradeep/pen/abPONOR)
