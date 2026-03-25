# Platform Wiring Guide

How to set up and connect all platforms for the Nakhla program. All tools are free tier.

---

## Platform Overview

| Platform | Role | Cost |
|----------|------|------|
| Google Classroom | Assignments, worksheets, async work | Free |
| Google Meet | Live sessions + breakout rooms | Free (Google Workspace for Education) |
| Google Sites | Student portfolio (replaces Seesaw) | Free |
| Kahoot | Trilingual quizzes | Free (basic plan) |
| Kialo Edu | Structured discussion (optional, Session 2–3) | Free |
| WhatsApp | Parent communication | Free |
| DeepL API | Translation layer | Free tier (500k chars/month) |

---

## 1. Google Classroom

### Setup
1. Create a Google Workspace for Education account (or use existing school account)
2. Create one Classroom per exchange cohort: **"Nakhla Exchange — [Cohort Name]"**
3. Add both Israeli and Emirati teachers as co-teachers
4. Invite all students via class code

### Structure
- **Topic per session:** "Session 1: Hello Neighbor", "Session 2: Our World", "Session 3: Friends Across the Shore"
- **Post types:**
  - **Material:** Vocab sheets (upload the .md files as Google Docs)
  - **Assignment:** Pre-session worksheet (complete before live session)
  - **Assignment:** Post-session reflection ("Write one thing you learned")
- **Stream settings:** Only teachers can post; students can comment

### Tips
- Upload vocab files as Google Docs (convert from Markdown)
- Use the "Schedule" feature to release materials 2 days before each session
- Create a shared Google Drive folder per cohort for moderator resources

---

## 2. Google Meet

### Setup
1. Create recurring meeting links (one per session date)
2. Enable breakout rooms (requires Google Workspace for Education)
3. Set up one breakout room per pod (2 Israeli + 2 Emirati kids)

### Breakout Room Configuration
- **Number of rooms:** Total students ÷ 4 (round up)
- **Assignment:** Manual — teacher pre-assigns students to pods
- **Timer:** Set to 25 minutes (pod pair block)
- **Allow participants to return to main room:** Yes

### Rotation Between Sessions
- Between Session 1 and 2: rotate half the Israeli kids to new pods
- Between Session 2 and 3: keep Session 2 pods (familiarity for final session)
- Document pod assignments in a shared spreadsheet

### During Session
1. Start in main room (Full Group block)
2. Open breakout rooms at 10:00 mark
3. Moderators float between rooms (join/leave as needed)
4. Close breakout rooms at 35:00 — automatic return to main room
5. Share screen for Kahoot/Jamboard activity
6. Wrap up in main room

### Technical Requirements
- Stable internet (recommend wired connection for teachers)
- Camera on (encouraged, not required for kids)
- Microphone: push-to-talk recommended for large group; open mic in breakouts

---

## 3. Google Sites (Student Portfolio)

Replaces Seesaw — free, teacher-moderated, no student accounts needed.

### Setup
1. Create one Google Site per class: **"Nakhla — [School Name] Portfolio"**
2. Add a page per student (teacher creates pages)
3. Set publishing to "Anyone with the link" (no sign-in required for viewing)
4. Only teachers can edit (students submit work via Classroom, teacher posts to Site)

### Structure
```
Home Page
├── About Nakhla
├── Session 1 Gallery
│   ├── [Student Name] — My Introduction
│   └── ...
├── Session 2 Gallery
│   ├── [Student Name] — My World
│   └── ...
├── Session 3 Gallery
│   ├── [Student Name] — Friendship Postcard
│   └── ...
└── Our Words (shared vocabulary wall)
```

### Moderation
- Students submit work via Google Classroom assignment
- Teacher reviews, then copies approved content to Google Sites
- No direct student access to edit the Site
- This ensures all published content is age-appropriate and reviewed

---

## 4. Kahoot

### Setup
1. Create a free Kahoot account at kahoot.com
2. Create one Kahoot per session using `kahoot-questions.json` from each content pack
3. Settings for each Kahoot:
   - **Game mode:** Classic (individual)
   - **Show scoreboard between questions:** OFF (trauma-aware — no competitive pressure)
   - **Timer:** 30 seconds per question
   - **Points:** OFF (or hidden from players)
   - **Music:** ON (gentle, not startling)

### Running Kahoot in Session
1. Teacher opens Kahoot on their screen, shares via Google Meet screen share
2. Students join on their devices via kahoot.it + game PIN
3. Questions display in English; answer options include Hebrew and Arabic text
4. After each question, teacher reads answers aloud in all 3 languages
5. At the end, celebrate participation (not scores)

