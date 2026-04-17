# HNG Stage 1B – Profile Card

This is a responsive and accessible Profile Card built as part of the HNG Internship Stage 1B task.

##  Live Demo
https://your-profile-card-vercel-link-here

##  Features
- Displays user avatar, name, and biography
- Shows current time in milliseconds using `Date.now()`
- Social media links (Twitter, GitHub, LinkedIn)
- Lists hobbies and dislikes
- Fully responsive layout (mobile, tablet, desktop)
- Semantic HTML with accessibility best practices
- Keyboard-friendly navigation for links

##  Tech Stack
- HTML5
- CSS3 (Flexbox & Grid)
- Vanilla JavaScript

##  How it works
- The time updates every second using `setInterval().`
- `Date.now()` is used to display the current epoch time in milliseconds
- Social links open in new tabs using `target="_blank"` and `rel="noopener noreferrer"`

##  Accessibility Notes
- Image includes meaningful `alt` text
- Semantic elements like `<article>`, `<header>`, `<nav>`, `<section>` are used
- Links are keyboard accessible with visible focus states
- Color contrast is maintained for readability

##  How to Run Locally
```bash
git clone https://github.com/Husinat/HNG-Stage-1B-Profile-Card
cd HNG-Stage-1B-Profile-Card
Then open:

Double-click index.html
OR
Use the VS Code Live Server extension


## Known Limitations
Time resets on page refresh (no backend persistence)
Avatar uses a static image path in this version
No user interaction or editing features yet
