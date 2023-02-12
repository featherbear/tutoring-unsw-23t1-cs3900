# Setup

Clone this repo and its submodules

# Editing your posts

Create a new post with `hugo new YOUR_SLIDE_NAME.md`  
This post will be created as a _draft_

When the post is finalised, remove the `draft: true` property from the front matter

## Colours

If the post exists within a directory, it will be colourised.  
The colour can be overrided in the front matter

## Front matter

* `hidden` - `true` / `false` - Whether to hide the presentation from the main page
* `redirect` - URL to redirect the presentation to
* `tileColour` - `#HEXCODE` / `colour` - Tile colour

# Previewing your posts

To preview the public view, run `hugo server`  
To preview draft post as well, run `hugo server -DEF`  
