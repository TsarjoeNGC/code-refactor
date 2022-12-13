# Code Refactor Challenge
## Description

# Deployed Link
https://tsarjoengc.github.io/code-refactor/

# HTML CSS Refactor

Refactoring is a recommended approach for incrementally improving the CSS codebase while maintaining the current look and feel (design).


## Key Topics

- Navigating the file tree
- Creating, copying, and removing files and directories
- Fullscreen mode
- Semantic elements, tags
-Attributes
-Best practices: indentation, file naming conventions and directory structure


## What is Refactoring 
Refactoring is the process of rewriting and restructuring the code to improve the design of the code base. This practice can be applied to any language but this article will focus on HTML and CSS. When refactoring, here are some goals to keep in mind:

Rewrite to reduce complexity. It’s easy to fall into the trap of over-engineering, especially when you’ve just learn a cool new trick. But try to keep in mind to only add what you need.

Make it reusable. Being able to reuse snippets of code means less code overall and more consistency.

Think about how you can make it flexible. This can help to make it easier to reuse and extend features by adding onto existing code snippets.

Make the code easy to read. Use whitespace, indentation and comments for organization. Show your intent by using descriptive class names and comments. Write your code as if you are writing it for someone else to understand. And in some cases you probably are! And even if you are only writing it for yourself, it’s not unusual to come back to a project months later and feel like you have to re-familiarize yourself with the codebase again.

Let’s take a look at some ways to refactor HTML and CSS.
## Reduce HTML markup
Something that happens often when adding content and styles to our web projects is inadvertently using too much HTML markup. For example, the <div> element is often used to group or wrap elements to add CSS to them. But it’s not always necessary to throw a <div> around the element that needs to be styled. Every HTML element is its own box and can be styled. In this example, the CSS style will look the same whether you add it to the <h1> element or its container element.

## Create rules for writing CSS
When it comes to CSS, organizing your code from the beginning can help reduce the amount of refactoring needed later. I use comments for grouping related CSS styles into sections or modules, to lower the chances of writing duplicate or extra code.

Any characters can be included within a CSS comment, as long as they are enclosed within the opening and closing slash and asterisks syntax (/* */). I prefer to add dashes underneath the text, to visually block out these sections. Then I’ll use this same comment style to organize other groupings of related styles for the specific portions of the webpage.
I always start with the base CSS, which are styles that are applied globally. Then add more specific styles as needed. When I say global CSS, I’m referring to the styles that are applied to all or most of the elements on the page, such as the font-family, defining font colors, general margin and padding styles and font sizes. These global styles are applied to the basic type selectors such as body, headings and links. Then get more specific as needed by applying styles using CSS classes. Even then, start with the more generic class styles like page wrappers and page layout styles.
## Reduce repetitive code
If you notice that you are declaring the same styles over and over again, this a good indicator that you could probably do some refactoring. Let’s go over a couple ways to make repetitive code more efficient.
## Combining selectors
Combine selectors to target multiple elements at the same time and use the separate declaration blocks for specific element styles. It’ll be easier to make updates to the shared styles and will reduce the amount of code.

## Create reusable classes
Creating reusable classes will also also reduce repetitive code. Instead of writing the same style for each element with a different selector, create a shared class that can be added to multiple elements. 
## Helpfull Links

 - [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
 - [Version Control](https://en.wikipedia.org/wiki/Version_control)
 - [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
 - [Dev Docs](https://devdocs.io/)


