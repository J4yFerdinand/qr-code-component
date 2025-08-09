# Frontend Mentor - Solution to the “QR Code Component” Challenge

![QR component preview](./preview.jpg)

## Table of Contents

  --[Description](#description)
  --[The challenge](#the-challenge)
  --[Screenshot](#screen-capture)
  --[Links](#links)
  --[Built-with](#built-with)
  --[What-I-learned](#what-I-learned)
  --[Next steps](#next-steps)
  --[Author](#author)
  --[Acknowledgements](#acknowledgements)

---

## Description

### The challenge

Create a screen-centric component that displays a QR code and short descriptive text, replicating as closely as possible the design provided by Frontend Mentor.

### Screenshot

![Screenshot of solution](./preview.jpg)

### Links

- Solution URL: _[Click here](https://github.com/J4yFerdinand/qr-code-component)_

### Built with

- **HTML5 semantic**
- CSS3** (custom properties, animations and transitions)
- Flexbox** for layout alignment and distribution
- _mobile-first_** flow

### What I learned

1. Basic animations with `@keyframes` to achieve a smooth input of the elements.
2. Use of CSS variables (`:root { --color: value; }`) to maintain a consistent palette and facilitate future changes.
3. How to structure reusable components with simple classes and keep CSS code clean.

````css
@keyframes upToCenter {
 0% { transform: translateY(-500px); }
 100% { transform: translateY(0); }
}
@keyframes leftToCenter {
  0% {
    transform: translateX(-500px);
  }
  100% {
    transform: translateX(0);
  }
}
@keyframes rightToCenter {
  0% {
    transform: translateX(500px);
  }
  100% {
    transform: translateX(0);
  }
````

### Next steps

- Add `:hover`/`:focus` accessible states.
- Test the use of **CSS Grid** to compare with Flexbox based solution.
- Implement performance and accessibility testing (Lighthouse).

## Author

- Portfolio: [Click here](https://github.com/J4yFerdinand)

## Acknowledgements

To the Frontend Mentor community for the free challenges and to all the people who provide constructive feedback.
