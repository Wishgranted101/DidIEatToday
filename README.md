# DidIEatToday
Readme · MD
Copy

# 🐹 DidIEatToday? ft. Nibble

> A friendly AI companion app that makes sure you actually remember to eat today — no guilt, no calorie counting, just Nibble.

---

## What is this?

**DidIEatToday?** is a mobile app for people who get so locked into their day — work, hyperfocus, stress, life — that they look up at 4pm with a headache and realize they haven't eaten a single thing.

At the heart of the app is **Nibble**, a chubby, expressive AI-powered hamster who lives on your phone and is genuinely, dramatically, personally offended when you skip meals. Every day at your chosen time, Nibble bursts onto your screen and asks one simple question: *did you eat today?*

No food logging. No macro tracking. No diet plans. Just a tiny hamster who refuses to let you run on empty.

---

## This Repo

This repository contains the **waitlist landing page** for DidIEatToday? ft. Nibble, built ahead of the app's launch.

- **Deployed on:** Vercel
- **Email collection:** FormSpree
- **Stack:** Pure HTML, CSS, JavaScript (no frameworks — zero dependencies)

---

## Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/didieattodayapp.git
cd didieattodayapp
```

### 2. Configure FormSpree

1. Create a free account at [formspree.io](https://formspree.io)
2. Create a new form and copy your form ID
3. Open `index.html` and replace `YOUR_FORM_ID` with your actual ID:

```html

```

### 3. Add Nibble's images

Generate 6 mascot images (see prompts below) and place them in the root directory, then uncomment the `<img>` tags inside the `.mascot-grid` section of `index.html`:

| File name | Nibble's mood |
|---|---|
| `nibble-happy.png` | Happy, cheering |
| `nibble-worried.png` | Arms crossed, worried |
| `nibble-celebrating.png` | Celebrating with confetti |
| `nibble-sleeping.png` | Sleepy, ZZZs |
| `nibble-pointing.png` | Pointing accusingly |
| `nibble-sign.png` | Holding a tiny "EAT" sign |

### 4. Update your X handle

In `index.html`, find the footer and replace `yourhandle` with your X (Twitter) username:

```html
Wish
```

### 5. Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → Import your repository
3. Leave all settings as default → click **Deploy**

Vercel will auto-deploy on every push to `main`. That's it. ✅

---

## Generating Nibble with AI

Use the following prompts in **Google Gemini** (or any image generation tool) to create Nibble's 6 mascot angles:

1. *"Cute chubby cartoon hamster mascot, happy and cheering, holding a tiny fork, warm orange and cream color palette, thick outlines, transparent background"*
2. *"Same hamster, arms crossed, dramatically worried expression, thick brows, thick outlines, transparent background"*
3. *"Same hamster celebrating with confetti, big smile, puffed cheeks, transparent background"*
4. *"Same hamster sleepy and passed out, tiny ZZZs floating above, transparent background"*
5. *"Same hamster pointing at viewer accusingly, one eyebrow raised, transparent background"*
6. *"Same hamster holding a tiny sign that says EAT, jumping excitedly, transparent background"*

> 💡 Tip: Generate all 6 in the same Gemini session to keep Nibble's style consistent across images.

---

## Project Structure

```
/
├── index.html        # Landing page (single file, no build step)
├── nibble-*.png      # Nibble mascot images (you add these)
└── README.md         # You are here
```

---

## Roadmap

- [x] Waitlist landing page
- [ ] iOS app (React Native + Expo)
- [ ] Android app
- [ ] Nibble AI companion (OpenAI powered)
- [ ] Push notifications (Firebase)
- [ ] Alternative mascot skins
- [ ] Nibble voice mode (TTS/STT)

---

## Built With

- ❤️ and a concerning amount of skipped lunches
- [FormSpree](https://formspree.io) — email collection
- [Vercel](https://vercel.com) — hosting
- [Google Fonts](https://fonts.google.com) — Fredoka & Nunito

---

## Author

Built with ❤️ by [Wish](https://x.com/yourhandle)

---

## License

MIT — do whatever you want, just feed Nibble.
