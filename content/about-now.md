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



#### Code block with backticks

```
const addTwo = function(n){
	return n+2;
}

console.log(addTwo(5)); 

```

#### Code block with Hugo's internal highlight shortcode
{{< highlight js >}}
const addTwo = function(n){
	return n+2;
}

console.log(addTwo(5));
{{< /highlight >}}

