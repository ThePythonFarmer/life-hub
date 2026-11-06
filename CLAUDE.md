# Life Hub: rules for every session

This repo is my personal projects hub. Follow these rules in every session, for every project.

## 1. How to talk to me

- I'm not a coder. Use plain English and no jargon. If a technical word can't be avoided, explain it in one short sentence.
- Tell me exactly what to tap or click next, one numbered step at a time, using the real button and menu names (for example: "Tap **Deploy** → **New deployment**").
- Assume I might be on my iPhone or iPad. Don't send me to steps that only work on a computer unless there's no other way, and say so if that's the case.
- When you finish, give a short plain-English summary: what you changed, why, and what I need to do now (if anything).
- If something fails or you skipped a step, say so honestly and simply.

## 2. Where I am

- I live in Cork, Ireland.
- Write in Irish/UK English spelling (colour, organise, programme, metre).
- Money is in euro (€). Write it as €12.50.
- Use metric units: km, kg, °C, litres.
- Show running and walking pace as minutes per km (for example 5:30 /km).
- Time zone is **Europe/Dublin**. Use it in code, Apps Script project settings, Sheets and Calendar events. Dates are day/month/year (06/11/2026) and times use the 24-hour clock (18:30).

## 3. The tools I use

- **Google for everything:** Gmail, Google Calendar, Google Drive and Google Sheets.
- **Todoist** is my task manager. When adding tasks, use the **Life** project unless I say otherwise.
- Build on these. Don't suggest new paid apps or services.

## 4. Free, and it works on all my devices

- Everything must be **free** to run. No paid plans, subscriptions, hosting fees or API keys that cost money.
- Everything must work on my **iPhone, iPad and Windows laptop**, in a normal web browser (Safari or Chrome). No installing software, no command line and no Mac-only or Android-only tools.

## 5. Privacy and safety (never break these)

- **Never put personal data in this repo.** No real names, addresses, phone numbers, emails, health details, finances or anything else about me or other people. Use made-up example data only.
- **My real data lives in Google Sheets**, in my own Google account, not here.
- **Never store passwords, card numbers, bank details (IBAN/BIC, account numbers) or PPS numbers anywhere**: not in this repo, not in Sheets, not in code, not in Apps Script properties. If a project seems to need one of these, stop and tell me instead.
- Don't paste links to my private Sheets or web apps into this repo. Keep those links in my own notes.

## 6. How to build things

### Apps that save data → Google Apps Script web app + Google Sheet
- Build it as a **Google Apps Script web app** with a **Google Sheet** behind it to store the data.
- Put the code in the project folder (for example `Code.gs` and `Index.html`) so I can copy it.
- Give me **step-by-step instructions** to:
  1. Create the Google Sheet (with the exact tab and column names).
  2. Open **Extensions → Apps Script**.
  3. Paste in each file.
  4. Set the time zone to Europe/Dublin.
  5. Deploy it as a web app (**Deploy → New deployment → Web app**, "Execute as: Me", "Who has access: Only myself").
  6. Approve the Google permission screens (and what "unsafe" warnings mean).
  7. Add the web app to my iPhone/iPad home screen (Safari → Share → **Add to Home Screen**).
- Also explain how to update it later (**Deploy → Manage deployments → Edit → New version**).
- Make it look good and easy to tap on a phone screen.

### Read-only dashboards → private artifact
- If something only **shows** information and doesn't need to save anything, publish it as a **private artifact** and give me the link.

## 7. How the repo is organised

- Every project gets its own folder inside `projects/`, for example `projects/running-log/`.
- Each project folder has a short `README.md` that explains in plain English:
  - what it does
  - how to set it up (the step-by-step guide)
  - how to use it day to day
  - what kind of app it is (Apps Script web app or artifact) and where the real data is kept
- When you add, rename or remove a project, update the project list in the main `README.md`.
