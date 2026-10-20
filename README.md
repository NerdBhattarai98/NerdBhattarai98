<!-- GitHub profile README · NerdBhattarai98 Palette: navy #0B1020 · cyan #00E5FF · violet #8B5CF6 · lime #7EE787 · soft white #E6F1FF · gray #8B949E Maintenance: the only section that changes often is "Currently Building" (four lines). --> <div align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1020,45:1E1B4B,75:8B5CF6,100:00E5FF&height=190&section=header&text=Anbit%20Bhattarai&fontSize=50&fontColor=E6F1FF&fontAlignY=38&desc=Computer%20Science%20Student%20%C2%B7%20Python%20%26%20Data%20%C2%B7%20Building%20toward%20AI%2FML%20and%20Full-Stack&descSize=15&descAlignY=60&descColor=00E5FF" alt="Anbit Bhattarai — Computer Science Student, Python and data, building toward AI/ML and full-stack" width="100%" /> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3200&pause=1000&color=00E5FF&center=true&vCenter=true&width=640&height=40&lines=Building+practical+software+through+code.;Exploring+machine+learning+and+data-driven+systems.;Learning+by+building%2C+testing%2C+and+improving." alt="Building practical software through code. Exploring machine learning and data-driven systems. Learning by building, testing, and improving." /> <br/> <img src="https://img.shields.io/badge/open%20to-internships%20%26%20entry--level-7EE787?style=flat-square&labelColor=0B1020" alt="Open to internships and entry-level roles" /> <img src="https://img.shields.io/badge/focus-Python%20%C2%B7%20Data%20%C2%B7%20ML-00E5FF?style=flat-square&labelColor=0B1020" alt="Focus: Python, data, machine learning" /> <img src="https://img.shields.io/badge/based%20in-Nepal-8B5CF6?style=flat-square&labelColor=0B1020" alt="Based in Nepal" />
<br/><br/>
<b><a href="#about">About</a> · <a href="#tech-stack">Stack</a> · <a href="#featured-projects">Projects</a> · <a href="#currently-building">Now</a> · <a href="#roadmap">Roadmap</a> · <a href="#contact">Contact</a></b>
</div> <br/>
About
I'm a computer science student who likes problems that can be taken apart and solved with code. Most of my work is in Python: I analyse data with Pandas, NumPy, Matplotlib and Seaborn, and I've built two full-stack Python applications, a file organizer and a book recommender.
Right now I'm moving from data analysis toward machine learning, and from small web pages toward full-stack development. I learn by implementing things myself, breaking them, and finding out why they broke. If I can't explain how a solution works, I don't consider it finished.
What I'm focused on
Area
Using now
Learning next
AI/ML & data
NumPy, Pandas, Matplotlib, Seaborn, EDA, TF-IDF with scikit-learn
Statistics, SQL, core ML models and evaluation
Software development
Python, C, C++, C#, Git, debugging
Testing habits, cleaner project structure
Web & apps
HTML, CSS, JavaScript, React, FastAPI, Flask, Flutter
Next.js, Django, relational databases, deployment

