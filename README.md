# Homework Assignment 1: Code Refactoring

## URLs
1. Deployed application: https://emangano2816.github.io/hw1_code_refactor/
2. GitHub Repository: https://github.com/emangano2816/hw1_code_refactor

## User Story
```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```
## Acceptance Criteria
```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
## Modifications Made to Achieve Acceptance Criteria

To meet the acceptance criteria provided above, the following changes were made to the original code:

1. Most div tags were replaced with semantic tags (i.e., header, nav, main, section, aside, and footer) to provide better accessiblity and maintainability.
2. Inserted spaces to indicate the start of a new "section" of code within the HTML.  Made sure to use indentation where appropriate to increase readability.
3. Added alt attributes to all images included in HTML file.
4. Heading attributes fall in a sequential order within each section they are used.
5. Modified the title to be more descriptive and in-line with the h1 tag.

## Additional Modifications Made to Code

To exceed expectations and improve the codebase for longterm sustainability, the following changes were made to the HTML file:

1. Included a title attribute inside the link tag within the head tag to remove ambiguity.
2. The "search engine optimization" link was broken.  Fixed the link by adding an id attribute to the search engine optimization section.
3. Inside the main tag and also the aside tag, all three sections were being styled the same, however, unique class attributes were used for each section.  Simplified this by using the same class attribute for all three sections within the main tag and then also within the aside tag.  By doing this, was able to simply the CSS file.

Inside the CSS file the following changes were made:

1. Included comments to increase readability and understanding.
2. Regrouped code so that styles within each semantic tag were grouped together.
3. Reordered code so that the flow of the CSS file followed the semantic structure in the HTML file.
4. Updated class names, where appropriate (i.e., due to updates in HTML).  
5. Elimanted chunks of code due to the use of a single class attribute within the main tag and the aside tag.