### Creating Trilingual Questions
- Use the `kahoot-questions.json` file from each session's content pack
- Question text: English
- Answer options: mix of Hebrew, Arabic, and English
- Add images where possible (food, flags, landmarks)

---

## 5. Kialo Edu

### Setup
1. Create a free teacher account at kialo-edu.com
2. Create a discussion per session (optional — best suited for Session 2 and 3)
3. Add students via class link (no student accounts needed)

### Discussion Topics (Non-Political)
- Session 2: "What makes a food 'special' to a culture?"
- Session 3: "What's the best way to stay friends with someone far away?"

### Settings
- Teacher moderates all claims before they appear
- Keep tree depth shallow (max 2 levels for this age group)
- Provide sentence starters: "I think… because…", "I agree with… and also…"

### Notes
- Kialo is optional — use only if students are comfortable with written English
- Can be done asynchronously between sessions as homework
- Teacher should pre-populate 2–3 starter claims

---

## 6. WhatsApp

### Setup
1. Create one WhatsApp group per class: **"Nakhla Parents — [School Name]"**
2. Add all parents + both teachers + program coordinator
3. Set group settings: Only admins can send messages (to prevent spam)
4. Admins: teachers + coordinator

### Communication Schedule
| When | What | Who Sends |
|------|------|-----------|
| 1 week before Session 1 | Welcome message + program overview | Coordinator |
| 2 days before each session | Reminder + "ask your child about…" prompt | Teacher |
| After each session | Parent tip (from `parent-tip.md`) | Teacher |
| After Session 3 | Thank you + portfolio link + certificate | Coordinator |

### Message Templates
Messages should be trilingual. Use the DeepL translation tool (`tools/translate.html`) to prepare messages.

**Welcome Message Example:**
```
🌴 Welcome to Nakhla!

EN: Your child will be part of a cultural exchange with children from [country]. Over 3 sessions, they'll learn greetings, share their world, and make new friends.

עב: הילד/ה שלכם ישתתפ/ו בחילופי תרבות עם ילדים מ[מדינה]. במהלך 3 מפגשים, הם ילמדו ברכות, ישתפו את העולם שלהם, ויכירו חברים חדשים.

عر: سيشارك طفلكم في تبادل ثقافي مع أطفال من [بلد]. خلال ٣ جلسات، سيتعلمون التحيات، يشاركون عالمهم، ويكوّنون صداقات جديدة.
```

---

## 7. DeepL API (Translation Layer)

### Setup
1. Sign up for DeepL API Free at deepl.com/pro-api
2. Get your API key from the account settings
3. Open `tools/translate.html` in a browser
4. Enter your API key (stored in localStorage — never leaves your browser)

### Usage
- Use for preparing all parent communications
- Use for translating any ad-hoc content (discussion prompts, instructions)
- Free tier: 500,000 characters/month (sufficient for this program)

### Supported Language Codes
| Language | DeepL Code |
|----------|-----------|
| English | EN |
| Hebrew | HE |
| Arabic | AR |

### Limitations
- DeepL free tier has no Hebrew support as of 2025 — use Google Translate API as fallback for Hebrew
- Arabic support is available
- For the content packs, translations are pre-prepared (no API needed during sessions)

---

## Wiring Diagram

```
┌─────────────────────────────────────────────────────┐
│                    BEFORE SESSION                     │
│                                                       │
│  Google Classroom ──→ Distribute vocab + worksheets   │
│  WhatsApp ──→ Parent reminders                        │
│  DeepL/translate.html ──→ Prepare translations        │
│  Kialo Edu ──→ Post async discussion (optional)       │
└───────────────────────┬─────────────────────────────┘
                        │
┌───────────────────────▼─────────────────────────────┐
│                    DURING SESSION                     │
│                                                       │
│  Google Meet (main room) ──→ Full group + wrap-up     │
│       │                                               │
│       ├──→ Breakout rooms ──→ Pod pairs               │
│       │                                               │
│       └──→ Screen share ──→ Kahoot / Jamboard         │
└───────────────────────┬─────────────────────────────┘
                        │
┌───────────────────────▼─────────────────────────────┐
│                    AFTER SESSION                      │
│                                                       │
│  Google Classroom ──→ Collect reflections             │
│  Google Sites ──→ Publish approved student work       │
│  WhatsApp ──→ Send parent tip                         │
│  Kialo Edu ──→ Continue async discussion              │
└─────────────────────────────────────────────────────┘
```
