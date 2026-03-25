# Platform Wiring Guide

How to set up and connect all platforms for the Nakhla program. All tools are free tier.

---

## Platform Overview

| Purpose | Tool | Why | Free Tier |
|---------|------|-----|-----------|
| LMS / Assignments | Google Classroom | Universal, already deployed | ✅ Free |
| Video + Breakouts | Google Meet | Built into Classroom | ✅ Free |
| Simple backup video | Whereby | Permanent links, no account needed | ✅ Free (100 participants) |
| Quiz / Engagement | Wooclap | Multilingual, calm UX, browser-only | ✅ Free |
| Structured debate | Kialo Edu | Visual argument trees, educator accounts | ✅ Free |
| Visual sharing board | Padlet | Student portfolio + discussion, no login needed | ✅ Free (3 boards) |
| Translation tool | tools/translate.html (DeepL) | Custom, offline-capable | ✅ Free API tier |
| Translation fallback | Google Translate widget | Zero setup, embed in any page | ✅ Free |
| Live captions | Google Meet captions | Built in, auto-translate | ✅ Free |
| Parent comms | WhatsApp group | Both countries native | ✅ Free |

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
5. Share screen for Wooclap quiz / Padlet activity
6. Wrap up in main room

### Live Captions
- Enable Google Meet captions for automatic transcription during sessions
- Captions support auto-translate — helpful for multilingual groups
- No additional setup required; built into Google Meet

### Technical Requirements
- Stable internet (recommend wired connection for teachers)
- Camera on (encouraged, not required for kids)
- Microphone: push-to-talk recommended for large group; open mic in breakouts

---

## 3. Whereby (Backup Video)

Simple browser-based video calling — use as backup if Google Meet has issues.

### Setup
1. Create a free account at whereby.com
2. Create a permanent room: **"nakhla-exchange"**
3. Share the room link with co-teacher as backup

### Why Whereby
- Permanent room links — no scheduling needed
- Works in browser, no app install required
- Free tier supports up to 100 participants
- Simpler interface than Zoom — better for kids
- No student accounts needed

### When to Use
- Google Meet is down or unreachable for some students
- Partner school can't access Google Workspace
- Quick ad-hoc meetings between sessions

---

## 4. Wooclap (Quiz / Engagement)

Replaces Kahoot — calmer UX, multilingual, no app install needed.

### Setup
1. Create a free account at wooclap.com
2. Create one event per session using the questions from `kahoot-questions.json` in each content pack
3. Settings for each quiz:
   - **Question type:** Quiz (multiple choice)
   - **Timer:** 30 seconds per question
   - **Show ranking:** OFF (trauma-aware — no competitive pressure)
   - **Allow anonymous participation:** ON

### Running Wooclap in Session
1. Teacher opens Wooclap event on their screen, shares via Google Meet screen share
2. Students join on their devices via wooclap.com + event code (displayed on screen)
3. Questions display in English; answer options include Hebrew and Arabic text
4. After each question, teacher reads answers aloud in all 3 languages
5. At the end, celebrate participation (not scores)

### Additional Wooclap Features
- **Word Cloud:** Ask "What's one word that describes today?" — responses appear as a live word cloud (great for warm-ups and wrap-ups)
- **Open Question:** Students type responses that the teacher can display and discuss
- **Polling:** Quick yes/no or multiple choice polls during sessions

### Why Wooclap Over Kahoot
- No app install — works entirely in browser
- Calmer interface — less frenetic, better for 8–12 year olds
- Built-in multilingual support
- Word clouds and polls in addition to quizzes
- No student accounts needed

### Importing Questions
- The `kahoot-questions.json` files contain quiz questions formatted for import
- In Wooclap: Create event → Add questions → use Quiz type
- Copy question text and answer options from the JSON file
- Mark the correct answer for each question

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

## 6. Padlet (Visual Sharing Board + Portfolio)

Replaces Google Jamboard (discontinued Nov 2024) and Google Sites. Padlet serves as both the collaborative activity board during sessions and the student portfolio.

### Setup
1. Create a free account at padlet.com (free tier allows 3 boards)
2. Create one Padlet board per session:
   - **Session 1:** "Nakhla — Hello Cards" (Wall layout)
   - **Session 2:** "Nakhla — Our World" (Grid layout)
   - **Session 3:** "Nakhla — Friendship Postcards" (Wall layout)
3. Board settings:
   - **Content filtering:** ON (auto-filters inappropriate content)
   - **Require approval:** ON (teacher approves posts before visible)
   - **Allow reactions:** ON (hearts/stars)
   - **Attribution:** First name only
   - **Posting permissions:** "Can write" for anyone with link

### Using Padlet During Sessions
1. Teacher shares the Padlet link in Google Meet chat
2. Students open on their devices — no account needed
3. Students post text, images, drawings, or voice recordings
4. Teacher approves posts in real-time during the activity
5. Teacher screen-shares the Padlet for the full group to see

### Portfolio Use
- Each session's Padlet board becomes a gallery of student work
- Share board links with parents after sessions
- Teacher can download boards as PDF/image for archiving
- No separate portfolio tool needed — Padlet IS the portfolio

### Tips
- Free tier: 3 boards (one per session — perfect fit)
- Students can post voice recordings in their own language
- Use the "Remake" feature to create boards from a template
- Boards remain accessible after the program ends

---

## 7. WhatsApp

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
| After Session 3 | Thank you + portfolio links (Padlet) + certificate | Coordinator |

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

## 8. Translation Layer

### DeepL API (Primary)
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
- DeepL free tier has no Hebrew support as of 2025 — use Google Translate as fallback for Hebrew
- Arabic support is available
- For the content packs, translations are pre-prepared (no API needed during sessions)

### Google Translate Widget (Fallback)
If DeepL is unavailable or Hebrew translation is needed:
1. Go to translate.google.com — no account needed
2. Supports Hebrew, Arabic, and English with no character limits
3. For embedding in materials: use the Google Translate website directly
4. No API key required — zero setup

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
│       └──→ Screen share ──→ Wooclap / Padlet          │
│                                                       │
│  (Whereby available as backup if Meet fails)          │
└───────────────────────┬─────────────────────────────┘
                        │
┌───────────────────────▼─────────────────────────────┐
│                    AFTER SESSION                      │
│                                                       │
│  Google Classroom ──→ Collect reflections             │
│  Padlet ──→ Portfolio of approved student work        │
│  WhatsApp ──→ Send parent tip + Padlet link           │
│  Kialo Edu ──→ Continue async discussion              │
└─────────────────────────────────────────────────────┘
```
