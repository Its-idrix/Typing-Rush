# ⚡ Typing Rush

A minimalist, high-performance web-based typing speed application inspired by Monkeytype. Built entirely using native web fundamentals (**HTML5**, **CSS3 variables**, and **Vanilla JavaScript**), it delivers sub-millisecond tracking precision while remaining completely framework-free.

---

## 🚀 Live Preview & Features

- **Adaptive Difficulty Architectures:** Three unique phrasing profiles (`Easy`, `Medium`, and `Hard`) customized by string length, casing rules, and punctuation weight variations.
- **Dynamic Accuracy Tracking:** Real-time character evaluation highlighting correct entries in natural white and wrong keys in rich contrast crimson with local padding warnings.
- **High-Precision Metric Engine:** Leverages the high-frequency browser Performance API (`performance.now()`) for exact WPM (Words Per Minute), precision error counts, and accuracy calculations.
- **Persistent Personal Records:** High scores are committed directly to individual difficulty rows via browser `localStorage` to display personal bests even across full reboots.
- **Fully Responsive & Fluid UX:** Designed from scratch using a system layout breakpoint system matching desktop, tablet, and mobile (Mac/Safari, Windows, iOS, Android) viewpoints cleanly.

---
---





## 📁 Project Architecture

The deployment architecture is fully self-contained inside a cross-browser secure structure:

```text
📁 typing-rush/
   └── 📄 index.html      # Standard Layout structure, style configurations, and game engine.


demo link : https://monkeylike.netlify.app


                                    Prompts


prompt N°1 - tool : Gemini 
prompt: "I want you to build me a TypeRush game a "monkey type" like with only HTML CSS and Vanilla JS don't use any other framework.  for the features : The texts  should be  taken randomly from a library of at least 5 texts each one should between   30 and 120 characters , it should be easy for the user to track his position  when he's typing (Green when he type good , red if he typed wrong ) , it also should have a timer that starts at the first keystroke and stop when the text is finished , the web app should also track the speed of the user typing with precision and give the stats at the end of each round "

prompt N°2 - tool : Gemini
Prompt : "ok it works now can you make it responsive  with 3 levels difficulty and save the best score and show it permanently on the page with auto update ? "

prompt N°3 - tool : Gemini
Prompt: "ok everything works nicely can you improve the UI/UX to make it more intuitive?"

prompt N°4 - tool : Gemini
prompt: "Nice now just add the title of the game and name it Typing rush on the top "