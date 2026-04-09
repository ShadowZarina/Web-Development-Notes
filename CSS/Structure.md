# CSS

From the book "HTML and CSS: Design and Build Websites" by Jon Duckett

## RULES OF CSS

CSS = Cascading Style Sheets
- separate content (HTML) from presentation
- SYNTAX: CSS rule = consists of Selector & Declaration Block
- SELECTOR: the HTML element you want to style
- DECLARATION: property & value (eg. color: blue;)

p {
  color: red;
}

p -> element/selector
color -> property
red -> value
color: red; -> declaration

## LINKING TO HTML
1. EXTERNAL (Best Practice)
- Link **external .css file** in <head> using <link rel="stylesheet" href="style.css">
2. INTERNAL
- Using <style> tags in the **head**
3. INLINE
- using the "style" attribute **directly** on an element

### EXAMPLES:

#### External Linking:

<head> 
  <link rel="stylesheet" href="style.css">
</head>

#### Internal Linking:

<head>
<style>
  p {
    color: red;
  }
</style>
</head>

#### Inline Linking:

<body>
  <p style="color: red;">
    Hello World
  </p>
</body>


### ORDER OF PRECEDENCE (IMPLEMENTATION-WISE)
1st Priority - Inline (closest to the HTML tag)
2nd Priority - Internal (within HTML file)
3rd Priority - External (outside HTML file)

## COLORS
- color: sets text color
- background-color: sets background color of element

## COLOR FORMATS
- Hex Codes: #RRGGBB
  - 0 is the lowest value, F is the highest value
  = #000000 is black, #ffffff is white
  = #ff5733
- RGB: rgb(red, green, blue)
  - 0 is the lowest value, 255 is the highest value
  = rgb(255,87,51)
- Color Names: simple keywords
  = red, navy, transparent

## TEXT
- font-family: choosing typefaces
  = Serif, Sans-serif, Monospace
- font-size: units include (px, em, rem)
- font-weight & font-style: for boldness and italicization respectively
- spacing:
  - line-height: vertical spacing between lines
  - letter-spacing: space between characters
  - text-align: alignment (left, right, center, justify)

## THE BOX MODEL
Every element in CSS is a rectangular box
- Content: text/images inside
- Padding: transparent space INSIDE the border
- Border: line surrounding padding AND content
- Margin: transparent space OUTSIDE border to separate elements

## STYLING LISTS, TABLES & FORMS
- Lists
  = remove bullets with list-style-type: none;
  = use custom images
- Tables
  = use border-collapse: collapse; to prevent double borders
  = add padding to cells for readability
- Forms
  = styling input, textarea, button to create clickable interfaces rather than default browser styles

