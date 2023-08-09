# Product cards
Replace `<your_account>` with your Github username and copy the links to Pull Request description:
- [DEMO LINK](https://HachevskyyMarkiyan.github.io/layout_product-cards/)
- [TEST REPORT LINK](https://HachevskyyMarkiyan.github.io/layout_product-cards/report/html_report/)

> Follow [this instruction](https://mate-academy.github.io/layout_task-guideline)
___

> Disable `Multiplayer Cursors` in figma to hide other cursors ([Learn how](https://mate-academy.github.io/layout_task-guideline/figma.html#multiplayer-cursors))
___

## ❗️❗️❗️ DON'T FORGET TO PROOFREAD YOUR CODE WITH [CHECKLIST](https://github.com/mate-academy/layout_product-cards/blob/master/checklist.md) BEFORE SENDING YOUR PULL REQUEST❗️❗️❗️

## The task

> ❗️❗️❗️ In order to use SCSS delete the `style.css` file and change the `<link>` in the `index.html` to:
```html
<link rel="stylesheet" href="./styles/index.scss">
```

Create a pages with product card using `flexbox` basing on [the mockup](https://www.figma.com/file/ojkArVazq7vsX0nbpn9CxZ/Moyo-%2F-Catalog-(ENG)?node-id=11325%3A2287).

### Requirements:
- Q reset browser's default margins
- Q card width is `200px` including border
- Q use images from [src/images](src/images)
- Q change link styles on `:hover`
- Q follow styles from the mock
- Q add `data-qa="card"` attribute to the card block
- Q add `data-qa="hover"` attribute to the link

--> [CHECKLIST](https://github.com/mate-academy/layout_product-cards/blob/master/checklist.md)

### Tips & Hints
- Q Add **ALL** `data-qa` attributes required in the task
- Q If you use SCSS, check `background-image: url()` to be relative to the `main.scss`. So should start with `../images`.
- Q Reuse `stars` block from [Stars task](https://github.com/mate-academy/layout_stars)
and keep it operational. If you change `stars--4` modifier to `stars--2` or
other - number of selected stars should change correctly.
- Q There should be only 2 BEM blocks in your code `card` and `stars` all the others are just card elements
- Q Item with the text `Buy` should be a link.
- Q Check font styles on the mockup. Use [google fonts](https://fonts.google.com/)

---
![screenshot](./references/card-example.png)

