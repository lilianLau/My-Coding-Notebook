## Apply the Ellipsis to Multiline Text in CSS

I learned it from the article shared by [GeeksforGeeks](https://www.geeksforgeeks.org/how-to-apply-an-ellipsis-to-multiline-text-in-css/).

To apply the ellipsis to more than one line of the text in css, we can use the CSS code as below:

```css
.text {
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 2;
    overflow: hidden;
    text-overflow: ellipsis;
}
```

-   `display: -webkit-box;` is used for multiline ellipsis

-   `-webkit-box-orient: vertical;` is used for set the box orientation to vertical

-   `-webkit-line-clamp: 2;` is used to limit the text to 2 lines

-   `text-overflow: ellipsis;` is used to add the ellipsis (...) at the end of the truncated text
