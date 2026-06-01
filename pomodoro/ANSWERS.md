# ANSWERS.md

## 1. How to run

Open `index.html` in any modern browser — no build step, no dependencies.
Or serve it locally:

```bash
npx serve .
```

Then visit `http://localhost:3000`.

---

## 2. Stack & design choices

Why I used this stack

I used HTML, CSS, and JavaScript in a single file because this is a small project and does not need a complex framework like React or Vue. It keeps the project simple, easy to understand, and fast to run in any browser.
Design decision 1:Centered timer layout

I placed the timer in the center of the screen and gave it large size because:
This affects the main timer display section.

Design decision 2: Simple button layout (Start / Pause / Reset)
I used only 3 buttons instead of many controls 
This affects the control button section under the timer.

## 3. Responsive & Accessibility
     Responsive behavior
1) On 360px mobile screens:
Timer size becomes smaller
Buttons stack vertically
Padding is reduced so everything fits properly
2) On 1440px desktop screens:
Timer appears large and centered
Buttons are in a horizontal row
More spacing is used for better visual balance

This is handled using CSS

Accessibility consideration (what I handled)
Buttons are large and clearly labeled (Start, Pause, Reset)
Good color contrast between background and text
Easy to understand layout for all users

## 4. AI Usage
Where I used AI
I used AI to help structure the initial scenario of the Pomodoro Timer 
I used AI suggestions for JavaScript timer logic (start, pause, reset functions).
What AI gave me
Basic timer functions using setInterval
Simple centered UI layout with buttons

## 5. Honest gap

One part that is not fully polished is the UI animation and smooth transitions.

Right now:

Buttons change instantly
Timer updates are basic

If I had one more grip in coding, I would:

Add smooth animations for button clicks
Improve timer transitions (fade or scale effect)
Add a progress circle around the timer for better visualizatio
