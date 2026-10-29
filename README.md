# 🧭 GIT QUEST

**GDG Weekly Challenges | Week 2: FOSS**

## 🗺️ 2 Levels. 1 Repository. Your Open Source Adventure Begins!

Welcome, Git Adventurer! 🚀

Ready to explore Git, discover hidden secrets, express yourself, and make your contribution? You've landed in the right place!

Complete the quests below, follow the clues, and leave your mark on the repository. Whether you're a Git newbie or a version-control veteran, the adventure starts here! 🎮

---

## 🎒 Before You Begin

1. **Fork** this repository using the Fork button at the top right.
   ⚠️ Make sure **"Copy the main branch only" is unticked**, or you'll miss the clues!
2. **Clone your fork** (not this repo) and create your own branch:

```bash
git clone https://github.com/<your-username>/Git_Quest.git
cd Git_Quest
git checkout -b my-branch-IIT2025123
```

🔖 Replace `<your-username>` with your GitHub username and `IIT2025123` with your own roll number.

⚠️ **Quest rule:** Do all your work on your own branch. Never push to or edit `main` directly.

---

## 📝 LEVEL 1: Intro Session

Every great adventure begins with an introduction. Let's get to know you! 👋

📂 **Your mission:** Create a file named `submissions/yourname.md` (e.g., `submissions/ankit_pal.md`).

Inside it, answer the following questions:

- 👋 **The Introduction:** What's your name, GitHub username, and why are you HERE at this college?
- 🦸 **Your Hero:** What's your favourite open-source tool, if you have one?
- 😂 **Comic Relief:** Share a programming joke or meme you've come across.
- 💡 **Your Take on Open Source:** What does open source mean to you?

  *(💚 Be yourself! We want to hear YOUR thoughts. No AI-generated answers for this question, please!)*

### 🐱 The Mood Cat

Create a little ASCII cat that represents your current mood!

Start with this tiny companion:

```text
 /\_/\
( o.o )
 > ^ <
```

Give your cat a personality by changing its eyes:

| Mood | Eyes |
|---|---|
| 😄 Happy | `^.^` |
| 😴 Sleepy | `-.-` |
| 😵 Confused | `@.@` |
| 😫 Stressed | `>.<` |

🎨 **Want to go beyond the basics?** Add accessories, a funny expression, a hacker identity, or a tiny developer-themed twist. Surprise us with your creativity!

Add your cat directly to your introduction file under a heading like `### 🐾 My Mood Cat` and make it uniquely yours.

✨ **Pro tip:** Use Markdown headings, lists, and emojis to make your introduction stand out.

### 🚀 Save Your Work & Push It

Once your introduction and mood cat are ready, commit your changes and push your branch to your fork.

```bash
git add submissions/yourname.md
git commit -m "Introduced myself 🐱"
git push -u origin my-branch-IIT2025123
```

🔖 Remember to replace the filename and branch name with your own.

---

## 🏴‍☠️ LEVEL 2: The Hunt for the Hidden Flag

A secret is buried somewhere in this repository... 👀

Your mission, should you choose to accept it, is to uncover the complete flag:

```text
FOSS{...}
```

### 🔍 Follow the Clues

- 📂 **Start your hunt in the `task` folder.**
- 🧩 The flag has **3 parts**.
- 🎭 Beware of fake flags! Not every discovery is the real one.
- 🕵️ Some clues might not be immediately visible, so explore carefully.
- 🕰️ Git remembers more than your files show. Sometimes the past holds the answers.
- 🔁 Once you've found the flag, **return to your own branch** before continuing.

> 💡 **Having trouble opening `secret.png`?**
>
> You can open the image directly from your terminal using the command for your operating system:
>
> | Operating System | Command |
> |---|---|
> | 🪟 Windows (Git Bash) | `start secret.png` |
> | 🍎 macOS | `open secret.png` |
> | 🐧 Linux | `xdg-open secret.png` |
>
> ⚠️ Run the command from the directory containing `secret.png`, or provide the correct relative path to the image.

🚩 **Found it?** Add the complete flag at the bottom of your introduction file:

```text
Flag: FOSS{...}
```

### 💻 Commit Your Discovery

After adding the flag, commit and push the update:

```bash
git add submissions/yourname.md
git commit -m "Uncovered the hidden flag 🔎"
git push
```

🔖 Replace `yourname.md` with your own filename.

---

## 📬 Submit Your Quest

1. Push your branch to your fork.
2. Open a **Pull Request** from your branch to this repository's `main` branch.
3. Submit your **Pull Request link** through the Google Form.

---

## 🏁 Quest Complete!

Congrats! 🎉

Before you wrap up, make sure you've completed everything:

- [ ] 👋 Created `submissions/yourname.md`.
- [ ] 💡 Answered the introduction questions in your own words.
- [ ] 🐱 Added your creative mood cat to your introduction.
- [ ] 🚩 Found and added the correct hidden flag.
- [ ] 🚀 Pushed your changes to your own branch on your fork.
- [ ] 📬 Opened a Pull Request and submitted its link in the Google Form.

---

Every open-source contributor starts somewhere. This is your chance to learn, explore, experiment, and become part of the community.

**Happy Hacking! 💚**