## Intro to CSS: Foundations
- Jenn Georgevich (they/them)
- tweet @jenngeorge_
- email: jenn@vsco.co
- Slides, Demo, and Project: [github.com/jenngeorge/superposition-css](github.com/jenngeorge/superposition-css)
---

### Topics

- Intro to CSS & Chrome Devtools
- Specificity & Selectors
- Display
- Box Model
- Position
- Flex Box


---

### Specificity & Selectors
- Universal selectors ( * )

- Tag selectors (div, h1, body) and pseudo-elements (:after)

- Class selectors (.hidden, .my-class)

- ID selectors (#thing-one)

- Inline styles (<div style="width: 50px;" />)

Note: call out selector type during demo

---

##Display
- Block:
    - width and height
    - width takes up 100% of parent element
- Inline:
    - ~~width or height~~
    - as large as largest descendant
- Inline-block:
    - width and height
    - as large as largest descendant

Note: show nav section
---
Position: static (default)
---

## Position: relative
- Occupies space in the flow of the page.
- Positioned relative to its normal position.
    - this means you can reposition it by using left, top, etc.

Note: show this in a plant item

---
### Position: absolute

- Positioned with respect to its most recent non-statically positioned ancestor.
-  You can adjust their location on the page by using left, top, etc.

Note: add a bee  image on top of the hero section

---
## Position: fixed
- Positioned relative to the viewport.
    - the element stays in the same place in the viewport
- Fixed elements are taken out of flow (they take up no space in the page)
- You can adjust their location on the page by using left, top, etc.

Note: make the navbar fixed to top

---
##Box Model
![box-model](http://res.cloudinary.com/jenngeorge/image/upload/v1504753778/box-model_nvjdp7.png)

Note: show box model in chrome dev tools

---
## Flex Box
- The container alters items to best fill its space
- easy solution for

[css tricks guide to flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

---
### Additional Resources
[MDN CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
[CSS Tricks](https://css-tricks.com/)
[MDN Intro To HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
---
## Try it!

[github.com/jenngeorge/pawneehacks-css](github.com/jenngeorge/superposition-css)
