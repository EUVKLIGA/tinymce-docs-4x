---
layout: default
title: Legacy Output Plugin (`legacyoutput`)
---

The `legacyoutput` plugin changes TinyMCE's output, producing legacy elements such as `font`, `b`, `i`, `u`, `strike` and use `align` attributes.

This plugin can be useful if you want to use TinyMCE in an HTML mail client or to render contents to Flash.

However, this is **not** intended for use in producing normal web content such as in a CMS. These elements should no longer be used for such purposes since they are deprecated in later XHTML and HTML5 specifications.

**Type:** `String`

**Example:**

```js
tinymce.init({
  selector: "textarea",  // change this value according to your html
  plugins: "legacyoutput"
});
```