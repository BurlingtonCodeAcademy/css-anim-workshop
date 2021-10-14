# CSS Animations Workshop

## Purpose

This workshop is designed to introduce the following topics to students with NO CSS experience:

* File structure organization.
* "Fluid"/"liquid" design that reduces media query reliance.
* Font importation.
* Semantic divs, use case of "class" versus "id"
* Responsive CSS units.
* Pseudo-classes.
* CSS animations.

## Lesson Guide

### File structure organization:
1. Using command line terminal, mkdir css-anim, cd css-anim, mkdir index and mkdir css.
1. cd css, touch style.css
1. cd index, touch index.html

### "Fluid"/"liquid" design:
1. Demo complete workshop, model by resizing window how responsive all elements are to change, discuss what fluid design means, etc, discuss why excessive media queries create "brittle" CSS.

### Set-Up:
1. HTML boilerplate
1. Import font
1. Create all divs, mention semantic divs, mention use case for "class" versus "id" (we could target all animated divs by class, but for the purpose of this workshop, we can elect to target all divs-- except one)

### CSS:
**CSS style sheet is organized base layer working up, so code-along with students from top to bottom and explain the following as you go along:**
1. Explain :not
1. Discuss different CSS units, how px is absolute and r/em, %, vh/vw are responsive
1. Discuss transition and transition-property

 #### Animation
1. Explain @keyframes and 0% to 100% "steps"
1. Discuss various transforms
1. Discuss border-radius purpose in "creating" a circle
1. Discuss various animation properties and their purpose
1. Discuss what the cubic-bezier easing function is
1. Discuss the media query, why we might choose to have the title go onto multiple lines and remove the hover effect
