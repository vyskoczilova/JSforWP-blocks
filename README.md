# JSforWP Blocks

Final project for [Javascript for WP Bootcamp](http://url.kybernaut.cz/js4wp-bootcamp-github) by Zac Gordon - a plugin extending the Blocks editor.

The plugin will ideally consist of two parts which I need for tailor made themes with Blocks editor the most.

1. Section block
1. Templating kit

## Section block

A top wrapper element for other bloks with possibility to add ID, classes, background-color etc. 

### Behavior

* no section block nesting
* when used, all other parts of content will be wrapped into a section block as well, e.g. either you don't use any section or you must have use them consistently on the page
* ? clean the code on post save and remove section block when only a single section block left in the content without any additional attributes

## Templating kit

Create a templating kit for sets of pre-build layouts as a template starter (kind of page-template system replacement, but less strict).

### Behaviour

* STEP 1: fill an empty page (or clean it up on demand) with predefined sets of blocks (hardcoded & shipped with a theme) 
* STEP 2: add a preset set of blocks s (e.g., 3 columns layout with an image (icon), headline and paragraph) to the end of the current editor
* STEP 3: let a user save the template or set of blocks (but not globally as the Gutenberg do, just empty not filled structure ready to fill in again)