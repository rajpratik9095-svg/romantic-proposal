# 💌 Romantic Interactive Proposal Web App

A beautiful, interactive, and mobile-friendly romantic proposal web experience built using HTML, CSS, and Vanilla JavaScript. The app features immersive animations, dynamic music integration through the YouTube IFrame API, and an evasive "No" button for a guaranteed "Yes" outcome!

## ✨ Features

- **Multi-Stage Experience**: Progress through beautifully crafted screens: 
  1. Envelope Reveal
  2. Emotional Love Letter
  3. The Proposal ("Kya tum meri girlfriend banogi?")
  4. The Final Celebration
- **Interactive "No" Button**: The "No" button is programmed to actively evade the user's cursor/taps to ensure a 100% success rate on the proposal. 
- **Premium Aesthetics**: Features a dark, vibrant color scheme, glassmorphic cards (`backdrop-filter`), CSS particles, floating hearts, and micro-animations for an elegant and immersive feel.
- **Dynamic Background Music**: 
  - Background music starts automatically upon the first user interaction (bypassing browser autoplay policies).
  - Uses the YouTube IFrame API for music playback, maintaining smooth control over volumes.
- **Simultaneous Music Control**: When the "Yes" celebration button is clicked, the background music seamlessly pauses to make way for a special celebration song.
- **Fully Responsive**: Optimized for perfect usability across desktop, tablets, and specifically mobile viewing (max-height viewports and responsive typography).

## 🚀 How to Run Locally

You don't need any complex frameworks. This is a Vanilla website.

1. **Clone this repository** (or download it).
2. Use an extension like **Live Server** in VS Code, or start any local web server in the directory.
   - Example using Python: `python -m http.server 3000`
3. Open `http://localhost:3000/index.html` in your web browser.

## 🛠️ Technology Stack

- **HTML5**: Semantic layout.
- **CSS3**: Complex animations (`@keyframes`), Flexbox, CSS Variables, and Glassmorphism.
- **Vanilla JavaScript**: State flow, DOM manipulation, evasive button math calculation, and YouTube API controls.

## 💡 Customizing

You can easily customize this for your own proposal!
- **Changing the background music**: Search the JavaScript for `videoId: 'siw7-MTgE4s'` in `startBgMusic()` and replace it with your own YouTube video ID.
- **Changing the celebration song**: Search for `videoId: 'IFv6RnLCgYo'` inside `startYesSong()` and replace it as needed.
- **Updating the text**: Open `index.html` and modify the text in the `#sc2` (Letter) and `#sc3` (Proposal question) glass cards.

## 📱 Mobile Preview
It is recommended to share the live link on WhatsApp. The view is specifically tailored to fit native mobile screen heights gracefully without clipping.
live https://repositorypratik.free.nf/?i=1 
