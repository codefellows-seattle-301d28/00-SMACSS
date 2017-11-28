##### How did you determine which rules should be placed in each new CSS file?

  I placed all my basic css in base.css including amy * css, body.  These are basic elements, not ids or classes.

  Layout.css contains css for elements that are major layout components ie, header, footer, main, aside.

  Module.css represents the sub-components of the modules.  Reusable css for the smaller portions of the layout elements as well as more specific selectors.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

When I read the SMACSS documentation, it seemed to frown on multiple selectors, being too specific, and repeating yourself.  I made comma separated selectors for repeating css and removed the css for elements that all set the same one rule.  I removed unnecessary specific selectors and replaced with them with fewer broad selectors.  SMACSS like to class the crap out of everything, so I classed a few of the ul and li elements so i could get rid of descendent dependent selectors.
