---
layout: default
title: Home
---

Typography and links
Bootstrap sets basic global display, typography, and link styles. Specifically, we:

Remove margin on the body
Set background-color: white; on the body
Use the @baseFontFamily, @baseFontSize, and @baseLineHeight attributes as our typographic base
Set the global link color via @linkColor and apply link underlines only on :hover
These styles can be found within scaffolding.less.

Reset via Normalize
With Bootstrap 2, the old reset block has been dropped in favor of Normalize.css, a project by Nicolas Gallagher and Jonathan Neal that also powers the HTML5 Boilerplate. While we use much of Normalize within our reset.less, we have removed some elements specifically for Bootstrap.
