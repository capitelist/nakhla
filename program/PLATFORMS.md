# Platform Wiring Guide

How to set up and connect all platforms for the Nakhla program. All tools are free tier.

---

## Platform Overview

| Purpose | Tool | Why | Free Tier |
|---------|------|-----|-----------|
| LMS / Assignments | Google Classroom | Universal, already deployed | ✅ Free |
| Quizzes / Engagement | Blooket | Game-based, fun for ages 8–12, browser-only | ✅ Free |
| Visual sharing board | Padlet | Student portfolio + discussion, no login needed | ✅ Free (3 boards) |
| Live video + breakouts | Zoom | Industry standard, Interpretation channels for multilingual | ✅ Free (40 min) |
| Async pen pals / video | Microsoft Flip | Moderated video messages, parent-visible, educator-free | ✅ Free |
| Cultural videos | YouTube unlisted playlists | No accounts needed to view, embed in Classroom | ✅ Free |
| Translation tool | tools/translate.html (DeepL) | Custom, offline-capable | ✅ Free API tier |
| Parent comms | WhatsApp group | Both countries native | ✅ Free |

---

## 1. Google Classroom

### Setup
1. Create a Google Workspace for Education account (or use existing school account)
2. Create **two** classrooms — one per country:
   - **"Nakhla — Israel Class"**
   - **"Nakhla — UAE Class"**
3. Add partner teacher as co-teacher in both classrooms
4. Share join codes with students in each country
5. Optionally create a third "combined" classroom for shared assignments

### Assignment Workflow
- **Topic per session:** "Session 1: Hello Neighbor", "Session 2: Our World", "Session 3: Friends Across the Shore"
- **Post types:**
  - **Material:** Vocab sheets (upload the .md files as Google Docs), YouTube playlist links, Padlet board links
  - **Assignment:** Pre-session worksheet (complete before live session)
  - **Assignment:** Post-session reflection ("Write one thing you learned")
  - **Assignment:** Microsoft Flip video prompt (link to Flip topic)
- **Stream settings:** Only teachers can post; students can comment

### Tips
- Upload vocab files as Google Docs (convert from Markdown)
- Use the "Schedule" feature to release materials 2 days before each session
- Embed YouTube playlist links and Padlet links directly in assignments
- Create a shared Google Drive folder per cohort for moderator resources

---

## 2. Blooket (Quiz / Engagement)

Game-based quiz platform — more engaging than traditional quizzes for ages 8–12.

### Setup
1. Create a free teacher account at blooket.com
2. Create one **Question Set** per session using the questions from `kahoot-questions.json` in each content pack
3. To import questions:
   - Go to **Create** → **Create a Set**
   - Title: "Nakhla Session 1: Hello, Neighbor!" (etc.)
   - Add questions manually from the JSON file — copy question text, answer options, and mark correct answers
   - Save the set

### Running Blooket in Session
1. From your dashboard, click the Question Set → **Host**
2. Choose a game mode:
   - **Gold Quest** — recommended for Nakhla (collaborative feel, less competitive)
   - **Tower Defense** — good alternative (strategy + knowledge)
   - Avoid **Battle Royale** or elimination modes (trauma-aware — no competitive pressure)
3. Students join at **play.blooket.com** + enter the Game ID displayed on screen
4. No student accounts needed — they enter a nickname only
5. Teacher shares screen via Zoom so everyone can see the game progress
6. After each question, teacher reads answers aloud in all 3 languages

### Why Blooket
- No app install — works entirely in browser
- Game-based format keeps 8–12 year olds engaged
- Multiple game modes — teacher controls the competitive level
- No student accounts needed
- Free tier allows unlimited games with up to 60 players

### Question Set Notes
- The `kahoot-questions.json` files contain all questions, answers, and correct flags
- Each session also has a `blooket-setup.md` with step-by-step instructions
- Questions include Hebrew and Arabic script with transliterations

---

## 3. Padlet (Visual Sharing Board + Portfolio)

Padlet serves as both the collaborative activity board during sessions and the student portfolio.

### Setup
1. Create a free account at padlet.com (free tier allows 3 boards)
2. Create one Padlet board per session:
   - **Session 1:** "Nakhla — Hello Cards" (Wall layout)
   - **Session 2:** "Nakhla — Our World" (Grid layout, 4 columns)
   - **Session 3:** "Nakhla — Friendship Postcards" (Wall layout)
