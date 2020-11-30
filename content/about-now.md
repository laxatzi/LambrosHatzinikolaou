---
title: "Now"
description: "What I am currently doing."
date: "2019-02-28"
author: "Hugo Authors"
slug: /about/now
menu:
  about:
    identifier: about
    name: About
    title: About
    url: /about
    weight: 1
  subpage:
    identifier: now
    parent: about
    name: Now
    title: Now
    url: /about/now/
    weight: 10
---

Just a subpage of About.

#### Code block with Hugo's internal highlight shortcode
{{< highlight html >}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

#### Code block with Hugo's internal highlight shortcode
{{< highlight js >}}
const addTwo = function(n){
	return n+2;
}

console.log(addTwo(5));
{{< /highlight >}}


#### Code block with Hugo's internal highlight shortcode

{{< highlight css >}}
.post-tags li {
    display: inline;
    margin-right: 1em;
    /* padding: 5px 7px; */
    border: 1px solid transparent;
    border-radius: 2px;
    background-clip: padding-box;
}

.post-tags li a {
    color: var(--font-color);
    font-style: oblique;
}
{{< /highlight >}}
