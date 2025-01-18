# infinite_scroll
Sure, here is a Read.me file for the given code:

# Infinite Scrolling Animation

This code creates a simple infinite scrolling animation using HTML and CSS.

## HTML Structure

The HTML code consists of the following elements:

* `<!DOCTYPE html>`: Declaration that defines the document type as HTML.
* `<html>`: Root element of the HTML document.
* `<head>`: Container for metadata about the document.
    * `<meta charset="UTF-8">`: Defines the character encoding of the document as UTF-8.
    * `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Sets the viewport properties to ensure proper responsiveness on different devices.
    * `<title>Infinite Scrolling Animation</title>`: Specifies the title of the webpage.
    * `<link rel="stylesheet" href="./style.css">`: Links the external CSS stylesheet to the HTML document.
* `<body>`: Container for the visible content of the webpage.
    * `<section class="tutorial">`: Main section element containing the animation.
        * `<div class="container">`: Container element for the scrolling content.
            * `<div class="scroller">`: First scroller element containing the list items.
                * `<p class="item">`: Individual list item elements containing programming languages.
            * `<div class="scroller">`: Second scroller element containing the same list items (for a mirrored effect).
        * `</div>`: Closing tags for all container elements.

## CSS Styling

The CSS code styles the various elements of the webpage as follows:

* `body`: Sets the background color to black and the font family to system-ui or sans-serif.
* `.tutorial`: Defines the height, width, margin, display, justification, and alignment for the main section.
* `.container`: Sets the display to flex, enables overflow hiding, and applies a mask image to create a viewing window effect.
* `.scroller`: Sets the display to flex, introduces a gap between items, and animates the scrolling using the `@keyframes` rule.
* `.scroller:nth-child(2)`: Targets the second scroller element and applies a different animation to create a mirrored scrolling effect.
* `.item`: Styles the individual list items with font size, text transformation, font weight, letter spacing, color, padding, border radius, and box shadow.
* `@keyframes scroll` and `@keyframes scroll2`: Define the animation keyframes for the scrolling effects, specifying the starting and ending positions for the translation along the X-axis.

## Functionality

The code creates two scroller elements containing a list of programming languages. The CSS animations create an infinite scrolling effect where the list items appear to move continuously from right to left for the first scroller and left to right for the second scroller, creating a mirrored effect.

## Usage
