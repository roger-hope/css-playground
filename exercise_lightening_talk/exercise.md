---
## Working in a group of three 👩‍👩‍👧‍👦
- This might be the first time, where you create an artefact together in a group of three
- Look very consciously at group dynamics
- Who makes what, why is one not contributing?
- Makes sense to distribute tasks at the beginning
- Steps
    - Everyone gets their own understanding
    - Discuss
    - One Person makes some small slides
    - Two people create some examples
    - Prep who says what
---
## CSS Lightning talks ⚡
* Talk should be about: 5 - 8 minutes
* Preparation time: 60 minutes
* General structure of the talk
    * Some small bit of theory (2-3 slides is enough)
    * Some live-coding, demonstrating the feature
        * Bonus points for creative/fun examples
    * Show some different use-cases
    * Q&A
* How to go about it
    - Read documentation
    - Be the expert about your topic  - anticipate questions!
    - Find cool things of how people used this bit of technology
        - "Everything you should know about ..."
        - "What you didn't know about..."
    - Upload code example (with pdf-slide) in `frontend-basics/talks/<your-topic>` (before giving the talk 🙏)

**Topics**
1. What can we do with backgrounds? (2)
    - Cover things like: `background-image`, `background-repeat`, `background-position`, [gradients](https://www.w3schools.com/css/css3_gradients.asp)
    - Explain what the parallax effect is and how to implement it ([example](https://www.w3schools.com/howto/howto_css_parallax.asp))
2. What are some remaining selectors and combinators? (2)
    - Cover [CSS combinators](https://www.w3schools.com/css/css_combinators.asp) and [Attribute Selectors](https://www.w3schools.com/css/css_attribute_selectors.asp)
    - Very recently [CSS nesting](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_nesting/Using_CSS_nesting) was published, explain how this makes CSS code cleaner
3. What are pseudo-elements and how to use them? (3)
    - Cover all pseudo-elements but put special emphasis on `::after`, `::before` since it really has [many applications](https://css-tricks.com/7-practical-uses-for-the-before-and-after-pseudo-elements-in-css/#:~:text=CSS%20%3A%3Abefore%20and%20%3A%3A,present%20in%20the%20HTML%20content.) 
4. What are pseudo-classes and how to use them? (3)
    - You do not have to cover all pseudo-classes since they are so many
    - Focus on [Tree-structural pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes?retiredLocale=de#tree-structural_pseudo-classes) (especially `:first-child`, `:nth-child()`, `:only-child`), [User action pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes?retiredLocale=de#user_action_pseudo-classes) (especially `hover`, `active`) and [Functional pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes?retiredLocale=de#functional_pseudo-classes) (all of them)
5. How do CSS animations work? (3)
    - Build a simple animation with the audience
    - But also showcase fancy examples from the internet
    - Show how subtle animations of a website can make the difference ([link1](https://www.uxpin.com/studio/blog/popular-web-animation-techniques-designers/), [link2](https://m2.material.io/design/motion/understanding-motion.html#principles))
6. How can I use vector graphics (`svg`) for the web (and apply CSS)? (3)
    - What are SVGs? What are the [advantages](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Adding_vector_graphics_to_the_Web) (e.g. scalability / accessability)?
    - How to style SVG's with CSS? (starter [link ](https://css-tricks.com/svg-properties-and-css/)
    - Showcase design elements like e.g. [blobmaker](https://www.blobmaker.app/) and [geometrize](https://www.samcodes.co.uk/project/geometrize-haxe-web/)
    - Mention SVG-based technologies like [vivus.js](https://maxwellito.github.io/vivus/), [d3.js](https://d3js.org/)

---
## Further topics (easier, maybe for one person each)
- What does `inherit`, `initial` and `unset` for all attributes do? How is it useful?
- How to work with fonts? `font-family` and web fonts (how to use Google Fonts?)
- Explain the more exotic universal-selector `*` and attribut-selectors. What are some use-cases?
- What can you do with `text-decoration` and `text-transform`?
- What can you do with borders? Including `border-style`, `border-radius` and more?
- `font-style`, `font-kerning`, `font-stretch`
- Transform
- `list-style-type` and `list-style-image`
- Sibling-combinators `+` `~`
- values with `calc()`
- Handling overflow (also inline vs block?)

## Own explanations
- ⚒️: Pseudo-Class vs Pseudo-Element?
```plaintext
- Pseudo-classes (:) are primarily used to style an element that's under various states. When referring to state, this includes the condition or user behavior, for example hover, active, focus, or disabled. States generally involve user interaction.
- Pseudo-elements (::) are used to style specified parts of an element. They can be used to target the first letter or first line. Or they can be used to insert content before or after the element.
```