<br/>
Tech Stack
<!-- Icons: skillicons.dev (ids checked against the skill-icons source). Data libraries have no skillicons icon, so they use text badges. -->
Languages<br/> <img src="https://skillicons.dev/icons?i=py,c,cpp,cs,js,dart&theme=dark" alt="Python, C, C++, C#, JavaScript, Dart" /><br/> <sub>Python · C · C++ · C# · JavaScript · Dart</sub>
Data analysis & visualization<br/> <img src="https://img.shields.io/badge/NumPy-0B1020?style=flat-square&logo=numpy&logoColor=00E5FF" alt="NumPy" /> <img src="https://img.shields.io/badge/Pandas-0B1020?style=flat-square&logo=pandas&logoColor=00E5FF" alt="Pandas" /> <img src="https://img.shields.io/badge/Matplotlib-0B1020?style=flat-square" alt="Matplotlib" /> <img src="https://img.shields.io/badge/Seaborn-0B1020?style=flat-square" alt="Seaborn" /> <img src="https://img.shields.io/badge/Jupyter-0B1020?style=flat-square&logo=jupyter&logoColor=00E5FF" alt="Jupyter Notebook" /> <img src="https://img.shields.io/badge/scikit--learn-0B1020?style=flat-square&logo=scikitlearn&logoColor=00E5FF" alt="scikit-learn" />
Web, backend & mobile — used in the projects below<br/> <img src="https://skillicons.dev/icons?i=html,css,react,vite,fastapi,flask,mongodb,sqlite,flutter&theme=dark" alt="HTML, CSS, React, Vite, FastAPI, Flask, MongoDB, SQLite, Flutter" /><br/> <sub>HTML · CSS · React · Vite · FastAPI · Flask · MongoDB · SQLite · Flutter</sub>
Tools<br/> <img src="https://skillicons.dev/icons?i=git,github,vscode&theme=dark" alt="Git, GitHub, VS Code" /><br/> <sub>Git · GitHub · VS Code</sub>
Currently learning: <code>Statistics</code> <code>SQL</code> <code>Machine learning</code> <code>Next.js</code> <code>Django</code>
<sub><i>Listed technologies are ones I've used in my own code. That isn't the same as equal mastery of all of them.</i></sub>
<br/>
Featured Projects
<!-- No screenshots exist in these repositories yet. To add one: 1. Put the image in the project repo, e.g. docs/screenshot.png 2. Paste a row like this into that project's table: <tr><td><b>Screenshot</b></td><td><img src="https://raw.githubusercontent.com/NerdBhattarai98/Smart-File-Organizer/main/docs/screenshot.png" alt="Smart File Organizer dashboard" width="100%" /></td></tr> -->
Smart File Organizer  <img src="https://img.shields.io/badge/full--stack-local%20app-00E5FF?style=flat-square&labelColor=0B1020" alt="Full-stack local app" />
A full-stack desktop-folder tool: scan a folder, sort its files into categories, find duplicates, and undo anything it moved.
<table> <tr><td width="150" valign="top"><b>Problem</b></td><td>Download and project folders fill up with unsorted files, duplicate copies, and meaningless names like <code>IMG_8812 (1).jpg</code>, and cleaning them by hand is slow and risky.</td></tr> <tr><td valign="top"><b>What I built</b></td><td> A <b>React + Vite</b> frontend with seven pages (dashboard, organize, classification, duplicates, batch operations, history, settings) talking to a <b>FastAPI</b> backend split into nine route modules: scan, classify, duplicate detection, name-collision checks, apply action, undo, history, file movements, and database sync. </td></tr> <tr><td valign="top"><b>How it works</b></td><td> • <b>Classification</b> is rule-based: extension map first, then MIME type, then filename keywords.<br/> • <b>Duplicate detection</b> runs from most to least certain: content hash (exact copies), an 8×8 average hash with Pillow (visually identical images), then filename similarity.<br/> • <b>Collision handling</b> checks for same-name files at the destination before moving and offers a resolution.<br/> • Detects random-looking filenames and suggests readable ones. </td></tr> <tr><td valign="top"><b>Design decisions</b></td><td> Every move is logged and reversible: undo the last action, a specific action, or a batch. Actions are stored in <b>MongoDB</b>. Because the API touches the file system, CORS and trusted hosts are restricted to localhost. </td></tr> <tr><td valign="top"><b>Stack</b></td><td><code>Python</code> <code>FastAPI</code> <code>Pydantic</code> <code>MongoDB</code> <code>Pillow</code> <code>React 18</code> <code>React Router</code> <code>Vite</code></td></tr> <tr><td valign="top"><b>Status</b></td><td>Working locally · no hosted demo · minimal test coverage so far</td></tr> <tr><td valign="top"><b>Code</b></td><td><a href="https://github.com/NerdBhattarai98/Smart-File-Organizer"><b>NerdBhattarai98/Smart-File-Organizer</b></a></td></tr> </table>
Book Recommendation System  <img src="https://img.shields.io/badge/ML-recommender-8B5CF6?style=flat-square&labelColor=0B1020" alt="Machine learning recommender" />
A Flask web app that recommends books from a user's favorites, to-read list, history and searches.
What I built: user accounts (register, login, profile), book browsing and search, favorites and to-read lists, and a recommendations page, using Flask with Jinja templates, HTML, CSS and JavaScript, with user data in MongoDB.
Recommendation logic: content-based filtering with TF-IDF (unigrams and bigrams, 8,000 features) and cosine similarity, blended with a genre-similarity model into a weighted hybrid, plus signals from other users' activity.
Engineering: a separate train_models.py precomputes the TF-IDF matrix so the app starts faster; four tests/ modules cover auth, books, and both filtering approaches.
Lesson: the source dataset has ratings per book, not per user, so true collaborative filtering wasn't possible from it. I used genre similarity and live user activity instead. Choosing an algorithm starts with checking what the data can actually support.
Stack: Python Flask scikit-learn Pandas NumPy SciPy MongoDB
Code: NerdBhattarai98/Book-Recommendation-System
Flutter Todo App  <img src="https://img.shields.io/badge/mobile-Flutter-7EE787?style=flat-square&labelColor=0B1020" alt="Mobile app built with Flutter" />
A cross-platform task manager and my first Flutter project.
Add, edit, complete and delete tasks (with a delete confirmation), and view them in separate Pending and Completed tabs with expandable descriptions.
Tasks persist on the device in SQLite through sqflite, behind a small singleton database class.
Stack: Flutter Dart sqflite google_fonts
Code: NerdBhattarai98/FlutterProject_1-
Data Analysis Portfolio  <img src="https://img.shields.io/badge/status-in%20progress-00E5FF?style=flat-square&labelColor=0B1020" alt="In progress" />
Five real datasets (Spotify, Netflix, Formula 1, international football, World Happiness 2019), each analysed with the same 8-step EDA workflow: question, inspect, clean, univariate, bivariate, multivariate, segments, findings. My working rules include logging every cleaning decision, applying minimum sample sizes before ranking, and never presenting correlation as causation.
Progress: Spotify Tracks, steps 1–4 done · the other four are planned  →  NerdBhattarai98/Data_Analysis_Projects
Learning repositories
Repository
What's inside
Numpy-for-AI-ML
Six modules with practice files and cheat sheets: array foundations, indexing (including views vs copies), manipulation, vectorization and broadcasting (standardization, softmax), linear algebra, random numbers and statistics
Pandas-for-AI-ML
Series, DataFrames, importing, selection, filtering, aggregation, data cleaning, and merge/concat/join

