## How to Fill an Image Size Without Stretching in CSS ?

I learned from the article by [geeksforgeeks](https://www.geeksforgeeks.org/how-to-fill-an-image-size-without-stretching-in-css/).

We can set a default width and height for the image. Then, use the `object-fit: cover` property to ensure that the image covers the entire container without stretching it!

```css
.img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}
```
