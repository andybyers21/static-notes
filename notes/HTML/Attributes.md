---
layout: note
title: Attributes
parent: HTML
nav_exclude: true
---

# Attributes
Elements can also have attributes which don't appear in the end user content, such as `<p class="editor quote">This is the best thing I've ever read</p>` in which case the attribute is `class="editor quote"`. In this example `class` is the attribute name and `"editor quote"` is the attribute value. 
	- The `class` attribute allows you to give the element an identifier that can be used to target the content of the element. (With CSS for example). 
	
Attributes should always have the following:
	- A space between it and the element name (or the previous attribute, if the element already has one or more attributes).
	- The attribute name followed by an equal sign.
	- The attribute value wrapped by opening and closing quotation marks.

> Note: Simple attribute values that don't contain ASCII whitespace (or any of the characters  `" ' = < > )` can remain unquoted, but it is recommended that you quote all attribute values, as it makes the code more consistent and understandable.