<br/>
Currently Building
<!-- Edit these four lines when your focus changes. -->
$ git status
  focus      : Python data analysis → practical machine learning
  project    : Spotify Tracks EDA (Data_Analysis_Projects, project 1 of 5)
  next       : steps 5–8: bivariate and multivariate analysis, written findings
  learning   : statistics and SQL foundations before scikit-learn models

<br/>
Roadmap
✓ done   ▸ in progress   ○ planned
AI/ML
✓ NumPy · Pandas · Matplotlib · Seaborn  →  ▸ Exploratory data analysis  →  ○ Statistics, probability & SQL  →  ○ Core ML & evaluation  →  ○ Feature engineering, leakage prevention & error analysis  →  ○ Deep learning fundamentals  →  ○ Model APIs & deployment  →  ○ LLM apps, retrieval & evaluation  →  ○ Reproducible workflows, testing & MLOps basics
Full-stack
✓ HTML · CSS  →  ▸ JavaScript fundamentals  →  ○ React in depth & Next.js  →  ○ Python backends (FastAPI, Django)  →  ○ SQL & relational design  →  ○ Testing, Git workflow & deployment  →  ○ Full-stack apps with data or AI features
<br/>
How I Solve Problems
Observe → Understand → Break down → Implement → Test → Improve
# when something breaks
reproduce  → make the failure happen on purpose
read       → the full error message, not just the last line
cause      → find the root cause, not the symptom
fix        → change one thing, then re-test
record     → write down the lesson if it will come back

