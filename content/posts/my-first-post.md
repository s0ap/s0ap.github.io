---
title: "My First Post"
subtitle: "python · statistics · life · random thoughts"
author: "Vishad Bhalodia"
date: "2021-04-29"
show_toc: false
tags: ["firstpost", "init"]
---

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

Placeholder text.
