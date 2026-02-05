# 💘 Interactive Valentine Experience

A mobile-first, cinematic Valentine webpage built with pure HTML, CSS, and JavaScript.

Designed for touch interaction, emotional UX, and a memorable “Yes” moment.

---

## 🌐 What this is

An interactive page that asks:

**“Will you be my Valentine?”**

- The “No” button runs away
- The “Yes” button grows and follows your finger
- A full celebration triggers when Yes is pressed
- Reveal: “Mya ❤️ Moe”
- Redirects to a date invite page

Built as a shareable iMessage / social link.

---

## ✨ Features

### 📱 Mobile-first UX
- Touch-optimized interactions
- Finger-tracking Yes button
- Haptic vibration
- Accessibility support (keyboard + aria)

### 💖 Interaction Flow
1. User taps No → button runs away
2. “Are you sure?” prompts appear
3. Yes grows and becomes dominant
4. No disappears
5. User taps Yes → celebration begins

### 🎉 Celebration Mode
When Yes is pressed:

- Background music plays
- Camera flash animation
- Center confetti burst
- Floating hearts animation
- Animated reveal: **Mya ❤️ Moe**
- Typewriter confirmation text
- Redirect to invite page

---

## 🔁 Redirect Setup

Inside `index.html`, update this line:

```js
const DATE_URL = "https://example.com/date-invite";
