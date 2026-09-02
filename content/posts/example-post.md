+++
title = "Example Post"
date = "2026-09-02T10:00:00Z"
draft = false
toc = true
math = true
tags = ["example", "meta"]
categories = ["notes"]
series = ["getting-started"]
description = "A sample post demonstrating metadata, table of contents, and LaTeX math."
cover = ""
keywords = ["hugo", "example", "latex"]

[author]
  name = "kamilianos3"
+++

# Introduction

This post exists to show the moving parts of a new entry in *The Mind Palace*:
front matter metadata, an automatic table of contents, and LaTeX math.

## Background

Every post carries TOML front matter. The `toc = true` flag renders the table of
contents box above, built from headings between level 1 and level 3.

### Prior art

The theme is [Hello Friend NG](https://github.com/rhazdon/hugo-theme-hello-friend-ng).
Math rendering is layered on top with KaTeX.

# Math

Inline math such as $E = mc^2$ sits in the flow of a sentence. Display math gets
its own line:

$$\int_{-\infty}^{\infty} e^{-x^2}\,dx = \sqrt{\pi}$$

## Working with equations

You can also use bracket delimiters:

\[
\sum_{k=1}^{n} k = \frac{n(n+1)}{2}
\]

### Next steps

Duplicate this file, change the front matter, and start writing.

# Conclusion

That is the whole setup: metadata, contents, and math.
