---
title: Test
publishDate: 17 Sep 2023
author: Stig Ark
heroImage: /assets/blog/sindri1.jpg
tags:
  - Power Pages
  - HTML
  - FetchXML
description: Power pages custom header.
layout: ../../layouts/BlogPost.astro
---

#### **TEST**

Lorem ipsum dolor sit amet.

<!--StartFragment-->

```html
<html lang={content.lang || 'en'}>
    <head>
    </head>
    <body>
        <BlogHeader />
        <div class="wrapper">
                <slot />
            </BlogPost>
        </div>
    </body>
</html>
```

<!--EndFragment-->

![Lorem ipsum](/assets/blog/sindri1.jpg "Tøff")