3. Board settings:
   - **Content filtering:** ON (auto-filters inappropriate content)
   - **Require approval:** ON (teacher approves posts before visible — "Moderated" mode)
   - **Allow reactions:** ON (hearts/stars)
   - **Attribution:** First name only
   - **Posting permissions:** "Can write" for anyone with link
4. Share the Padlet link in Google Classroom under each session's Topic

### Using Padlet During Sessions
1. Teacher shares the Padlet link in Zoom chat
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

## 4. Zoom (Live Sessions + Interpretation)

### Setup
1. Create a free Zoom account (or use school account)
2. Schedule a **recurring meeting** for all 3 sessions
3. Enable **Interpretation** feature:
   - Go to **Settings** → **In Meeting (Advanced)** → **Language Interpretation** → Toggle ON
   - When scheduling the meeting, click **Interpretation** and add channels:
     - **Hebrew** (interpreter: Israeli teacher or bilingual moderator)
     - **Arabic** (interpreter: Emirati teacher or bilingual moderator)
     - **English** (default floor language)
4. Share the meeting link in both Google Classrooms

### Interpretation Channels — How It Works
1. During the meeting, interpreters join their assigned language channel
2. Interpreter hears the floor audio and speaks the translation into their channel
3. Students click the **Interpretation** globe icon in their Zoom toolbar
4. They select their preferred language channel to hear translation
5. Floor language (English) is always available as default
6. **Tip:** If you don't have live interpreters, students can use the English floor and help each other translate in breakouts

### Breakout Rooms
1. **Number of rooms:** Total students ÷ 4 (round up)
2. **Assignment:** Manual — teacher pre-assigns students to pods (2 Israeli + 2 Emirati per pod)
3. **Timer:** Set to 25 minutes (pod pair block)
4. **Allow participants to return to main room:** Yes
5. Moderators float between rooms (join/leave as needed)

### Rotation Between Sessions
- Between Session 1 and 2: rotate half the Israeli kids to new pods
- Between Session 2 and 3: keep Session 2 pods (familiarity for final session)
- Document pod assignments in a shared spreadsheet

### During Session
1. Start in main room (Full Group block)
2. Remind students about the Interpretation globe icon
3. Open breakout rooms at 10:00 mark
4. Moderators float between rooms
5. Close breakout rooms at 35:00 — automatic return to main room
6. Share screen for Blooket quiz / Padlet activity
7. Wrap up in main room

### Free Tier Notes
- Free Zoom: 40-minute limit on group meetings
- Nakhla sessions are 60 minutes — you need Zoom Pro ($13.99/mo) OR:
  - Ask school IT if they have a Zoom Education license (free for K-12)
  - Split session into two 40-min meetings with a break
  - Many schools already have Zoom Pro

---

## 5. Microsoft Flip (Async Pen Pals / Video Messages)

Free moderated video discussion platform for educators. Students record short videos; teacher approves before publishing.

### Setup
1. Go to **flip.com** and sign in with a Microsoft or Google educator account (free)
2. Create a **Group**: "Nakhla Exchange"
3. Create one **Topic** per session:
   - **Topic 1:** "Hello! Introduce Yourself" (Session 1)
   - **Topic 2:** "My World — Food, Family, Traditions" (Session 2)
   - **Topic 3:** "Message to My Pen Pal" (Session 3)
4. Topic settings:
   - **Video length:** 30–60 seconds
   - **Moderation:** ON (teacher reviews before publishing)
   - **Camera and screen recording:** Both enabled
   - **Text responses:** Enabled (for students who prefer writing)
5. Share the Group join code or link in Google Classroom

### How Students Use Flip
1. Students go to flip.com and join with the Group code
2. They open the current Topic and click **Record**
3. They record a 30–60 second video responding to the prompt
4. Teacher reviews and approves videos
5. Students can watch and respond to each other's videos with video replies

### Flip Prompts
Each session folder contains a `flip-prompt.md` with the exact prompt for that session's Topic.

### Why Microsoft Flip
- **Free** for educators (Microsoft account or Google login)
- **Moderated** — teacher approves all content before it's visible
- **Parent-visible** — share the Topic link with parents so they can see their child's videos
- **Async** — students can record between sessions, not just during live time
- **Safe** — designed for K-12, COPPA/FERPA compliant
- **Low barrier** — works on any device with a camera, no app required (web-based)

### Tips
- Assign Flip videos as homework in Google Classroom (link to the Topic)
- Use between sessions to keep engagement alive
- Encourage students to reply to their pen pal's video with their own video
- Teacher can feature standout videos in the next live session

---

## 6. YouTube Unlisted Playlists (Cultural Videos)

