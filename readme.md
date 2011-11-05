# Glide: A CSS3 Animation Library

The purpose of Glide is to provide a library of CSS3 animations that are robust and reusable in a wide variety of contexts, but flexible enough to be adjusted when necessary.

# Requirements

Sass: http://sass-lang.com/

# Usage

Glide is written in Sass, using the SCSS syntax. You must have Sass installed, preferably the latest version. For more details, see the "Requirements" section above.

To use Glide, simply include Glide into your .scss file, like this:

    @import "glide";

Then, in your .scss file, you can apply glide animations to your page elements, like this:

    #fade {
      @include fade();
    }

Glide animations have some default settings, but you can pass your own, like this:

    #fade {
      @include fade($iteration-count: infinite);
    }

The arguments that can be passed to Glide animations are the same as the values for CSS3 animations. However, some animations can also accept a background argument, so be sure to check the glide.scss file for the specific animation you want to use. Below is a list of all the arguments with example values:

    $duration: 1s
    $timing-function: linear
    $delay: 2s
    $iteration-count: 1
    $direction: alternate
    $background: #06A

Glide comes with a premade project that features all of the animations currently available. Simply open the index.html file in your web browser (Google Chrome works best right now) to see all of the animations in action. 

## Notes

Currently, only the latest version of Google Chrome is supported officially. However, this is unacceptable. The goal is to make these animations work across as many browsers as possible. Glide animations are also not chainable in any sense of the word. A solution for this is in the works.
