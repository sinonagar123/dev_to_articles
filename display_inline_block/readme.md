## 
Difference between **CSS display _inline, block & inline-block_**

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/92dmf8jajlu0om78nzlg.jpeg)

The display property defines how an HTML element should be displayed on the webpage. There are several values for the display property, including _block, inline, and inline-block._These values determine the layout behavior of the element they are applied to.

` display:block; `
` display:inline;`
`display:inline-block;`

Here's an example of how these display values might be used in HTML and CSS:

![](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/mwswt0x7cntb7lhe3lz2.png)

## **`display:block;`**

The element will start on a new line and occupy the full width available. Block elements will occupy the entire width of its parent element. And you can set width and height values.This means that block elements stack vertically, one below the other. Common block elements include 

- div
- h1 to h6
- p
- li
- section


```javascript
.block-element {
  display: block;
}
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/xqp54f1qwp3kvcl7af3k.jpeg)

## **`display:inline;`**

The element doesn't start on a new line and only occupy just the width it requires. You can't set the width or heightThey flow within the content, allowing other inline elements to be placed beside them. Common inline elements include 

- span 
- a
- strong
- em

```javascript
.block-element {
  display: inline;
}

```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/pm2cptgs6sm1ewll23sz.jpeg)

## **`display:inline-block;`**

It's formatted just like the inline element, where it doesn't start on a new line. BUT, you can set width and height values. It combine aspects of both block and inline elements. They maintain their inline characteristics, allowing other elements to be placed beside them, while also allowing you to set their width, height, margins, and padding. This is often used for creating layout components that need to be positioned horizontally but require control over their dimensions.
```javascript
.block-element {
  display: inline-block;
}

```
