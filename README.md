# PageWidgets


Python widgets to create HTML content for pages

## Dry Technical Overview

**PageWidgets** is a python library for creating web page content.  Widgets are provided for:

* Bootstrap widgets
* Charts
* Forms

## Rational and Concept

In most web frameworks, HTML pages are created in a two step process.  First content is created then it is passed to a template that generates the HTML to display the content.  The essential rational behind this design is to separate the layout and rendering of the web page from the task of creating the page's content.

While this design has much to recommend it and is certainly appropriate for sites with many pages and/or separate groups for content creation and page design, in many instances those conditions simply do not exist.  In many cases the developer responsible for content creation is also responsible for the template.  Additionally, the approach requires looking in several places to understand the page.  This is a particular problem when the template needs or uses various programatic features.

Additionally:

* The creation of templates, particularly complex templates, is an expensive and error prone process.  Most template languages are rather adhoc affairs and represent yet another artibrarily different technology in the application stack.
* As a practical matter HTML is a rather verbose and brittle technology.  As a general proposition it requires both opening and closing tags and missing tags are often catastrophic.  One need only consider the consequence of a missing **</div>** on a pages rendering to appreciate the issues.


```
**Example page widget here
```


# License

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/deed.en_US">
<img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a>
<br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">DjangoPages</span> by
<span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Richard Bell</span> is licensed under a
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/deed.en_US">
Creative Commons Attribution-NonCommercial 4.0 International License</a>.<br />Based on a work at
<a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/rbell01824/django_pages" rel="dct:source">github.com/rbell01824/djangopages</a>.

# Getting Started

TBD # todo 1:

# Installation

TBD # todo 1:
