# KEY TERMS

1. HTML
  - Hypertext Markup Language
  - the STRUCTURE; it describes what things are (headings, paragraphs, lists)
2. CSS
  - Cascading Style Sheets
  - the PRESENTATION; describes how things look (color, font, position)
3. Text Editor
  - the tool used to write code (eg. Notepad++, VS Code, Sublime)
4. Site Map
  - diagram showing the hierarchy of pages and how they link (like a family tree for your site)

# HTML TAGS & ELEMENTS
- eg. `<html>, <body>, <h1>, <p>`
- elements consisting of an opening tag, content, and closing tag


# LAYOUT & DESIGN


## The Box Model
  = Think of every element in HTML as a rectangular box
  = COMPONENTS: Content -> Padding -> Border -> Margin

## CONTROLLING POSITION
- Normal Flow = how elements stack naturally (block vs inline)
- Floats: moving elements to the left or right (used for columns)
- Positioning: Relative, Absolute, Fixed positioning
- Visual Hierarchy = using size, color & contrast to guide the user's eye to the most important info

Relative = original/normal position; moved using `top`, `left`, `bottom`, and `right`

Absolute = removed from document flow

Fixed = putting actual coordinates/number of location

**Relative moves an element from its normal spot, Absolute places it relative to the nearest parent container, and Fixed locks it to the viewport (screen)**


# DESIGNING NAVIGATION

Most Efficient Method
- Use an unordered list `<ul>` of links `<a>`

Styling the Nav
- Remove bullets (list-style-type: none;)
- Displaying list items inline / floating them to create a horizontal bar
- States: Visual cues for link, visited, hover & active states to provide user feedback

# DATA ENTRY SELECTION (FORMS)
- Use <form> to contain the form
- Inputs: come in multiple types including:<br>
  = Text Input -> short answers (name, email)<br>
  = Textarea -> long answers (comments, messages)<br>
  = Radio Buttons -> select one option from a list (gender, yes/no)<br>
  = Checkboxes -> select multiple options (interests)<br>
  = Dropdowns (<select>) -> select from a long list without taking up space<br>
  -- indicated using `<input type="(insert type)" />`<br>
- Labels -> tell the users what each field is for


# PROMOTING YOUR WEBSITE

- SEO = Search Engine Optimization
- On-Page = using keywords in <title>, <h1>, and body text naturally
- Alt Text = describing images for search engines (and blind users)
- Analytics = using tools (eg. Google Analytics) to track who visits your site & what they look at
- Meta Tags = providing descriptions in the <head> that appear in search results
- Domain Names = choosing a memorable URL relevant to the brand
