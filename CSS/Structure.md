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

#### Inline Linking:

### ORDER OF PRECEDENCE (IMPLEMENTATION-WISE)
1st Priority - Inline (closest to the HTML tag)
2nd Priority - Internal (within HTML file)
3rd Priority - External (outside HTML file)
