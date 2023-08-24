## What is `<div>`,`<section>` & `<article>`

`<div>`, `<section>`, and `<article>` are HTML elements used for structuring and organizing content within a web page. Each of these elements serves a specific purpose in dividing content and improving the semantic structure of a webpage.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/gddpk1fnpiutu5h6m7xx.jpeg)

**1. `<div>` Element:**

The `<div> `element is a generic container used to group and style elements together for layout and styling purposes. It doesn't carry any inherent meaning on its own and is often used to create divisions or sections within a webpage that can be targeted with CSS for styling or JavaScript for interactivity.The syntax for using the `<div>` element in HTML is as follows:

html

```javascript
<div>
    <!-- Your content goes here -->
</div>
```
For example:

```javascript
<div class="container">
    <h1>Welcome to codewithevayola</h1>
    <p>Its me Vayola </p>
    <img src="https://res.cloudinary.com/dhfay42ie/image/upload/v1692137113/WhatsApp_Image_2023-08-15_at_6.04.19_PM_jlfydk.jpg" alt="An image">
</div>
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/hgmil92lzjq8mrjxo2rs.jpeg)

2. **`<section> `Element**:

The `<section> `element is used to define a thematic grouping of content, such as a chapter, a block of related content, or a self-contained portion of a webpage. It helps to improve the semantic structure of the page and makes it easier for search engines and assistive technologies to understand the content's context.The syntax for using the `<section>` element in HTML is as follows:

```javascript
<section>
    <!-- Your content goes here -->
</section>
```

For Example:

```javascript
<section>
    <h2>About Me</h2>
    <p>Passionate Full Stack Dev crafting seamless web solutions</p>
</section>

<section>
    <h2>Services</h2>
    <ul>
        <li>Web Design</li>
        <li>Web Development</li>
    </ul>
</section>
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/fh2s34hdhzha8pq76soa.jpeg)

3. **`<article>` Element**:

The `<article>` element represents a self-contained and independently distributable piece of content. It's typically used for blog posts, news articles, forum posts, or any content that can stand alone and make sense when taken out of context. It's beneficial for improving SEO and making content more accessibleThe syntax for using the `<article>` element in HTML is as follows:

```javascript
<article>
    <!-- Your content goes here -->
</article>
```

For Example:

```javascript
<article>
    <h2>what is Git</h2>
    <p>Git is a distributed version control system (VCS) designed to track changes in source code during software development. </p>
    <p>It allows multiple developers to collaborate on projects by providing a framework for managing and recording changes to the codebase over time</p>
</article>
```

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/6wloregkwinjfgnw8myv.jpeg)
