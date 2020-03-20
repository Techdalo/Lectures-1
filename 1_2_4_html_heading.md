---
title: HTML Heading
layout: page
---

In HTML, paragraphs are used to display some textual content, exactly like it is done with the paragraph you are reading right now. **Headings** are used to structure the content of the website (mostly paragraphs) and therefore have the same purpose as the headings in normal documents, for example Word-Documents or PDFs.

```html
<h#> ... </h#>       with # ∈ [1, ..., 6]
```

A heading can be created by using the tag name h#, where the # stands for an arbitrary number between 1 to 6. This number represents the hierarchy-level of the heading. 
An `<h2></h2>` heading will always be more important than an `<h3></h3>` and less important than `<h1></h1>`. The following section shows the headings 1 to 6.

<iframe src="https://tumwlfe-mooc.srv.mwn.de/api/edx/18" style="width: 100%; height: 300px; border: 1px solid #dedede;" allowfullscreen="true" frameborder="0"></iframe>

### Task

Now that you've fixed all the bugs in the last exercise, your new goal is to make the weather forecast more readable. Structure the HTML document with the heading element. Use a first level headline for the title "FORECAST" and paragraphs for the descriptions. The weekdays are less important than the "FORECAST" but more important than the simple descriptions of the weather, therefore assign a second level headline.

<!-- Exercise Editor ID 39 -->