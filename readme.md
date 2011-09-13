# AP Museum Core
Contributors: jazzs3quence  
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=AWM2TG3D4HYQ6  
Tags: two-columns, white, custom-menu, threaded-comments, sticky-post, fixed-width, custom-background, featured-image-header, featured-images, post-formats, right-sidebar  
Requires at least: 2.8  
Tested up to: 3.2.1  
Stable tag: 0.2

A simple WordPress theme/framework with support for post formats, thumbnails, background, header, menus and more...

## Description 

AP Museum Core will be the core framework behind all commercially-released <a href="http://museumthemes.com">Museum Themes</a>.  It supports all built-in WordPress theme options like post thumbnails, post formats, custom backgrounds, etc.

## Installation 

1. Unpack and upload the contents of `AP-Museum_Core.zip` to the `/wp-content/themes/` directory.
2. Activate the theme through the *Themes* menu in WordPress.
3. That's it!  

## Screenshots 

There are currently no screenshots.

## Changelog 

### Version 0.1
#### 6/14/2011

* initial commit (forked from AP-blueprint)
* updated style.css with name, new version # and description 
* removed landing sites 
* removed theme options 
* removed git README 
* removed calls to get-theme-options.php 
* removed twitter widget from footer (discontinuing hard-coded twitter feeds in the theme since this is easily added with Jetpack or any of a million other plugins)
* removed left/right if statement (may bring this back in some revised form)
*  removed social media links (may bring these back but probably won't)
* removed twitter widget (see note on last footer commit)
* uncommented the dynamic title tags in the header (will change these around later)
* changed path to reset styles
* removed link to non-existant fonts.css (but may add another one later)  
* renamed /blueprint to /css 
* removed tweet button and dynamic twitter variable in sharing block (might remove the sharing block entirely, anyway, since -- again -- sharedaddy is included in Jetpack)

### Version 0.1.1
#### 6/15/2011  

* changed version
* added readme.txt with changelog

### Version 0.1.2
#### 7/22/2011

* updated version
* added menu support
* added automatic feed links
* added custom header stuff
* added custom background support
* added post formats support
* added ap_core_setup
* added fonts
* added style.css call to the functions.php file
* added screen.css and print.css to the style.css
* removed css calls in header.php
* added ie conditional to functions.php
* added versioning relative to theme version to wp_register_style and wp_register_script calls

### Version 0.2
#### 9/12/2011

* fixed ap_core_setup (using wrong hook)
* added nav menus to header.php
* removed nav menu fallback default (set to no fallback)
* removed old twitter callback scripts
* changed do_action('wp_footer') to wp_footer.php()
* changed footer text
* added footer menu
* added Inconsolata font for monospaced elements (pre, tt, code and .code class)
* added more typography classes for potential typography settings options
* added new theme options page and sidebar options (still a work in progress)
* updated version
* removed sharing options from single posts

### Version 0.3
#### 9/13/2011

* NOW USING BOILERPLATE HTML5!
* replaced blueprint resets and print styles with BPH5 css
* removed ie conditional stylesheet (in favor of BPH5 conditional classes)
* removed separate typography stylesheet (replaced with inline css in style.css)
* leaving the embedded typography in a separate stylesheet but changing the call to 'stylesheet_directory' rather than 'template_directory' -- this is so each child theme can define its own styles without loading the fonts from the parent theme
* added readme.md for the benefit of Git