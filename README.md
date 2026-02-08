# Student Rank Master (RankMaster Pro)

Student Rank Master (RankMaster Pro) is a web application that builds a shared class leaderboard from students’ semester marks.[page:1] Students enter their name, USN (roll number), and seven subject-wise marks (up to three digits each), and the app automatically calculates the total and ranks everyone from highest to lowest.[page:1]

## Features

- Add and track up to 60 students in a single leaderboard.[page:1]
- Subject-wise marks entry (7 subjects, up to 3-digit scores) with **automatic** total calculation.[page:1]
- Class ranking updates instantly whenever a new student is added or updated.[page:1]
- High-contrast, easy-to-read input fields and table layout for quick data entry in labs or classrooms.[page:1]
- Persistent storage so leaderboard data is not lost on refresh (local and cloud-backed, depending on configuration).[page:1]
- Shareable HTTP/HTTPS leaderboard link so friends opening the link see the same results and can add their own entries while preserving previous data.[page:1]

## VTU Smart Importer (Concept)

The project is designed to work alongside the VTU results portal.[page:1] Instead of manually calculating totals, a “Smart Import” flow allows students to copy result text from the official site, paste it into the app, and let AI extract the name, USN, and total marks out of 700 before adding it to the leaderboard.[page:1]

## Tech Stack

- Frontend: React + TypeScript (App.tsx, StudentForm, RankTable, StatsOverview, PerformanceChart components).[page:1]
- Styling: Standard web UI with focus on clarity and accessibility.[page:1]
- Storage & Sharing: Browser storage plus a cloud-backed board ID and shareable URL for collaborative leaderboards.[page:1]

## How to Use

1. Enter your name, USN, and subject-wise marks in the form.
2. Click “Register Profile” to add yourself to the leaderboard.
3. Share the generated link with friends so they can open the same board and add their marks.
4. Watch the leaderboard update and see ranks recalculate automatically.[page:1]

## Future Improvements

- More powerful VTU Smart Importer with direct text parsing for multiple students.
- Advanced analytics (average, highest, lowest per subject).
- Authentication and per-class admin controls for secure leaderboard management.[page:1]
