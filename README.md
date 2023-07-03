# Frontend Mentor - [Order summary component.](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Build out the project to the designs provided.
Your users should be able to:

- See hover states for interactive elements

### Screenshot

<details>

<summary>Click to open</summary>

![Desktop](https://i.imgur.com/UnRLl6Y.png)
![Mobile](https://i.imgur.com/bSjWMJn.png)

</details>

### Links

- Live Site URL: [Live](https://solracss.github.io/FrontendMentor-order-summary/)

## My process

### Built with

<div >
	<img width="30" src="https://user-images.githubusercontent.com/25181517/192108891-d86b6220-e232-423a-bf5f-90903e6887c3.png" alt="Visual Studio Code" title="Visual Studio Code"/>
	<img width="30" src="https://user-images.githubusercontent.com/25181517/192158954-f88b5814-d510-4564-b285-dff7d6400dad.png" alt="HTML" title="HTML"/>
	<img width="30" src="https://user-images.githubusercontent.com/25181517/192158956-48192682-23d5-4bfc-9dfb-6511ade346bc.png" alt="Sass" title="Sass"/>
	<img width="30" src="https://user-images.githubusercontent.com/25181517/183898674-75a4a1b1-f960-4ea9-abcb-637170a00a75.png" alt="CSS" title="CSS"/>
</div>

### What I learned

1. Working with pseudo element ` ::before`` to add  `svg` as background.

```css
.order-container::before {
	content: "";
	position: absolute;
	top: 0;
	left: 0;
	background: url("../images/illustration-hero.svg") no-repeat center;
	background-size: cover;
	width: 100%;
	height: rem(167px);
}
```

2. Keeping code as simple as possible and avoid unnecessary divs

```html
<div class="order-container">
	<h1 class="order-summary">Order Summary</h1>
	<p class="order-description">
		You can now listen to millions of songs, audiobooks, and podcasts on any device anywhere you like!
	</p>
</div>
```

does not need wrapper.
