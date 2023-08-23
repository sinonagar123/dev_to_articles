# How to Center a Div for Perfect Layouts 

Centering a div might seem like a puzzle, but it's an essential technique for creating beautifully balanced web designs. Follow these 3 ways you can center a div:

- Using horizontal centering
- Using vertical centering
- Using horizontal & vertical centering

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/kx486mbaq3iq5j483g8v.jpeg)


## Horizontal centering

Horizontal centering of a div element in CSS can be achieved using various methods. Here are a few commonly used techniques:


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/2br090ic1fmuof548vr2.jpeg)

1.**Using Auto Margins**:

In this method, setting both the left and right margins to "auto" will automatically center the div horizontally within its parent container. The width property can be adjusted as required.

HTML
```javascript
<div class="center">
  codewithvayola
</div>
```
CSS

```javascript
.center {
  margin-left: auto;
  margin-right: auto;
  width: 50%; /* Adjust the width as needed */
  background-color:yellow;
}
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/67019t0hawnz3r9ovhhw.jpeg)

2.**Using Flexbox**:

With Flexbox, setting `display: flex `on the parent container and justify-content: center will center the child div horizontally within the parent.

HTML
```javascript
<div class="center">
  codewithvayola
</div>
```
CSS

```javascript
.center {
  display: flex;
  justify-content: center;
  background-color:yellow;
}
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/pm2e6nioqfzkovu3y81t.jpeg)

3.**Using Grid**:

Using CSS Grid, applying `display: grid` to the parent container and place-items: center will center the child div horizontally.

HTML

```javascript
<div class="center">
  codewithvayola
</div>
```
CSS

```javascript
.center {
  display: grid;
  place-items: center;
  background-color:yellow;
}
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/qq6wrqyp2jkzqer8rkkx.jpeg)

4.**Using Text-Align**:

For inline or inline-block elements within a div, you can center them horizontally using text-align: center applied to the parent div.

HTML

```javascript
<div class="center">
   <p>codewithvayola</p>
</div>
```
CSS

```javascript
.center {
  text-align: center;
  background-color:yellow;
}
```


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/tyd1r5206gj6gph22lkr.jpeg)

## Vertical centering

Vertical centering of a div element in CSS can be achieved using various methods. However, vertical centering can sometimes be a bit trickier than horizontal centering due to the behavior of block-level elements. Here are a few commonly used techniques:


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/yszn24vtl7rstf2nb3or.jpeg)

1.**Using Flexbox**:

With Flexbox, setting display: flex on the parent container and using justify-content: center and align-items: center will center the child div both horizontally and vertically within the parent. The height of the parent can be adjusted as required.

HTML
```javascript
<div class="center">
  <div class="content">
    codewithvayola
  </div>
</div>
```
CSS

```javascript
.center {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh; /* Adjust the height as needed */
  background-color:yellow;
}

.content {
  /* Add styles to your content here */
  background-color:red;
}
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/okqe3q7ind2rfedyybqk.jpeg)

2.**Using Grid**:

Using CSS Grid, applying display: grid to the parent container and using place-items: center will center the child div both horizontally and vertically within the parent. The height of the parent can be adjusted as required.

HTML
```javascript
<div class="center">
  <div class="content">
    codewithvayola
  </div>
</div>
```
CSS

```javascript
.center {
  display: grid;
  place-items: center;
  height: 100vh;  /* Adjust the height as needed */
  background-color:yellow;
}

.content {
  /* Add styles to your content here */
  background-color:red;
}
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lylj21nj11zdyt1vqett.jpeg)

3.**Using Absolute Positioning**:

Using absolute positioning, you can center the child div vertically by setting its top to 50% and using transform: translateY(-50%) to adjust its position.

HTML
```javascript
<div class="center">
  <div class="content">
    codewithvayola
  </div>
</div>
```
CSS

```javascript
.center {
  position: relative;
  height: 100vh; /* Adjust the height as needed */  
  background-color:yellow;
}

.content {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background-color:red;
  /* Add styles to your content here */
}
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/tiqzuues61t507vqyd4v.jpeg)

## Vertical & Horizontally centering

You can use a combination of Flexbox or CSS Grid to center a div both horizontally and vertically. Here's how you can achieve that:

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/gfb4a875fed8t8d2ztja.jpeg)

1.**Using Flexbox**:

With Flexbox, setting display: flex on the parent container and using justify-content: center and align-items: center will center the child div both horizontally and vertically within the parent. The height of the parent can be adjusted as required.

HTML
```javascript
<div class="center">
  <div class="content">
    codewithvayola
  </div>
</div>
```
CSS

```javascript
.center {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh; /* Adjust the height as needed */
  background-color:yellow;
}

.content {
  /* Add styles to your content here */
  background-color:red;
}
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/okqe3q7ind2rfedyybqk.jpeg)

2.**Using Grid**:

Using CSS Grid, applying display: grid to the parent container and using place-items: center will center the child div both horizontally and vertically within the parent. The height of the parent can be adjusted as required.

HTML
```javascript
<div class="center">
  <div class="content">
    codewithvayola
  </div>
</div>
```
CSS

```javascript
.center {
  display: grid;
  place-items: center;
  height: 100vh;  /* Adjust the height as needed */
  background-color:yellow;
}

.content {
  /* Add styles to your content here */
  background-color:red;
}
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lylj21nj11zdyt1vqett.jpeg)
