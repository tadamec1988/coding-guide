# U+ Coding Guide

This document describes best practices to follow when coding html+css.

## TOC

- [Workflow](WORKFLOW.md)
	- [Understanding design](#design)
- Stylesheet architecture


## Workflow

### Understanding project desing <a id="design"></a>

// TODO

## CSS Stylesheet architecture

We adhere to component/module-based approach [css-bliss](https://github.com/gilbox/css-bliss) which shares common ideas with 
[BEM](http://bem.info), [SMACSS](https://smacss.com/), [OOCSS](http://oocss.org/), [SUITECSS](https://github.com/suitcss),
but adds further restrictions to **fix design flaws in CSS**.

To be studied in following order

- [Walkthrough](http://gilbox.github.io/css-bliss/walkthrough/release/)
- [Chapters in README](https://github.com/gilbox/css-bliss)
- [How css-bliss tackles problems with complex CSS identified by Facebook](https://github.com/gilbox/css-bliss/blob/master/solving-complexity.md)
- [Common mistakes](https://github.com/gilbox/css-bliss/blob/master/common-mistakes.md)

All credits go to [Gil Birman](https://github.com/gilbox)

This architecture is preprocessor independent. 
We are using SASS to make things DRY.