In code, this means tracing how data moves and where conditions branch until I can explain the output. In data analysis, it means inspecting and cleaning before plotting, and treating every finding as a hypothesis until the numbers and sample sizes support it.
<br/>
GitHub Activity
<!-- Optional: these cards come from third-party services. Delete this section if they become unreliable; nothing else depends on it. --> <div align="center"> <img src="https://github-readme-stats.vercel.app/api?username=NerdBhattarai98&show_icons=true&hide_border=true&bg_color=0B1020&title_color=00E5FF&text_color=E6F1FF&icon_color=8B5CF6&border_radius=10" alt="GitHub statistics for NerdBhattarai98" height="165" /> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NerdBhattarai98&layout=compact&langs_count=6&hide_border=true&bg_color=0B1020&title_color=00E5FF&text_color=E6F1FF&border_radius=10" alt="Most-used languages by bytes across public repositories" height="165" /> <img src="https://streak-stats.demolab.com?user=NerdBhattarai98&hide_border=true&background=0B1020&ring=00E5FF&fire=8B5CF6&currStreakNum=E6F1FF&currStreakLabel=7EE787&sideNums=E6F1FF&sideLabels=8B949E&dates=8B949E&border_radius=10" alt="Contribution streak for NerdBhattarai98" width="100%" />
<sub><i>Language shares are file sizes in public repos, not skill levels. Flutter's generated platform code counts as C++.</i></sub>
</div> <details> <summary><b>Contribution graph</b></summary> <br/> <img src="https://github-readme-activity-graph.vercel.app/graph?username=NerdBhattarai98&bg_color=0B1020&color=00E5FF&line=8B5CF6&point=7EE787&area=true&area_color=8B5CF6&hide_border=true&title_color=00E5FF&custom_title=Contribution%20activity" alt="Contribution activity graph for NerdBhattarai98" width="100%" /> </details> <br/>
Contact
I'm open to conversations about internships, entry-level roles, technical projects and collaboration.
<a href="https://www.linkedin.com/in/anbit-bhattarai-518377370"><img src="https://img.shields.io/badge/LinkedIn-Connect-00E5FF?style=for-the-badge&logo=linkedin&logoColor=00E5FF&labelColor=0B1020" alt="LinkedIn: Anbit Bhattarai" /></a> <a href="mailto:anbitbhattarai2005@gmail.com"><img src="https://img.shields.io/badge/Email-anbitbhattarai2005%40gmail.com-8B5CF6?style=for-the-badge&logo=gmail&logoColor=8B5CF6&labelColor=0B1020" alt="Email: anbitbhattarai2005@gmail.com" /></a> <a href="https://github.com/NerdBhattarai98?tab=repositories"><img src="https://img.shields.io/badge/GitHub-Repositories-7EE787?style=for-the-badge&logo=github&logoColor=7EE787&labelColor=0B1020" alt="All GitHub repositories" /></a> <a href="https://github.com/Arixon-Technology"><img src="https://img.shields.io/badge/Org-Arixon--Technology-00E5FF?style=for-the-badge&logo=github&logoColor=00E5FF&labelColor=0B1020" alt="Arixon-Technology on GitHub" /></a>
<sub>Text links: LinkedIn · anbitbhattarai2005@gmail.com · Repositories · Arixon-Technology</sub>
<br/> <div align="center">
<code>while (learning) { build(); test(); improve(); }</code>
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00E5FF,50:8B5CF6,100:0B1020&height=90&section=footer" alt="" width="100%" /> </div> 

