# Markdown Tips

Better living through Markdown...

## Images

<img src="https://imgs.xkcd.com/comics/standards.png" align="left"> The HTML image tag isn't "Markdown flavored" but it is more readable (IMHO) than the Markdown markup for images _plus_ it feels more intuitive to do some of the more obvious "wants" like wrapping text around an image and scaling an image.

**Wrapping text around an image**

```html
<img src="..." align="left">
```
`align="right"` also works.

**Scaling an image**

```html
<image src="..." width="50%">
```

Of course you can also set the height. Set just one to make the scaling proportional. Any legal CSS units can be used.
