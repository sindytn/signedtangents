---
layout: post
title: Starting Project Euler
summary: Why I'm starting Project Euler
tags: ["#math"]
---

Recently I've started to suspect that my brain is atrophying. Whether reasoning about something deeply technical or attempting a quick computation, moving with the same focus or nimbleness that I had, say five or ten years ago, feels harder. It's time to hit the gym. 

Project Euler is one of many options for a brain workout. I chose it because the problems are fun to solve and the process is different enough from my normal work that it feels like a break. And I miss doing math.

I'll be sharing solutions here. To start, here it is for [problem 1](https://projecteuler.net/problem=1):


<details>
<summary>Solution</summary>
We compute the sums of multiples of 3 and 5, then subtract the double-counted numbers, which are the multiples of 15. Each term is an arithmetic series which can be evaluated by $$\sum_{k=1}^{n}k = \frac{1}{2}n(n+1)$$ This gives us

$$
3 \sum_{k=1}^{333} k + 5 \sum_{k=1}^{199} - 15 \sum_{k=1}^{66}k = 233168
$$
</details>