🧠 1. What is Git? (Simple Explanation)

👉 Git = Version Control System

Means:

Tum apne code ka history track kar sakte ho
Galti ho jaye → previous version pe wapas ja sakte ho
Changes ka record maintain hota hai
📌 Real Life Example:

Socho tum Word file bana rahe ho:

Version1.doc
Version2.doc
Final.doc
Final_Final.doc 😂

👉 Git kya karta hai?
➡️ Ye sab automatically manage karta hai
➡️ Tumhe alag-alag files banani nahi padti

🌐 2. What is GitHub?

👉 GitHub = Online storage for your code (Cloud + Sharing platform)

Git = Local (tumhare laptop pe)
GitHub = Online (internet pe)
📌 Use:
Code backup
Team collaboration
Portfolio (job ke liye important 🔥)

🛠️ 3. Install & Setup Git (Practical)
✅ Step 1: Download Git

👉 Google: Git download

✅ Step 2: Check Installation

Open terminal in VS Code and type:

git --version

✅ Step 3: Setup Git (VERY IMPORTANT)
git config --global user.name "Your Name"
git config --global user.email "your@email.com"

✅🔗 4. Create GitHub Account

👉 Go to: https://github.com

Steps:
Sign up
Username choose karo (professional rakho)
Email verify karo

📂 5. First Git Project (Hands-on 🔥)
Step-by-step:

# folder banao

mkdir my-first-project

# folder open karo

cd my-first-project

# git start karo

git init

# file banao

echo "Hello World" > index.txt

# add file

git add .

# save (commit)

git commit -m "First commit"

👉 Ab tumne apna first project bana liya 🎉

🔥 6. Connect to GitHub
Step 1: GitHub pe repository banao
Step 2: Connect karo
git remote add origin https://github.com/username/repo-name.git
git branch -M main
git push -u origin main

👉 Ab tumhara code online hai 🚀

⌨️ 7. VS Code Shortcuts (Important 🔥)
🧑‍💻 Basic Shortcuts
Shortcut Use
Ctrl + S Save file
Ctrl + C Copy
Ctrl + V Paste
Ctrl + Z Undo
Ctrl + Shift + Z Redo

⚡ Coding Shortcuts
Shortcut Use
Ctrl + / Comment code
Alt + ↑ / ↓ Line move
Shift + Alt + ↓ Duplicate line
Ctrl + D Select same word
Ctrl + P File search
Ctrl + Shift + P Command palette
