# gatsby-remark-images-custom-widths

A fork of [gatsby-remark-images](https://www.gatsbyjs.org/packages/gatsby-remark-images/) that displays images at a custom width, via the width attribute on an `img` in markdown:

```md
<img src="./image.jpg" alt="My image" width="500px"/>
```

The width used in this attribute overrides the `maxWidth` option passed into the plugin, so the image is processed based on the specified width. (Or more correctly, the set of responsive images generated are based around this width instead).
