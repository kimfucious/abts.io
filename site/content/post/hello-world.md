---
title: "Hello Fibonacci"
date: 2019-01-01T17:16:39+07:00
tags: 
  - recursion
  - fibonacci
categories: 
  - javascript
  - coding
description: The Fibonacci Sequence
---
# Hello Fibonacci!

{{< highlight go "linenos=table,hl_lines=3,linenostart=1" >}}
function fib(n) {
  if (n <= 2) return 1
  return fib(n-1) + fib(n-2)
}
{{</highlight>}}

Why is the text all indented and shit?!

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/0/04/Liber_abbaci_magliab_f124r.jpg" title="Fibonacci's Liber Abaci" >}}
