---
title: Test
publishDate: 17 Sep 2023
author: Stig Ark
description: Power pages custom header.
layout: ../../layouts/BlogPost.astro
---
#### **TEST**

Lorem ipsum dolor sit amet.



<!--StartFragment-->

<html lang={content.lang || 'en'}>

    <head>

        <BaseHead {title} {description} {permalink} />

    </head>



    <body>

        <BlogHeader />

        <div class="wrapper">

            <BlogPost {title} {author} {authorURL} {heroImage} {publishDate} {alt}>

                <slot />

            </BlogPost>

        </div>

    </body>

</html>

<!--EndFragment-->



![Lorem ipsum](/assets/blog/sindri1.jpg "Tøff")