Curated video playlists for cultural context — unlisted so only people with the link can view.

### Setup
1. Sign in to YouTube with your school Google account
2. Create one **playlist** per session:
   - **Session 1 Playlist:** "Nakhla — Hello, Neighbor!" — videos about greetings, Israeli and Emirati daily life, kid-friendly cultural intros
   - **Session 2 Playlist:** "Nakhla — Our World" — videos about food, music, games, and family traditions in both cultures
   - **Session 3 Playlist:** "Nakhla — Friends Across the Shore" — videos about friendship, the Abraham Accords (kid-friendly), date palms, shared heritage
3. Set each playlist to **Unlisted** (only accessible via direct link)
4. Add 3–5 short videos per playlist (2–5 minutes each, age-appropriate)

### Embedding in Google Classroom
1. In Google Classroom, create a **Material** post under each session's Topic
2. Paste the YouTube playlist link
3. Title: "Watch Before Session [X]: Cultural Videos"
4. Students can watch at home before the live session as preparation

### Content Guidelines
- All videos must be age-appropriate (8–12 years old)
- Avoid any political or conflict-related content
- Focus on daily life, traditions, food, music, nature, and geography
- Include videos from both Israeli and Emirati creators where possible
- Prefer short videos (under 5 minutes) to maintain attention

### Tips
- Unlisted playlists are not searchable — only people with the link can find them
- Teacher can add/remove videos between sessions as needed
- Use the YouTube "Add to Watch Later" feature to collect candidate videos before curating the playlist
- Consider adding a comment on each video in Google Classroom explaining what to look for

---

## 7. WhatsApp (Parent Communications)

### Setup
1. Create one WhatsApp group per class: **"Nakhla Parents — [School Name]"**
2. Add all parents + both teachers + program coordinator
3. Set group settings: Only admins can send messages (to prevent spam)
4. Admins: teachers + coordinator

### Communication Schedule
| When | What | Who Sends |
|------|------|-----------|
| 1 week before Session 1 | Welcome message + program overview | Coordinator |
| 2 days before each session | Reminder + YouTube playlist link + "ask your child about…" prompt | Teacher |
| After each session | Parent tip (from `parent-tip.md`) + Padlet link + Flip link | Teacher |
| After Session 3 | Thank you + portfolio links (Padlet + Flip) + certificate | Coordinator |

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

## 8. Translation Layer (DeepL + translate.html)

### DeepL API (Primary)
1. Sign up for DeepL API Free at deepl.com/pro-api
2. Get your API key from the account settings
3. Open `tools/translate.html` in a browser
4. Enter your API key (stored in localStorage — never leaves your browser)

### Usage
- Use for preparing all parent communications (WhatsApp messages)
- Use for translating any ad-hoc content (discussion prompts, instructions, Flip prompts)
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

### Google Translate (Fallback)
If DeepL is unavailable or Hebrew translation is needed:
1. Go to translate.google.com — no account needed
2. Supports Hebrew, Arabic, and English with no character limits
3. No API key required — zero setup

---

## Wiring Diagram

```
┌─────────────────────────────────────────────────────┐
│                    BEFORE SESSION                     │
│                                                       │
│  Google Classroom ──→ Distribute vocab + worksheets   │
│  YouTube Playlists ──→ Cultural videos (homework)     │
│  WhatsApp ──→ Parent reminders + playlist links       │
│  DeepL/translate.html ──→ Prepare translations        │
│  Microsoft Flip ──→ Async video introductions         │
└───────────────────────┬─────────────────────────────┘
                        │
┌───────────────────────▼─────────────────────────────┐
│                    DURING SESSION                     │
│                                                       │
│  Zoom (main room) ──→ Full group + wrap-up            │
│       │                                               │
│       ├──→ Interpretation ──→ Hebrew / Arabic / EN    │
│       │                                               │
│       ├──→ Breakout rooms ──→ Pod pairs               │
│       │                                               │
│       └──→ Screen share ──→ Blooket / Padlet          │
└───────────────────────┬─────────────────────────────┘
                        │
┌───────────────────────▼─────────────────────────────┐
│                    AFTER SESSION                      │
│                                                       │
│  Google Classroom ──→ Collect reflections             │
│  Padlet ──→ Portfolio of approved student work        │
│  Microsoft Flip ──→ Async pen pal videos              │
│  WhatsApp ──→ Send parent tip + Padlet/Flip links     │
│  YouTube ──→ Add new videos for next session          │
└─────────────────────────────────────────────────────┘
```
