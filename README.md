<h1 align="center">👋 Hi, I'm Thep</h1>

<p align="center">
  💻 Web App Developer | Computer Science Student | Front-End & Back-End
</p>

from datetime import date, timedelta
import os

TEXT = [
    "TTTT H   H EEEE PPP ",
    " T   H   H E    P  P",
    " T   HHHHH EEEE PPP ",
    " T   H   H E    P   ",
    " T   H   H EEEE P   ",
]

start_date = date(2024, 1, 1)  # เริ่มวาดจากวันที่
for y, row in enumerate(TEXT):
    for x, char in enumerate(row):
        if char != ' ':
            d = start_date + timedelta(days=x + y * 7)
            os.system(f"GIT_COMMITTER_DATE='{d}T12:00:00' git commit --allow-empty -m 'dot' --date='{d}T12:00:00'")

---

### 🌟 About Me
- 🧠 Currently learning **React, Node.js, and Cloud Computing**
- 💬 Ask me about **HTML, CSS, JS, or Web Development**
- ⚡ Fun fact: I love minimal design & clean UI!

---

### 🧠 Tech Stack
<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,react,nodejs,python,vscode,github" />
</p>

---


---

### 🐍 Snake Animation
<p align="center">
  <img src="https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg" alt="snake animation" />
</p>

