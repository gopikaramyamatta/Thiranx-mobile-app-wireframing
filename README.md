# UI/UX Design Projects Portfolio

## Student Name: [Your Name]
## Date: May 17, 2026

---

# PROJECT 1: Website UI Redesign

## Website Chosen
Local Community Library Website

## Heuristic Evaluation (Usability Problems Found)

| Problem | Why It's Bad | Severity (1-5) |
|---------|--------------|----------------|
| Search bar is hard to find | Users waste time looking | 2 |
| Buttons look different on each page | Confusing, looks unprofessional | 2 |
| Too much text, no images | Boring, hard to read | 3 |
| Website breaks on mobile phone | Can't use on phone | 1 |
| No confirmation before deleting | Users lose data by mistake | 2 |

## Mood Board & Style Guide

**Mood Board Description:** Clean, modern look with blue and white colors. Friendly and professional.

**Style Guide:**
Colors:

-Main color: #2C5F8A (blue)

-Secondary: #F5F5F5 (light gray)

-Buttons: #FF8C42 (orange)

Fonts:

-Headings: Arial Bold, 24px

-Body text: Arial Regular, 16px

Buttons:

-Round corners, orange background, white text


## High-Fidelity Mockups

**Desktop Design:**
- Header with logo and menu
- Big search bar in the middle
- 3 columns showing popular items
- Footer with contact info

**Mobile Design:**
- Hamburger menu (☰) at top
- Same content but stacked vertically (one column)
- Bigger buttons for fingers

## Responsive Layout

| Component | Desktop | Mobile |
|-----------|---------|--------|
| Navigation | Horizontal top bar | Hamburger menu + bottom bar |
| Search | Full-width bar | Icon that expands |
| Card grid | 3 columns | 1 column |
| Touch targets | Standard | 44x44px minimum |

## Expected Outcome & Learnings

- **Visual hierarchy:** Made search bar prominent and visible
- **Layout design:** Used 3-column grid for desktop, stacked for mobile
- **Responsive design:** Content reflows based on screen size

---

# PROJECT 2: Interactive Prototype Creation

## Part 1: Converting Wireframes to Interactive Prototype

**Tool used:** Figma (free version)

**Steps:**
1. Prepared wireframes as starting point
2. Linked screens together using hotspots
3. Added interactions using Figma's Prototype tab
4. Connected navigation paths: Home → Details → Back → Home

## Part 2: Adding Animations and Transitions

**Animations added:**
- Fade (for modal popups)
- Slide (for menu opening)
- Smart Animate (for button hover effects)
- Push (for screen transitions)

**Settings:**
- Duration: 200-300ms
- Easing: Ease In and Out
- Trigger: On Click / On Tap

## Part 3: Navigation Flows Created

**Primary Flow:**
Home → Detail → Back to Home

**Secondary Flow:**
Menu → Category Page → Detail Page → Back

**Complete Journey:**
User opens app → Home screen → Taps menu → Menu slides open → Taps "Products" → Screen pushes to Products → Taps product card → Card expands to detail → Taps back → Returns to Products → Taps home → Returns to Home

## Part 4: User Testing (Guerrilla Testing)

**Method:** Guerrilla Testing (quick, informal testing with strangers)

**Setup:**
- Location: College library
- Participants: 5 people
- Time per test: 5-10 minutes
- Incentive: Small coffee

**Tasks given:**
1. "Find and open detail page of any item"
2. "Go back to home screen"
3. "Open menu and navigate to different section"

**Think-Aloud Method:** Users spoke their thoughts while testing

## Part 5: Feedback Received

**What users liked:**
- "Animations feel smooth"
- "Easy to navigate"
- "Buttons are easy to tap"

**Problems found:**
- "Back button animation too slow" → Reduced from 400ms to 250ms
- "Didn't know menu was clickable" → Added hover state effect
- "Transitions felt choppy" → Changed easing to Ease In and Out

## Part 6: Refinements Made

| Element | Before | After |
|---------|--------|-------|
| Transition speed | 400ms | 250ms |
| Back button animation | Slide | Fade + Slide |
| Menu icon | Static | Hover effect + color change |
| Card taps | No feedback | Subtle scale animation |

## Part 7: What I Learned

1. Animations must be fast (over 300ms feels slow)
2. Easing matters (Linear feels mechanical)
3. Test early with real people (users find problems team misses)
4. Small incentives work (coffee = 5-10 minutes of time)
5. Layer naming is critical for Smart Animate in Figma

---

# PROJECT 3: Mobile App Wireframing

## Part 1: Basic User Research

**Research Method:** 5-minute interviews with 5 people

**Questions Asked:**
1. "What apps do you use every day?"
2. "What frustrates you most about mobile apps?"
3. "How do you track your tasks or to-dos?"
4. "What would make a task app easier to use?"

