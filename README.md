# Deal or No Deal? 🎮
### A Classroom Dilemma Game for English Teachers

A self-contained, single-file web app designed for online and in-person English classes for advanced levels. Display it on a shared screen (e.g. via Jitsi screenshare) or use it in your classroom and let your students wrestle with tempting deals that always come with a catch.

<img src="https://github.com/user-attachments/assets/94859ab1-5e28-443e-abe8-bc2fe5ac7144" alt="deal-or-no-deal_logo_II" width="762" height="auto" />   

---

## How It Works

Each round presents students with a tempting offer — followed by a **BUT...**

> *You will never have to work again.*
> **BUT...: You can only leave your house once a week.**

Students decide: **Press it** (take the deal) or **No, I'll pass**.

After the decision, a stats screen reveals how a **fictional** pool of hundreds of thousands of people voted — sparking discussion, debate, and a lot of laughter.

<img width="762" height="878" alt="How to play" src="https://github.com/user-attachments/assets/5b650492-a79c-4f32-8604-e06dbc69f73c" />

---

## Features

- 25 pre built-in B2-level dilemmas, you can change / delete or add your own
- Green/red button design that makes the choice feel real
- Animated **fake** stats screen with percentage bars and a cheeky summary sentence
- Highlights the student's own choice on the stats screen
- Full question editor: add, edit, or delete any dilemma
- JSON export and import for sharing custom question sets between teachers
- Reset to defaults at any time
- Progress bar tracking across all questions
- Fully self-contained: fonts and logo are embedded, no internet required
- Works in any modern browser — just double-click the file

---

## How to Use

1. Download `deal-or-no-deal.html`. You only need the .html file to run the program!
2. Open it in any modern browser
3. Screenshare with your students or use it in class
4. Students call out their choice — press it or pass
5. Click the matching button to reveal the **fake** stats which the students can read out loud
6. Use the stats screen as a springboard for discussion
7. Hit **Next question** to continue

<img width="763" height="881" alt="How to use" src="https://github.com/user-attachments/assets/5dad2a1c-93c6-4945-b22f-7a83f7ec5f7e" />

## You can play the game online too! 

Go to https://xavierbit.github.io/deal-or-no-deal/deal-or-no-deal.html to play online. 
All functions are available as changes are stored only in the browser.

---

## Editing Questions

Click the **gear icon** in the top right to open the question editor. From there you can:

- Edit any existing dilemma
- Add new ones
- Delete questions you do not want
- Export your custom set as a `.json` file
- Import a set shared by another teacher
- Reset everything back to the 25 built-in defaults

Custom questions are saved in the browser's local storage and persist between sessions.

<img width="762" height="882" alt="Editing questions" src="https://github.com/user-attachments/assets/2b26f2a3-8429-4fbb-b9a2-8fef5f98f968" />

---

## Classroom Tips

- The pre-configured dilemmas work best at B2 and above, though strong B1 students can manage with support
- The "BUT..." structure is itself a useful grammar and discourse teaching point
- Encourage students to justify their choice before revealing the stats
- Use the stats mismatch ("you went against the grain") as a discussion prompt

---

## Technical Notes

- Single `.html` file, no dependencies, no server, no internet required after download
- Fonts (Outfit, Playfair Display) and logo are embedded as base64
- Custom questions stored in `localStorage` — tied to the browser and machine
- All data stored locally in the browser (no server, no login, no "phoning home")
- Use Export/Import to move question sets between machines or share with colleagues

---

## License

GNU General Public License v3.0 - https://www.gnu.org/licenses/gpl-3.0.en.html 

Copyright (C) 2025 Ivo Schmid / EASY Escola de Idiomas

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

---

## Part of the EASY Classroom Tools Suite

This game is part of a growing collection of interactive classroom tools developed for [EASY Escola de Idiomas](https://github.com/XavierBit).

***Made with ❤️ for the students of EASY Escola de Idiomas, Brazil.***
