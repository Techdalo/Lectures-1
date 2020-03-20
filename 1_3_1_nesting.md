---
title: Nesting
layout: page
---

As you've already seen in the previous lessons HTML elements can be written after one another. But even more important, HTML elements can be nested. Nesting is normally quite intuitive, so you shouldn't have much trouble nesting elements in HTML. Nevertheless, you should remember that there are some rules regarding nesting. The most important rule for nesting elements is that the start and end tag of the child element must always stay inside the parent element. Have a look at the following code example:

<iframe src="https://tumwlfe-mooc.srv.mwn.de/api/edx/22" style="width: 100%; height: 200px; border: 1px solid #dedede;" allowfullscreen="true" frameborder="0"></iframe>

In this example the `<strong></strong>` element is a child of the `<p></p>` element. The `<p></p>` element is therefore the parent of the `<strong></strong>` element. The start and end tag of the `<strong></strong>` element stay inside the `<p></p>` element.

### Task

Until now the weather forecast only consists of the weekdays with a short textual description of the upcoming weather. In a new version, which can be seen below, the temperature for each day is already added at the end of each paragraph. As the temperature is of high importance for many people, you want the temperature to be displayed bold. This should be done by using the `<strong></strong>` element, but something went wrong. Can you fix it?


<!-- Exercise Editor 41 -->