**Key Findings:**

| Finding | Number of Users |
|---------|-----------------|
| Current task apps are too complicated | 4 out of 5 |
| Want to add tasks in under 10 seconds | 5 out of 5 |
| Forget to check task lists | 3 out of 5 |
| Need reminders for important tasks | 5 out of 5 |

**User Needs Defined:**
1. Simple – No complicated menus
2. Fast – Add task in 3 taps or less
3. Reminders – Automatic notifications
4. Visual – See what's urgent at a glance

## Part 2: User Personas

**Persona 1: Busy Student**

| Attribute | Details |
|-----------|---------|
| Name | Alex, 21 years old |
| Occupation | College student |
| Pain points | Forgets assignments, overwhelmed |
| Goals | Track homework deadlines |
| Quote | "I need something so simple I don't have to think about it" |

**Persona 2: Working Professional**

| Attribute | Details |
|-----------|---------|
| Name | Sarah, 34 years old |
| Occupation | Marketing manager |
| Pain points | Too many meetings, misses follow-ups |
| Goals | Quick task entry, reminders |
| Quote | "If it takes more than 5 seconds, I won't use it" |

## Part 3: User Flows

**Flow 1: Add a New Task**
Open App → Tap "+" Button → Type Task Name → Set Due Date → Tap Save → Task Appears

**Flow 2: Complete a Task**
Open App → See Task List → Tap Checkbox → Task Moves to Completed

**Flow 3: Set a Reminder**
Open App → Tap on Task → Tap Reminder Icon → Choose Date & Time → Save

## Part 4: Low-Fidelity Wireframes

**Screen 1: Home Screen (Task List)**
┌─────────────────────────┐
│ ☰ TASKS + │
├─────────────────────────┤
│ TODAY (3 tasks) │
│ ☐ Submit assignment │
│ ☐ Buy groceries │
│ ☐ Call dentist │
├─────────────────────────┤
│ THIS WEEK (2 tasks) │
│ ☐ Finish project │
│ ☐ Schedule meeting │
├─────────────────────────┤
│ [Home] [Add] [Profile]│
└─────────────────────────┘


**Screen 2: Add Task Screen**
┌─────────────────────────┐
│ ← BACK NEW TASK │
├─────────────────────────┤
│ Task name: │
│ [__________________] │
│ Due date: │
│ [Select date ▼] │
│ Reminder: │
│ [None ▼] │
│ Priority: │
│ ( ) Low (•) Med ( ) High│
│ [ CANCEL ] [ SAVE ] │
└─────────────────────────┘

**Screen 3: Task Detail Screen**
┌─────────────────────────┐
│ ← BACK DETAIL │
├─────────────────────────┤
│ ☐ Buy groceries │
│ Due: Friday, May 20 │
│ Reminder: None │
│ Priority: Medium │
│ Notes: │
│ [__________________] │
│ [ EDIT ] [ DELETE ] │
└─────────────────────────┘

**Screen 4: Menu Screen**
┌─────────────────────────┐
│ ✕ CLOSE PROFILE │
├─────────────────────────┤
│ 👤 Alex │
│ alex@email.com │
│ 📋 All Tasks │
│ ⭐ Important │
│ ⚙️ Settings │
│ Logout │
└─────────────────────────┘

## Part 5: Design Thinking Process

**Phase 1: Empathize** – Interviewed 5 users about task management frustrations

**Phase 2: Define** – "Users need a way to quickly add and track tasks without complicated menus"

**Phase 3: Ideate** – Big "+" button, minimum taps, color-coded priorities

**Phase 4: Wireframe** – Created 4 low-fidelity wireframes

**Phase 5: Test** – Tested with 2 users using paper wireframes

## Part 6: Final Wireframe Summary

| Screen | Purpose | Key Elements |
|--------|---------|--------------|
| Home | View all tasks | Task list, checkbox, "+" button |
| Add Task | Create new task | Text input, date picker, priority |
| Task Detail | View/edit one task | Task info, edit/delete buttons |
| Menu | App settings | User info, navigation links |

## Part 7: What I Learned

1. Start with paper – Drawing is faster than digital for early ideas
2. Talk to users before designing – Interviews simplify your design
3. Personas keep you focused – Ask "Would Alex use this?"
4. Low-fidelity is enough – You don't need colors to test flows
5. Every tap costs patience – Remove unnecessary screens

---

# PROJECT SUMMARY

| Project | Main Deliverable | Key Skill Learned |
|---------|------------------|-------------------|
| Website UI Redesign | Style guide + responsive mockups | Visual hierarchy, responsive design |
| Interactive Prototype | Clickable prototype with animations | User testing, iteration |
| Mobile App Wireframing | Low-fidelity wireframes + personas | User research, wireframing |

---
