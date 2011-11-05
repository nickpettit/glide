# Glide: A CSS3 Animation Library

The purpose of Glide is to provide a library of CSS3 animations. These animations should be robust and reusable in a wide variety of contexts, but flexible enough to be adjusted when necessary.

# Usage

Glide is written in Sass, using the SCSS syntax. You must have Sass installed, preferably the latest version. You also will need the gem for bourbon. For links to these projects, see the "Requirements" section below.

To use Glide, simply include both bourbon and Glide into your .scss file, like this:

    @import "bourbon/bourbon";
    @import "glide";


# Requirements

- Sass: http://sass-lang.com/
- bourbon: https://github.com/thoughtbot/bourbon

## Notes:

Currently, only the latest version of Google Chrome is supported officially. However, the goal is to make these animations work across as many browsers as possible. Glide animations are also not chainable in any sense of the word. A solution for this is in the works.
