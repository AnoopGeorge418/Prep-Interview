# 🚀 `PrePInterView` Application - Features.md

A next-gen interview preparation platform that blends structured planning, social accountability, AI mentoring, and immersive feedback loops — designed for frontend excellence and real-world utility.

---

## 1. **User Authentication & Session Management**

* Secure Login/Signup with localStorage token simulation.
* Forgot password UI flow (email-based mockup).
* Social Auth placeholders (Google, GitHub for future use).
* Guest mode with warning about non-persistent data.
* Auto-session handling, local token refresh system (mock).

---

## 2. **User Onboarding Experience**

* Multi-step onboarding wizard UI:

  * Personal Details (First name, Last name, Email, Phone)
  * Resume Upload: PDF parse simulation (education, experience)
  * Job field/role interest selection with tag-based input (e.g., Frontend, Backend, DevOps)
  * Preferred company targets selection (Google, Amazon, etc.)
* Smart preview & edit of parsed resume data.
* Onboarding progress bar and save state.

---

## 3. **Personalized Dashboard**

* Dynamic module layout (cards/widgets):

  * Recent activity log
  * Streak tracker (calendar-based)
  * Today’s prep goals (interview cards, flashcards, DSA)
  * Mentor spotlight
  * Progress overview (charts)
* Modular layout switcher: list/grid views.
* Quick links to most used sections.

---

## 4. **Resource Library**

* Categorized content:

  * DSA Question Bank (filter/sort/search by tag/difficulty/company/topic)
  * Podcasts (Spotify, YouTube integration)
  * Music for focus (Curated study playlists)
  * Free Courses (Coursera, edX, YouTube)
  * Internal Courses & Blogs (Platform-original)
* Bookmark/favorite system with localStorage tracking.
* Content recommendation based on user behavior.
* UX-enhanced content cards with hover previews, tags, estimated time.

---

## 5. **Interview Scheduler**

* Select date/time + duration for mock interviews.
* Notification system (mock frontend toast reminders).
* ICS file generation for calendar integration.
* UI calendar component to manage upcoming slots.
* Interview type selector (text, voice, assignment, AI).

---

## 6. **Interview Cards**

* Each card includes:

  * Title, description, target role/company
  * Skills tested, tags, level, duration
  * Custom ratings: difficulty, importance
  * Progress tracker (question checklist)
  * Peer reviews & AI feedback summary
* Save, duplicate, share card (frontend only)
* Visibility toggle: private/public template

---

## 7. **Custom Interview Card Builder**

* Create/edit interview cards:

  * Add your own questions
  * Attach LeetCode/Codeforces links
  * Link mock assignments
  * Connect AI coach or human mentor
  * Embed custom notes/resources
* Visual card editor with preview mode
* Version history system (undo/redo)

---

## 8. **Mentor System (Community Support)**

* Request mentors based on skill/field
* Mentor profiles with:

  * Social links, availability schedule
  * Experience & area of focus
  * Testimonials & reviews
* Request mentoring slots
* Mock chat UI (for async text feedback)
* Post-session mentor review form

---

## 9. **AI Assistant - PrepAI**

* Use cases:

  * Daily study suggestions
  * Answer explanations
  * Topic research summarization
  * Mock interview via Q\&A
* Chat UI thread system
* Smart follow-up generator
* Tone/structure evaluation of answers (mock feedback)

---

## 10. **Interview Demo Phase**

* Step-by-step interactive walkthrough:

  * What the interview process looks like
  * Sample question cards
  * Timer simulation
  * AI voice intro/demo
* User can retry or skip demo phase

---

## 11. **Multi-Mode Interview Simulation**

* Interview formats:

  * Text-based Q\&A
  * Assignment-only mode (file upload)
  * Voice-only mode (recorded answers)
  * Video mode (camera UI placeholder)
  * AI-powered simulated interviews
* Timer, question progress, skip/flag feature

---

## 12. **Feedback System**

* Auto-generated feedback (AI + system):

  * Summary: strengths & weaknesses
  * Suggested resources (articles/videos)
  * Skill radar chart
  * Tag-based breakdown (communication, coding, etc.)
* Review rating system for mentors/AI sessions
* Export feedback as PDF/Markdown

---

## 13. **Whiteboard & Notes System**

* Markdown note editor
* Folders named after Interview Cards
* Rich text formatting, checklist
* Autosave with localStorage or indexedDB
* Attach feedback + notes per session automatically

---

## 14. **Error & Offline Handling**

* Custom 404 page with helpful links
* Offline fallback page for PWA support
* Toasts and modals for client-side errors
* Retry/load buttons and empty-state designs

---

## 15. **Gamification & Productivity Enhancers**

* XP & leveling system
* Leaderboard (mocked for frontend)
* Achievement badges (Daily streak, 7-day run, etc.)
* Pomodoro timer with sound/music toggle
* Dark mode toggle + themes

---

## 16. **Settings & Personalization**

* Change name, email, interests
* Resume re-upload and re-parse
* Language preference (English/Hindi/etc.)
* Set daily prep reminder time
* Reset app data (local only)

---

## 17. **Manual Job Application Tracker**

* Users can manually log job applications:

  * Job Title, Company Name, Job Link
  * Status (Applied, In Process, Rejected, Accepted)
  * Interview rounds attended
  * Notes, contacts, dates
* No automation for now (AI parsing can be future upgrade)
* Integrated with dashboard analytics
* Export to CSV option (local-only simulation)

---

## 18. **System Design (Frontend Architecture)**

* Vite + Vanilla JS (Modular structure)
* TailwindCSS w/ utility-first design
* Routing via lightweight JS router
* LocalStorage / IndexedDB for data caching
* Optional SSR-ready architecture

---

## 19. **Tech Stack**

* **UI/UX:** Figma, Mobile and Web design
* **Frontend:** Vite, HTML, JS, Tailwind
* **Version Control:** Git, GitHub
* **Deployment:** Netlify, GitHub Pages, Vercel
* **Backend (future):** ExpressJS + MongoDB/PostgreSQL

---

> ✨ *PrepInterview isn't just a tool — it's a personalized dojo for interview warriors.*

