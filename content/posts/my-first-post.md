---
title: "My First Post"
subtitle: "python · statistics · life · random thoughts"
author: "Vishad Bhalodia"
date: "2021-04-29"
show_toc: false
tags: ["firstpost", "init"]
---

Try adding some code to the post -

```python
class Solution:
    def longestCommonPrefix(self, strs: List[str]) -> str:
        if not strs:
            return ""
        if len(strs) == 1:
            return strs[0]

        strs.sort()
        p = ""
        for x, y in zip(strs[0], strs[-1]):
            if x == y:
                p += x
            else:
                break
        return p
```

Let's try some math. As the source is a Markdown and not an RMarkdown file, one has to use special syntax to enable math rendering. Specifically, one can use

1. `\\( <LaTeX> \\)` and `\\[ <LaTeX> \\]`,
1. `` `$<LaTeX>$` `` and `` `$$<LaTeX>$$` ``,

for inline and display mode, respectively. In the former, one can use `\newline` or `\\\\\` instead of `\\` to break lines.

Let \\(x = 1\\) and

\\[
\begin{align}
z^2 &= x^2 + y^2 \\\\\
x &= 3 \newline
y &= 4.
\end{align}
\\]

Alternatively, let `$x = 1$` and

`$$
\begin{align}
z^2 &= x^2 + y^2 \\
x &= 3 \\
y &= 4.
\end{align}
$$`
