# 💌 A Letter from God

A beautiful, interactive web experience where users receive a personalized love letter from God — presented through an animated envelope with romantic visual effects.

> **Live Demo:** Hosted via Firebase Hosting

---

## ✨ Features

### 📬 Interactive Envelope
- A realistic envelope with a **flap** and **pocket** crafted entirely in CSS
- Users enter their name and click **"Open"** to reveal a heartfelt letter
- The flap opens with a smooth 3D rotation, and the letter slides out and centers on screen

### ✍️ Typing Animation
- The letter content is revealed character by character with a natural typing effect
- **4 randomized messages** — each visit shows a different letter, keeping it fresh and personal

### 🌸 Flower Finale
- **10 seconds** after the letter finishes typing, it gently fades out
- A stunning **CSS-animated flower garden** blooms on screen — 3 flowers with stems, leaves, glowing firefly lights, grass, and foliage
- A **fluttering butterfly 🦋** appears alongside the flowers
- A beautiful quote is displayed:
  > *"Bunga di ladang saja Aku rawat, apalagi engkau..."*  
  > — Matius 6:28

### 💕 Romantic Effects
- **Floating hearts** — soft golden hearts drift upward in the background
- **Pulsing button** — the "Open" button gently pulses to invite interaction
- **Heart burst** — a burst of hearts explodes when the button is clicked
- **Background music** — plays a gentle loop of *"Jesus Loves Me"*

### 🎨 Design
- **Fonts:** *Indie Flower* (letter), *Playfair Display* (UI), *Great Vibes* (quote), *Cormorant Garamond* (base)
- **Color palette:** Deep crimson background with gold accents
- **Responsive:** Works beautifully on both desktop and mobile

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Structure & semantic markup |
| **CSS3** | All styling, animations, and visual effects (no libraries!) |
| **Vanilla JavaScript** | Interactivity, typing animation, and effects |
| **Firebase Hosting** | Deployment |

> 💡 **Zero dependencies** — this entire project is built with pure HTML, CSS, and JavaScript. No frameworks, no build tools.

---

## 📁 Project Structure

```
Valentine/
├── index.html                 # Main application (HTML + CSS + JS all-in-one)
├── backsound-jesuslovesme.mp3 # Background music audio file
├── firebase.json              # Firebase Hosting configuration
├── .firebaserc                # Firebase project settings
├── .gitignore                 # Git ignore rules
└── README.md                  # This file
```

---

## 🚀 Getting Started

### Run Locally
Simply open `index.html` in any modern browser:
```bash
# Option 1: Double-click index.html

# Option 2: Use a local server (recommended for audio)
npx serve .
```

### Deploy to Firebase
```bash
# Login to Firebase
firebase login

# Deploy
firebase deploy
```

---

## 📝 How It Works

1. **User lands on page** → sees the envelope with floating hearts in the background
2. **Enters their name** → types their name in the input field
3. **Clicks "Open"** → heart burst animation + envelope flap opens + letter slides up
4. **Letter centers** → fills the screen and begins the typing animation with a random message
5. **10 seconds after typing ends** → letter fades out gracefully
6. **Flower finale** → animated flowers bloom from the bottom, butterfly flutters, and the scripture quote appears

---

## 🙏 Credits

- **Flower CSS Animation** — Inspired by a CodePen CSS flower garden
- **Font Families** — [Google Fonts](https://fonts.google.com/)
- **Concept** — A Valentine's / appreciation letter from God, reminding the reader of their worth

---

## 📜 License

This project is open source and available for personal use. Feel free to fork and customize it for your own loved ones! 💖

---

*Made with ❤️ by [nowahgit](https://github.com/nowahgit)*
