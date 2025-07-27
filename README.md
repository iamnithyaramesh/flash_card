# Flash Card Game
An interactive quiz-style flashcard web game for testing knowledge on GST (Goods and Services Tax) through randomized question-reward cards. This tool was conceptualized and developed as part of the 20th Batch of Induction Course for Inspectors of GST, NACIN Chennai.

## Overview
This browser-based flashcard game challenges users with GST-related questions assigned to randomized reward values. Inspired by classroom games and gamified learning tools, it provides:

- Dynamic card flipping and randomized questions

- Timed answer reveal with animated countdown

- Points system with various reward levels

- Visually rich and responsive UI


##  Features
- 36 clickable flashcards with randomized points (e.g., 50, 250, Double-200, Pass-200)

- Timed modal that reveals a GST question with countdown and SVG clock animation

- "Show Answer" button and automatic reveal when time expires

- Responsive for mobile view (smaller cards)

- Final modal auto-closes when all cards are answered

- Thematic visuals for card types using gradients and classes (bonus, pass, etc.)

## How to Use
Open in Browser
Simply double-click index.html or open it in any modern web browser.

- Flip a Card : Click once to reveal the points on the back.

- Start Question : Click the same card again to trigger the question modal with timer and answer options.

- Answer & Learn: You can reveal the answer early or wait for the timer to expire.

### Scoring System

50 Pts – Basic recall

100 Pts – Moderate complexity

250 Pts – Application-based questions

500 Pts – Advanced and critical thinking

Double-200 – Bonus with higher stakes

Pass-200 – Skip question but retain some points

## Customization Tips

To add or modify questions, edit the qaList array in the <script> tag inside index.html.

To change the number of cards, update the values array accordingly and match it with new or repeated qaList entries.

Adjust styles inside <style> for themes, colors, or animations.
