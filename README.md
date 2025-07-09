# Ask SDM Chatbot Embed

This repository contains the JavaScript file used to embed the **Ask SDM Chatbot** on external pages. The script dynamically injects a branded chatbot UI (HTML + CSS + JS) after a short delay, with zero impact to site performance or analytics tracking (e.g., Olytics).

---

## 🚀 How It Works

After a 4-second delay, the script:

* Injects a fully styled chatbot interface
* Adds typewriter-style greeting animation
* Allows users to ask security & integration industry questions
* Redirects to the Ask SDM landing page with the user’s query

---

## ✅ How to Use

1. **Add a placeholder `div` where the chatbot should appear:**

```html
<div id="askSdmPlaceholder"></div>
```

2. **Add the script to your page:**

```html
<script src="https://subscriptionarchitect.github.io/ask-sdm-chatbot/ASK-SDM-CB-SCRIPT.JS" defer></script>
```

That’s it — the chatbot will appear 4 seconds after the page loads.

---

## 🧠 Why This Script?

* ✅ Fully self-contained (no external dependencies)
* ✅ Hosted via GitHub Pages with correct MIME type
* ✅ Safe for metered environments — does not block Olytics
* ✅ Mobile-friendly with responsive layout
* ✅ Custom branded for SDM Magazine + Napco

---

## 🔧 Options & Customization

Want to change how or when the chatbot loads?

* **Change the delay**: edit the `setTimeout(..., 4000)` line
* **Trigger on scroll instead**: replace the timeout with an IntersectionObserver
* **Only show once per session**: wrap in a `localStorage` check

Feel free to fork or open an issue for enhancements.

---

## 📄 License

MIT License © [SubscriptionArchitect](https://github.com/SubscriptionArchitect)
