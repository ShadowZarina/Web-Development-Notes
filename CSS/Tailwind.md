# WHAT IS TAILWIND?
Tailwind CSS is a popular, utility-first CSS framework that lets you build modern, responsive websites without leaving your HTML or JSX. Instead of writing custom CSS or relying on pre-built UI components, you build custom designs by composing low-level utility classes directly in your markup.

## Key Concepts
- **Utility-First:** Classes represent specific CSS properties (e.g., flex, pt-4, text-center), making it fast to style elements directly.
- **Zero-Runtime & Performance:** Tailwind scans your codebase and extracts only the classes you use, compiling them into a highly optimized, small static CSS file.
- **Responsive & Dark Mode:** Built-in prefixes and modifiers (like md:, lg:, and dark:) make handling screen sizes and color schemes straightforward.

# TAILWIND SYNTAX

For a list of all possible syntax in Tailwind CSS, check out [this link!](https://www.creative-tim.com/twcomponents/cheatsheet)

## CORE SYNTAX EXAMPLE

```
<button class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded-lg shadow-md md:py-3 md:px-6 transition duration-200">
  Click Me
</button>
```

- bg-blue-600: Sets a background color using Tailwind's predefined color palette.
- hover:bg-blue-700: Applies a state modifier; changes background color on hover.
- text-white: Modifies typography to set the text color to white.
- font-bold: Modifies font weight.
- py-2 / px-4: Adds vertical padding (0.5rem) and horizontal padding (1rem) via Tailwind's 4px multiplier scale.
- rounded-lg: Sets border-radius to curve the element corners.
- shadow-md: Generates a standard outer box-shadow effect.
- md:py-3: Triggers a responsive mobile-first breakpoint modifier (768px and up) to scale up vertical padding.
- transition duration-200: Automates smooth property transitions over 200 milliseconds.

## REAL-WORLD EXAMPLE (CARD COMPONENT)

```
<div class="max-w-sm mx-auto bg-white dark:bg-zinc-900 rounded-xl shadow-lg overflow-hidden border border-gray-100 dark:border-zinc-800">
  <div class="p-6 flex flex-col gap-4">
    <div class="flex items-center gap-x-3">
      <div class="h-10 w-10 bg-indigo-100 text-indigo-600 flex items-center justify-center rounded-full font-bold">
        AI
      </div>
      <div>
        <h3 class="text-base font-semibold text-gray-900 dark:text-white">Workspace Admin</h3>
        <p class="text-xs text-gray-500">Updated 2 mins ago</p>
      </div>
    </div>
    <p class="text-sm text-gray-600 dark:text-zinc-400 leading-relaxed">
      Easily manage team assignments, invite external guests, and oversee global permission profiles.
    </p>
  </div>
</div>
```

# REFERENCES

[Tailwind CSS Website](https://tailwindcss.com/)
[Tailwind CSS GitHub](https://github.com/tailwindlabs/tailwindcss)
[Tailwind CSS v4 for Beginners | Full Course 2026](https://www.youtube.com/watch?v=9I3JQ1q4IMk)
