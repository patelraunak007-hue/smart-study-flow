# Smart Study Flow ⚡

> AI Priority-Driven Auto Timetable Generator & Distraction-Aware Pomodoro Focus Tracker for Students.

---

## 🌟 Key Features

1. **Auto Timetable Generator**:
   - Calculates assignment urgency score using \( \text{Urgency} = \frac{\text{Difficulty Weight} \times 10}{\text{Hours Remaining}} \).
   - Maps 25-minute Pomodoro study blocks automatically into student's available daily free time slots.

2. **Pomodoro Focus Mode with Distraction Detection**:
   - Built-in study timer (25m study / 5m short break / 15m long break).
   - Real-time **Tab Switch & Window Blur Detection** via `document.visibilityState`.
   - Dynamic **Focus Score** (\(100\% - (\text{Distractions} \times 5\%)\)).
   - Timestamped distraction event log and audio alerts.

3. **Assignment & Deadline Tracker**:
   - Central deadline dashboard color-coded by urgency.
   - Status filters & countdown trackers.

4. **Group Study Rooms**:
   - Virtual co-working space with shared Pomodoro timers, peer activity indicators, and real-time chat.

5. **Progress Analytics Dashboard**:
   - Subject-wise study time breakdown, focus score trends, streaks, and focus badges.

---

## 🚀 How to Run the App

### Option A: Open Standalone Interactive Demo (Instant Pitch Preview)
Open the generated HTML app artifact directly in your browser:
`C:\Users\Student\.gemini\antigravity\brain\91ecbba5-bd3e-4cbe-a387-f82888ea45e0\smart_study_flow.html`

### Option B: Node / Vite App Development
```bash
cd C:\Users\Student\.gemini\antigravity\scratch\smart-study-flow
npm install
npm run dev
```

---

## 🏆 Hackathon Pitch Tips for Judges

1. **Highlight the AI Timetable Engine**: Demonstrate adding an assignment with an imminent deadline and high difficulty, then click **Generate Optimized Schedule** to show how the algorithm rearranges study blocks.
2. **Demonstrate Tab Switch Detection**: Start a Pomodoro timer and switch tabs in your browser. Switch back to watch the live alert banner trigger and the Focus Score drop.
