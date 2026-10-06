*🙏 Hare Kṛṣṇa. All glories to Śrīla Prabhupāda.*

# 🪷 Daily Sadhana Card

A phone-friendly page for filling out a daily sadhana card and sending it as a neatly formatted WhatsApp message. 📱

🌐 **Live page:** https://gmpadmavakya.github.io/sadhana/

## ✨ Why

A daily sadhana report is the same short form every day. This page replaces the typing with taps and builds the message in a consistent format.

## 🌟 Features

- 🕐 **Round clock picker:** a 12-hour dial with AM/PM for bed, wake-up, and japa times.
- 🧘 **Smart defaults:** the japa start fills 30 min after wake-up, and the finish 2 hours after the start.
- ⏱️ **Quick buttons:** 15, 30, 45 min, 1 hr, 0 min, or type your own.
- 📊 **Auto calculations:** japa duration, rest duration, and japa score (shown on the page only).
- 👀 **Live preview:** aligned monospace card with an emoji on each row.
- 💬 **Send or copy:** "Send to Mentor" opens WhatsApp with the message ready.
- 💾 **Remembers entries** in your own browser.
- 📝 **Feedback button** that sends a note to the maintainer without exposing any email address.
- 🌗 **Light and dark mode.**

## ⭐ Japa score

| Finished | Points |
|---|---|
| 🌄 Before 7 AM | +5 |
| ☀️ Before noon | +4 |
| 🌤️ Before 4 PM | +3 |
| 🌇 Before 6 PM | +2 |
| 🌆 6 to 9 PM | 0 |
| 🌙 After 9 PM | -5 |

## 🚀 Using it

1. 📲 Open the live page on your phone and, optionally, add it to your home screen.
2. ✍️ Fill in the fields and check the preview.
3. 📤 Tap **Send to Mentor** and press send in WhatsApp.

To open a specific chat directly, enter the number with country code under **Settings** (for example `15551234567`).

## 🛠️ Built with

- 📄 A single `index.html` with plain HTML, CSS, and JavaScript. No build step.
- 🌍 Hosted on GitHub Pages.
- 🔧 Feedback goes through a small Google Apps Script that saves to a Google Sheet and emails the owner.
- ✏️ To customize, edit `build()` (message), `paintJapa()` (score), or `PRESETS` (buttons).

## 🔒 Privacy

Your entries and saved number stay in your browser. Nothing leaves it except the WhatsApp message you choose to send and any feedback you submit.
