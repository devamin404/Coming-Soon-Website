# 🚀 Coming Soon Page

A stylish **"Coming Soon"** countdown page with a live timer, animated rocket, and a clean dark background — built with HTML, CSS, and vanilla JavaScript.

## ✨ Features

- ✅ Live countdown to a specific launch date
- ✅ Shows Days, Hours, Minutes, and Seconds
- ✅ Rocket fly-up animation (CSS keyframes)
- ✅ Resets to `00` when countdown reaches zero
- ✅ Clean, minimal dark-themed design
- ✅ No libraries or frameworks — pure HTML, CSS, JS

## ⏳ How The Countdown Works

1. A target launch date is set in script.js
2. Every second, the current time is compared to that date
3. The difference is broken down into Days, Hours, Minutes, Seconds
4. Those values are updated live on the screen
5. When the timer hits zero — it stops and shows 00:00:00:00

To change the launch date, update this line in `script.js`:

In javascript:
const countDownDate = new Date("Nov 05, 2026 00:00:00").getTime();
// ↑ Change this date to your own

## 🚀 Rocket Animation

The rocket uses a CSS animation that makes it fly from the bottom of the screen to the top, then loops infinitely:
