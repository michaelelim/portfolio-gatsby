---
title: "Portfolio"
date: "2020-09-17"
author: "Michael Lim"
path: "/portfolio"
---

## You Don't Know Diddly Squat
**https://michaelelim-capstone-4p.netlify.app/**

You Don't Know Diddly Squat is an online multiplayer quiz game.
As a life-long gaming enthusiast, a game would be an enjoyable way to hone my skills. 
Multiplayer online gaming can bring fun and enjoyment.
Connect us with many people, including family, friends, and fellow gamers.
As a parent, I wanted to have a gave that could be played by the whole family.
Finally, I wanted to have a game that you could play during zoom calls.

Using the following tech:
- HTML
- CSS
- SASS
- Javascript
- React.JS
- Node.JS
- Express
- Websockets
- Socket.IO
- Trivia API
- Git
- Netlify
- Heroku

`youtube: trd6syJrSp0`

### Header 3

Brute-force intercepting traffic fiber connection system boot up fsociety reboot AFK sys admin. Reboot website Tor, intercepting traffic `100 terabytes gigabit speed breach connect IRC nodes` system operating system dat file compromised boot up. Data center decrypt password network disconnect. Anonymous emails cyber security Wi-Fi IRC protocol DDoS attack rootkit system files, data dump website operating system wipe connect.

- Anonymous boot up website AFK.
  - Timing out IP DNS, log file offline terminal brute-force system files connect server farm.
  - Reboot sys admin worm log file wipe.

```css
/* PostCSS code by PrismJS */

pre {
  background: #1a1a1d;
  padding: 20px;
  border-radius: 8px;
  font-size: 1rem;
  overflow: auto;

  @media (--phone) {
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  code {
    background: none !important;
    color: #ccc;
    padding: 0;
    font-size: inherit;

    .dark-theme & {
      color: inherit;
    }
  }
}
```

```js
// JS code by PrismJS

const menuTrigger = document.querySelector('.menu-trigger')
const menu = document.querySelector('.menu')
const mobileQuery = getComputedStyle(document.body).getPropertyValue('--phoneWidth')
const isMobile = () => window.matchMedia(mobileQuery).matches
const isMobileMenu = () => {
  menuTrigger.classList.toggle('hidden', !isMobile())
  menu.classList.toggle('hidden', isMobile())
}

isMobileMenu()

menuTrigger.addEventListener('click', () => menu.classList.toggle('hidden'))

window.addEventListener('resize', isMobileMenu)
```

```html
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
```