# 🎂 Romantic Interactive Birthday Celebration Web App

A modern, responsive, mobile-first interactive Birthday Celebration Web App built with **React**, **Tailwind CSS**, **Framer Motion**, **Canvas-Confetti**, and **Web Audio API**.

---

## ✨ Features & Interactive Stages

1. **Slide 1: The QR / Heart Gate ("Tap to Open")**
   - 3D-styled glowing heart with mock QR code badge and recipient name greeting.
   - Pulsating heartbeat animation with sparkle particle explosion upon unlocking.

2. **Slide 2: Cute Characters & The Runaway Trick Question**
   - Animated cute plush/panda characters holding a birthday cake with flickering candle.
   - Floating confetti rain.
   - Highlighted **"YES! 😍"** button & a playful runaway **"No 🙈"** button that hops away whenever hovered or tapped with funny messages!

3. **Slide 3: Interactive Balloon Pop ("Pop all 4 balloons")**
   - Realistic pastel balloons (Sky Blue, Soft Pink, Mint Green, Lavender) with specular highlights.
   - Live counter: "0/4 Popped" -> "4/4 Popped".
   - Tapping balloons pops them with sound effects and realistic fragment particles, revealing hidden words: **"You"**, **"Are"**, **"So"**, **"Special ❤️"**.

4. **Slide 4: Cake & Candle Blow (Mic or Tap Interaction)**
   - Dual interaction: **"Blow into the mic 🎙️"** (Web Audio API detects breath/puff threshold) or tap the flame.
   - Flame extinguishes with realistic rising smoke wisps.
   - Screen dims into a magical twilight night glow with twinkling stars.
   - *"Close your eyes & make a wish... ✨"* leading to the next stage.

5. **Slide 5: Rose Bouquet & Compliment Bubbles**
   - 3D-styled red rose bouquet with satin ribbon and craft wrap.
   - Stylized blooming cherry blossom trees at bottom corners.
   - Floating compliment tags with heart pulses on tap unlocking the personal letter.

6. **Slide 6: Sealed Heart Envelope & Typewriter Letter**
   - Sealed envelope with a golden heart wax seal.
   - Parchment paper letter with emotional typewriter effect typing the custom letter.

7. **Slide 7: Surprise Gift Box & Grand Finale**
   - 3-tap unboxing interaction on animated gift box with golden bow.
   - Pop-out celebration modal with cute characters (Brown & Cony style) holding a birthday cake.
   - Full-screen multi-color confetti explosion (`canvas-confetti`).
   - **"Replay Celebration 🔄"** and **"Download / Share Wish 💌"** options.

---

## 🛠️ Quick Customization

You can customize the recipient's name, your name, and the letter in two easy ways:

### Method 1: In `src/config.js` or `src/App.jsx`
Edit the top variables:
```javascript
export const RECIPIENT_NAME = "Shabinu B L";
export const SENDER_NAME = "Kishore";
export const CUSTOM_LETTER = `Dear {recipientName}, ...`;
```

### Method 2: In the Browser
Click the **"Customize"** pill in the top-left corner of the web app to edit the names and letter dynamically!

---

## 🚀 Running the App Locally

```bash
# Install dependencies (if not already installed)
npm install

# Start Vite development server
npm run dev

# Build for production
npm run build
```
