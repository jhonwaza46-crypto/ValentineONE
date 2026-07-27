
<div align="center">

# 💕 For My Valentine
**"Normal gifts are boring — so I built this instead."**

An interactive Valentine's Day wish website built with love and code: a playful "Will you be mine?" proposal that doesn't make it easy to say no, a three-gift reveal, and a closing personal video message.

[![Live Demo](https://img.shields.io/badge/OPEN%20WEBSITE-Live%20Demo-E63950?style=for-the-badge)](https://valentine-one-three.vercel.app/)
[![Made With](https://img.shields.io/badge/Made%20With-love.js-FF6B81?style=for-the-badge)](https://valentine-one-three.vercel.app/)
[![No Backend](https://img.shields.io/badge/No%20Backend-Pure%20Frontend-8C1D2F?style=for-the-badge)](https://valentine-one-three.vercel.app/)
[![Type](https://img.shields.io/badge/Type-Valentine%20Wish%20Site-2E0F14?style=for-the-badge)](https://valentine-one-three.vercel.app/)
<div class="center-box">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</div>

</div>

---

## About

**For My Valentine** is a personal, interactive Valentine's Day website, a handcrafted alternative to flowers or chocolate that walks someone special through a charming, multi-step proposal experience.

Ambient music sets the mood from the moment the page loads. A playful "Will you be mine?" flow gently insists through a couple of "are you sure" screens before landing on "Happy Valentine's Day, Baby!", then reveals three personal gifts one at a time, and closes with a personal video message. Because sometimes the most romantic thing you can build is something made just for them.

> **Heads up:** this is a **self-contained front-end experience** meant to be personalized and re-deployed for someone specific. There's no backend and no database, you edit the names, messages, gifts, music, and video directly in the source files, then redeploy your own copy.

---

## Proposal Flow

```
Landing Screen         →  "Normal gifts are boring, so I built this instead"
    ↓
Proposal Screen        →  "Will you be mine? 🥺"  (Yes / No)
    ↓
Persistence Screens     →  The "No" path gently insists, twice
    ↓
Valentine Reveal          →  "Happy Valentine's Day, Baby! ♡"
    ↓
Gift Reveal Section         →  Three personal gifts, unveiled one by one
    ↓
Video Finale                  →  A personal closing video message
```

---

## Features

- **Ambient Music** — Background music plays automatically to set the mood
- **Interactive Proposal** — A playful "Will you be mine?" flow where "No" doesn't make for an easy exit
- **Gift Reveal Section** — Three personal gifts revealed one at a time
- **Personal Video Message** — A closing video, the final and most heartfelt surprise
- **Smooth Screen Transitions** — Elegant animations between every stage of the experience
- **Fully Responsive** — Looks good on both mobile and desktop
- **Custom Valentine Theming** — Warm reds and pinks with romantic typography throughout

---

## Built For

```
Purpose  → A one-off, personalized Valentine's Day gift website
Backend  → None — single-page front end, personalize and redeploy per recipient
Theme    → Romantic reds and pinks, playful and heartfelt
Status   → Complete template — swap in your own names, gifts, music, and video
Not For  → Multi-recipient or reusable "send to anyone" gift platforms
```

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 — animations, transitions, responsive layout |
| Logic | JavaScript (`love.js`) — screen flow and interactive proposal logic |
| Media | Background music (`music.mp3`), closing video (`assets/Valentine.mp4`) |
| Deployment | Vercel |

---

## Project Structure

```
ValentineONE/
├── index.html            Main page structure and all screen content
├── style.css             Styling, animations, Valentine theme
├── love.js                Interactive flow and proposal logic
├── music.mp3              Background music
└── assets/
    └── Valentine.mp4      Personal closing video message
```

---

## Make Your Own Version

1. Clone the repository:
   ```
   git clone https://github.com/Paim41/ValentineONE.git
   cd ValentineONE
   ```
2. Personalize the files for your recipient:

   | File | What to Change |
   |------|-----------------|
   | `index.html` | Names, messages, gift descriptions |
   | `love.js` | Flow logic, button behavior |
   | `style.css` | Colors, fonts, animations |
   | `music.mp3` | Replace with a song that means something to you both |
   | `assets/Valentine.mp4` | Replace with your own personal video |

3. Deploy for free on [Vercel](https://vercel.com):
   ```
   git add .
   git commit -m "💕 my valentine website is ready"
   git push origin main
   ```
4. Connect the repo to Vercel for automatic deployment, then share the link

---

## Customization Ideas

- Write a longer, more personal message on each screen
- Replace generic gift slots with real, meaningful surprises
- Add a photo gallery of shared memories before the video
- Change the color palette to their favorite colors
- Add a countdown to your next anniversary or special date

---

## Roadmap / Ideas

- [ ] Optional photo gallery step before the gift reveal
- [ ] Shareable link/QR generation like the other gift-page projects
- [ ] Additional theme presets beyond red/pink
- [ ] Configurable number of "persistence" screens

---

<div align="center">

*Sometimes the most romantic thing isn't what you buy — it's what you build.*

[valentine-one-three.vercel.app](https://valentine-one-three.vercel.app/)

</div>
