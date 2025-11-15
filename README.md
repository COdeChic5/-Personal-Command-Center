# Personal Command Center ⚔️

A neon cyberpunk-themed **personal dashboard** that lives in your browser.  
Manage your **tasks**, dump your **notes**, and lock in using a **focus timer** – all in one place.

Everything is stored in `localStorage`, so your data stays on your device.

---

## 🔥 Features

- ✅ **Tasks Panel**
  - Add missions (tasks)
  - Mark them as complete
  - Delete when done
  - Tasks auto-save in `localStorage`

- 🧠 **Notes / Intel Dump**
  - Freeform notes area
  - Perfect for ideas, links, thoughts
  - Notes are auto-saved as you type

- ⏱️ **Focus Timer**
  - 25-minute default focus timer (Pomodoro-style)
  - **Start / Pause / Reset** controls
  - “Mission complete” alert when time’s up

- 💾 **Local-First**
  - No backend, no server
  - All data is saved in your browser using `localStorage`

- 🎨 **Cyberpunk UI**
  - Neon gradients
  - Glowing cards
  - Monospace hacker vibe

---

## 🧩 Tech Stack

- **HTML** – structure  
- **CSS** – neon cyberpunk styling  
- **Vanilla JavaScript** – tasks, notes, timer, and localStorage logic  
- **No frameworks**, no build tools

---

## 🚀 Getting Started

1. Clone the repo:

   ```bash
   git clone https://github.com/COdeChic5/-Personal-Command-Center.git
   cd -Personal-Command-Center
Open the index.html file in your browser:

Option A: Double-click index.html

Option B: Use a simple dev server (example with Python):

bash
Copy code
# if you have Python 3 installed
python -m http.server 8000
Then visit: http://localhost:8000

🛠️ Project Structure
bash
Copy code
-Personal-Command-Center/
├─ index.html    # Main file containing HTML, CSS (in <style>) and JavaScript (in <script>)
├─ README.md     # Project documentation
(If you later split CSS/JS into separate files, you can update this section.)

🧠 How It Works (Dev Notes)
Tasks
Stored in localStorage under the key "tasks".

Each task is an object:

js
Copy code
{ text: "Task name", done: false }
Notes
Stored as a simple string under "notes" in localStorage.

Auto-saves on every input event.

Timer
Default duration: 25 * 60 seconds.

Uses setInterval to tick every second.

Displays time in MM:SS format.

🌐 Live Demo (GitHub Pages)
You can host this as a static web app using GitHub Pages:

Go to your repo:
https://github.com/COdeChic5/-Personal-Command-Center

Go to Settings → Pages

Under Source, select:

Branch: main

Folder: / (root)

Click Save

After a minute, your site will be available at:

text
Copy code
https://codechic5.github.io/-Personal-Command-Center/
💡 Future Ideas
Customizable timer lengths (e.g., 25 / 50 mins, break timer)

Dark/light theme toggle

Task categories or priority tags

Export / Import data as JSON

Keyboard shortcuts for tasks and notes

📜 License
MIT License – feel free to use, modify, and build on this.

yaml
Copy code
