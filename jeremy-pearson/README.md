##### How did you determine which rules should be placed in each new CSS file?

Based on this structure:

base.css should contain any general styling on top of what is provided by a reset.css or normalize.css file (these files will be discussed in further detail in lecture)
Apply to elements such as body and main
Examples include styling of overall font and background color

layout.css should contain general positioning on the page
Apply to elements such as header, footer, nav, aside
Classes and IDs can be included here

modules.css should contain smaller components on the page
Apply to elements such as list items, individual images, specific paragraphs
Classes and descendant selectors should primarily be included here

state.css should contain any styling that changes upon user interaction or state change
Apply to hover state, before or after clicking on a link, focus and blur effects
Pseudo-classes and pseudo-elements should be included here

theme.css should contain small changes on top of all other normal styling
Applying temporary changes, such as a holiday theme

Along with adding the imports for the font as needed in multiple.
---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

None re-factored.
