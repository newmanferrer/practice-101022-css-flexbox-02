![css flexbox logo](./assets/images/css-flexbox-01.jpg)

# PRACTICE: CSS FLEXBOX BASIC 02

## Project description

Practice properties:

- justify content
- align items
- align content

<span style="color: #f7941f">Important note:</span> The "justify-items" property, does not apply for css flexbox.

### <span style="color: #995db5">1.- JUSTIFY CONTENT</span>

The justify-content property is a sub-property of the CSS Box Alignment Module. Aligns items along the "main axis".

justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right ... + safe | unsafe;

![css justify content image](./assets/images/justify-content-01.svg)

### <span style="color: #995db5">2.- ALIGN ITEMS</span>

The align-items property is a sub-property of the CSS Box Alignment Module. Aligns items along the "cross axis".

align-items: stretch | flex-start | flex-end | center | baseline | first baseline | last baseline | start | end | self-start | self-end + ... safe | unsafe;

<span style="color: #f7941f">Important note:</span> The wrap or wrap-reverse property must be applied. If the items jump (due to the wrap property) when overflowing the container, a space will be generated between the items.

![css align items image](./assets/images/align-items-01.svg)

### <span style="color: #995db5">3.- ALIGN CONTENT</span>

The align-content property is a sub-property of the CSS Box Alignment Module. Aligns items along the "cross axis". This aligns a flex container’s lines within when there is extra space in the cross-axis, similar to how justify-content aligns individual items within the main-axis.

align-content: flex-start | flex-end | center | space-between | space-around | space-evenly | stretch | start | end | baseline | first baseline | last baseline + ... safe | unsafe;

<span style="color: #f7941f">Important note:</span> The wrap or wrap-reverse property must be applied. If the items jump (due to the wrap property) when the container overflows, "NO" will generate a space between the items, the items behave as a block.

![css align content image](./assets/images/align-content-01.svg)

### <span style="color: #995db5">4.- PLACE CONTENT (Shorthand)</span>

Place Content is a shorthand for the align-content (cross axis) and justify-content (main axis). If only one value is provided, then it sets both properties.

place-content: start space-evenly;

## Used technology

- Html 5
- CSS

## Resources and documentation used

- CSS-TRICKS: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

## Developers: Requirements

- Web Browser
- Code editor

## Developers: Installtion

1. Clone the repository: https://github.com/newmanferrer/practice-101022-css-flexbox-02.git
2. Another option is to download the repository using ZIP format.

---

## Author: Newman Ferrer

newmanferrer@gmail.com

:sun_with_face: Maracaibo - Venezuela :venezuela:

Practice date: 10/10/2022
