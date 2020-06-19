---
layout: note
title: Transclusion
parent: Web Development
grand_parent: Working Notes
nav_exclude: true

---
# Transclusion
Transclusion is the inclusion of a document (or prat of a document) within another document by referance.

For example:
[Links](https://maykind.com)
-or-
Backlinks [[Web Development]]

https://en.wikipedia.org/wiki/Transclusion

Usually performed when the referencing document is displayed and should be automatic and transparent to the end user.

The result of transclusion is a single integrated document made of parts assembled dynamically from separate sources. (Possibly stored on different computers or servers in disparate places).

Transclusion facilitates [[TK Modular Design]] a resource is stored once and distributed for reuse multiple times. Updates or corrections to a resource should be reflected in any referencing documents.

## Best Practices
### Context neutrality
Transclusion works better when transcluded sections of text are self-contained, so that the meaning and validity of the text is independent of context. For example, formulations like "as explained in the previous section" are problematic, because the transcluded section may appear in a different context, causing confusion. What constitutes "context neutral" text varies, but often includes things like company information or boilerplate.

See also [[TK Note titling best practices]]

### Parameterization
Under some circumstances, and in some technical contexts, transcluded sections of text may not require strict adherence to the "context neutrality" principle, because the transcluded sections are capable of parameterization. Parameterization implies the ability to modify certain portions or subsections of a transcluded text depending on exogenous variables that can be changed independently. This is customarily done by supplying a transcluded text with one or more substitution placeholders. These placeholders are then replaced with the corresponding variable values prior to rendering the final transcluded output in context.