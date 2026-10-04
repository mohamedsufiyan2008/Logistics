# Basics of Logistics Tutor

A simple quiz app for practising the Basics of Logistics question bank (B.Com Accounting and Finance). It runs in any web browser, works offline, and needs no installation.

## Features

- 246 questions across 5 units
- One question at a time, with options A to D
- Instant right or wrong marking, and the correct answer is shown
- Practise all units together or one unit at a time
- Running score during each session
- No repeated questions within a session
- Review the questions you missed at the end
- Reset the seen list to start fresh

## Units

| Unit | Theme | Questions |
|------|-------|-----------|
| 1 | Logistics basics | 48 |
| 2 | Supply chain | 50 |
| 3 | Transportation | 48 |
| 4 | Logistics activities | 50 |
| 5 | 3PL and forecasting | 50 |

Unit themes were inferred from the questions, so check them against your syllabus.

## How to use

1. Open `logistics-tutor.html` in a browser.
2. Pick "All units" or a single unit.
3. Tap an option to answer, then tap Next.
4. At the end, review your missed questions or return to the menu.

Your progress lives only in the open page. Refreshing the page resets the score and the seen list.

## Files

| File | Purpose |
|------|---------|
| `logistics-tutor.html` | The quiz app, with all questions built in |
| `logistics-tutor/question_bank.json` | The cleaned question data |
| `logistics-tutor/SKILL.md` | Skill for quizzing with Claude, with short explanations and memory tricks |

The web app shows the correct answer but has no explanations, because the source spreadsheet contains none. For explanations and memory tricks, use the skill with Claude.

## Data notes

- Question 140 had an answer key of "all of the above", but its option was cut off in the spreadsheet. The full text was restored.
- One option in the same question is also cut off in the spreadsheet and was left as is.
- Some questions are fill-in-the-blank, and some wording is rough in the original.

## Host on GitHub Pages

1. Create a new public repository.
2. Upload `logistics-tutor.html`. Rename it to `index.html` if you want a shorter link.
3. Go to Settings, then Pages. Choose the `main` branch and the `/ (root)` folder, then Save.
4. After a few minutes the app is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Source

Questions come from the college exam question file `B_COM__A_F__nme_logistics_23_10_24.xlsx` (Guru Nanak College, Autonomous, batch 2024, B.Com Accounting and Finance, Shift II). For personal study use.
