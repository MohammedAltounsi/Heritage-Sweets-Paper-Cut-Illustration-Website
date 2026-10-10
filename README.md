<div align="center">

**English** · [العربية](README.ar.md)

# Hijazi Taste website

<a href="https://hijazi-taste-preview.vercel.app"><img src="https://img.shields.io/badge/Live_preview-hijazi--taste--preview.vercel.app-820D13?style=for-the-badge" alt="Open the live preview"></a>

</div>

<img src="assets/showcase.jpg" width="100%" alt="The hero on desktop and on a phone: the Hijazi Taste logo and the Arabic headline on brand red, with a palm basket of dates in front of an old Jeddah skyline">

This is the website for Hijazi Taste (المذاق الحجازي), a sweets factory in Jeddah that makes Tamriati date pastries, maamoul, rahayef and other Hijazi sweets. The site is in Arabic, and an `EN` button in the menu switches it to English. It introduces the factory and its products to customers and to shops, hotels and companies that want to stock them. The site shows no prices. Every product button opens the company's online store.

As you scroll, a single date falls down the page through a series of paper-cut style scenes. They show how these sweets were made in old Jeddah homes, and then the factory where they are wrapped and packed today.

Designed and built by **Mohammed Altounsi** · [LinkedIn](https://www.linkedin.com/in/mohammed-altounsi/)

<img src="assets/tour.gif" width="100%" alt="Scrolling down the live preview: the date drops through the scenes from the palm basket to the tannour, then a car takes the baked piece to the factory, where it goes into the red Tamriati tub">

<sub>Recorded from the live preview using the "Watch the story" button, sped up about five times.</sub>

## What's on the site

One page, top to bottom:

- **Hero:** the logo, the headline, a button to the store and a "Watch the story" button that scrolls the page by itself and follows the date.
- **Our story:** the factory in Jeddah, its first step abroad in Bahrain, and Gulfood 2026 in Dubai.
- **Tamriati:** the main product line, in five kinds (white wheat, brown wheat, millet, chocolate and kleija).
- **Wrapped piece by piece:** each piece is sealed on its own, so a tub can be opened many times or a piece put in a school bag.
- **The family:** six product cards (Tamriati Special, Mamoulista, Rahayef, Tamriati Kleija, Homemade Maamoul and the packages), each linking to the store.
- **For trade and business:** shops, hotels, restaurants and companies can get in touch by WhatsApp or email.
- **Contact:** the store, WhatsApp, email, Instagram and TikTok.

## The paper-cut scenes

A scene sits above each section, seven in all: the basket, the stone, the filling, the dough, the shaping, the tannour, and the factory. The date lands in each scene and the scene works it one step further, until it becomes a baked Tamriati piece. Each scene has a short line of Arabic text under it. Six of the scenes are pictured here.

| | | |
|:-:|:-:|:-:|
| <img src="assets/scenes/basket.jpg" width="280" alt="A palm-frond basket full of dates"> | <img src="assets/scenes/stone.jpg" width="280" alt="Two hands opening a date over a wooden bowl, with stones on a saucer"> | <img src="assets/scenes/dough.jpg" width="280" alt="A bowl of dough on a low table, with a flour sack and stalks of wheat"> |
| Dates in a palm-frond basket | The stones taken out by hand | Dough mixed in a bowl |
| <img src="assets/scenes/shaping.jpg" width="280" alt="The dough rolled round the filling on a wooden board, with a wooden stamp beside it"> | <img src="assets/scenes/tannour.jpg" width="280" alt="A clay tannour oven with embers, and a car waiting beside it"> | <img src="assets/scenes/factory.jpg" width="280" alt="A wrapped piece on a factory conveyor dropping into the red Tamriati tub"> |
| Shaped on a board with a wooden stamp | Baked in the tannour | Wrapped at the factory and dropped into the tub |

A pause button in the corner stops all motion. With reduced motion turned on in the system settings, each scene shows its finished state and nothing moves.

## How it's built

- Plain HTML, CSS and JavaScript, with no framework and no build step.
- The scenes are SVG drawings. JavaScript moves their parts and the falling date as you scroll, and the date lands on the edges of the cards and images on its way down.
- All the text is kept in one file in Arabic and English, and the Cairo font is hosted with the site.

---

> This repo shows the design and front end of the site. The source code is private. If you want a website like this, message me on [LinkedIn](https://www.linkedin.com/in/mohammed-altounsi/).
