# 🧠 AHK-Vimmy-Navigator 🚀

**"The keyboard is your sword. Master it."**

Welcome to your new favorite AHK script that brings **Vim-style navigation**, **superpowered text selection**, and **lazy habits detox**—right to your fingertips. Whether you're a Vim nerd moonlighting on Windows or just want smoother keyboard mojo, this script is here to give you ninja-like control over your cursor (and more).

---

## 🌟 What This Script Does

This AutoHotKey script:

- Emulates **Vim-style navigation** (with Alt + hjkl) for fast cursor movement anywhere.
- Powers up your text selection game (with Shift, Ctrl, Alt combos).
- Adds **launch shortcuts** (like launching Everything Search).
- Remaps **CapsLock to Backspace** to cure your backspace addiction.
- Offers **text shortcuts** in terminals.
- Automatically runs at startup for constant key-zen mode.

---

## 🛠️ Setup (How to Install)

1. **Install [AutoHotKey](https://www.autohotkey.com/)** (if you haven’t already).
2. Save this script as something like `vimmy-nav.ahk`.
3. Double-click it to run!
4. **Optional but awesome:** Auto-run on startup by adding this line to the script:
   ```ahk
   FileCreateShortcut, %A_ScriptFullPath%, %A_Startup%\%A_ScriptName%.lnk, %A_ScriptDir%
   ```
   This creates a shortcut to the script in your Startup folder. ✅ Boom, it launches itself!

---

## 🎮 How to Use

### 📦 Navigation (Vim-style, but ALT is your buddy)

| Combo     | Action       | Description                 |
| --------- | ------------ | --------------------------- |
| `Alt + i` | ↑ Move Up    | Just like `k` in Vim        |
| `Alt + k` | ↓ Move Down  | Just like `j` in Vim        |
| `Alt + j` | ← Move Left  | Move left one character     |
| `Alt + l` | → Move Right | Move right one character    |
| `Alt + h` | ⬅ Home       | Go to beginning of the line |
| `Alt + ;` | ➡ End        | Go to end of the line       |
| `Alt + u` | Ctrl + Home  | Go to beginning of document |
| `Alt + o` | Ctrl + End   | Go to end of document       |

### 🔥 Word-by-word Navigation (ALT + CTRL)

| Combo            | Action             |
| ---------------- | ------------------ |
| `Ctrl + Alt + j` | Move left by word  |
| `Ctrl + Alt + l` | Move right by word |

### 🎯 Selecting Stuff (with SHIFT)

| Combo             | Action                          |
| ----------------- | ------------------------------- |
| `Shift + Alt + i` | Select line above               |
| `Shift + Alt + k` | Select line below               |
| `Shift + Alt + j` | Select character to the left    |
| `Shift + Alt + l` | Select character to the right   |
| `Shift + Alt + h` | Select to beginning of line     |
| `Shift + Alt + ;` | Select to end of line           |
| `Shift + Alt + u` | Select to beginning of document |
| `Shift + Alt + o` | Select to end of document       |

### 🤯 Selecting Word-by-word (SHIFT + CTRL + ALT)

| Combo                    | Action               |
| ------------------------ | -------------------- |
| `Ctrl + Shift + Alt + j` | Select previous word |
| `Ctrl + Shift + Alt + l` | Select next word     |

### 🤹 Multicursor-ish? (SHIFT + CTRL + ALT)

| Combo                    | Action                        |
| ------------------------ | ----------------------------- |
| `Ctrl + Shift + Alt + i` | Move multicursor up (kinda)   |
| `Ctrl + Shift + Alt + k` | Move multicursor down (kinda) |

### 🧙‍♂️ Bonus Combos

| Combo             | Action                                                   |
| ----------------- | -------------------------------------------------------- |
| `Ctrl + Alt + E`  | Launch\* [Everything Search](https://www.voidtools.com/) |
| `CapsLock`        | Acts like `Backspace` (say goodbye to bad habits)        |
| `Ctrl + CapsLock` | Acts like regular `CapsLock`                             |
| `Backspace`       | Now acts like `CapsLock`                                 |

> What is `Everything Search`?

_Keep scrolling to find out why Everything Search is the best tool you didn’t know you needed but now can’t live without..._

(Also, it’s free. Like actually free. Like “you-won’t-even-get-an-email-about-it-later” free.)

---

## 🖥 Terminal Text Expansions (Hyper Terminal only)

| Type... | And get...                                           |
| ------- | ---------------------------------------------------- |
| `cdt`   | `cd "C:\Users\visco\OneDrive\Desktop\html-projects"` |
| `cdh`   | `cd ~` (go home, literally!)                         |

---

## Other Text Expansions

| Type... | And get...                                 |
| ------- | ------------------------------------------ |
| `amz`   | `Site:Amazon.com` (for quick search links) |

---

## 🎧 Special Modes

> I don't have a right `Control` key in my keyboard !

- **F3 in VSCode** launches _Zen Mode_ with `Ctrl + K, Z`. Instant minimalism. 🧘
- **AltGr fix**: When active in any window (or Anki), `AltGr` becomes regular `Alt`. Helpful for typing special characters or fixing layout bugs.

---

## 💬 Why This Exists

- You're a Vim lover who sometimes uses Notepad. 😅
- Your fingers are tired of mouse acrobatics.
- You want to level up keyboard workflows.
- You want a smarter CapsLock key (or to break up with Backspace).
- You dream of a frictionless terminal life.

---

## ⚠️ Known Quirks

- Some shortcuts may behave differently in certain apps (depending on how they handle keystrokes).
- Make sure `Everything.lnk` is correctly linked or change the path if needed.
- Not all apps love being told what to do via AutoHotKey—experiment and adjust!

---

## ✨ Final Words

This script is your personal productivity exoskeleton. Tweak it. Break it. Make it yours. Your pinky finger will thank you.

Happy Hacking! 💻💥  
— _Your friendly keyboard whisperer_

---

---

---

# What is **Everything Search**?

🚀🧠 **Everything Search: The Instant File Ninja Your PC Deserves** 🔍✨

_Why wait for Windows Search to “find itself” when you just need your dang PDF? 📁💨_

---

## 💥 Your Files Are Being Held Hostage By Windows Search

Let’s paint a picture:

You’re in a rush.  
You're late to a meeting.  
You need _that one file_ — the critical spreadsheet/presentation/battle plan — and fast. You hit the **Windows key**, type in the filename with the confidence of a thousand suns, and then…

> “No items match your search.” 😐

Excuse me?!  
I _literally just opened it yesterday_. It’s right there. I can **_ see it_** on my desktop. But no — Windows Search has decided it needs to go on a soul-searching journey through the meaning of “indexing” first.

Meanwhile, you’re sweating, your boss is asking where the file is, and Cortana is whispering something unhelpful about the weather.

💡 Enter: **Everything Search.**

Imagine a world where your search bar doesn’t make you question your life choices.  
A world where files appear the _moment_ you type.  
A world where indexing doesn’t take longer than a Marvel movie marathon.

Welcome to the utopia of **Everything** — the Google of your hard drive, but without the ads, surveillance, or existential dread.

---

## 🔍 Why Windows Search Sucks

Let’s be honest, Windows Search is:

- **Slow.** Like, “go make coffee while it finds your file” slow. ☕
- **Bloated.** It’s doing... something? Probably writing a memoir while you wait.
- **Limited.** Doesn’t search system files, special folders, or network drives without begging.
- **Unreliable.** Sometimes it finds stuff. Sometimes it pretends that file never existed. Gaslighting, basically.
- **Indexing like a turtle on vacation.** “Indexing…” — the eternal message. Is it indexing the cosmos? Who knows.
- **Random.** Sometimes finds a file, sometimes just _stares blankly into the void_.

Searching with it is like yelling into a well and hoping the right file echoes back.

It’s like asking a **groggy librarian** who just woke up from a nap:

> “Hey, where’s that PDF from last week?”
>
> > Windows Search blinks slowly... “Hmm... let me look... somewhere... someday... eventually…”

---

## ⚡ Why Everything Search Is the Hero We Deserve

**Everything** is what happens when file search:

- Drinks a double espresso ☕
- Gets a gym membership 🏋️‍♂️
- And actually _cares about your time_

Let’s break it down:

| Feature               | Windows Search                            | Everything Search                                            |
| --------------------- | ----------------------------------------- | ------------------------------------------------------------ |
| 🚀 **Speed**          | “Searching... Searching... Searching...”  | Instant. Like _blink and it’s there_ instant                 |
| 🔍 **Accuracy**       | Kinda just... guesses?                    | Exact matches, wildcards, regex support! Dead-on, every time |
| 🧠 **Resource Usage** | Eats RAM like a buffet                    | Lightweight and efficient                                    |
| **Size**              | Bundled bloat                             | <2MB, portable version available                             |
| 🕰 **Indexing**        | Indexes forever and _still_ misses things | Indexes **millions** of files in seconds                     |
| 😠 **Frustration**    | 😡😤🤯                                    | 😌👏🎉                                                       |
| 🧙‍♂️ **UI Vibes**       | Confusing menus and Cortana yelling       | Minimalist, no-BS, wizard-level precision                    |
| 🛠 **Admin Mode**      | Buried in obscure right-click hell        | One click. Boom. Hacker mode enabled.                        |
| 📚 **Learning Curve** | Somehow still confusing in 2025           | Open it, type stuff, be amazed                               |
| 📦 **Bloat Factor**   | Packs ads, Bing, and sadness              | A 2MB download that respects your SSD                        |
| **Nerd Mode**         | LOL no                                    | Regex, CLI tools, API access                                 |
| 🎩 **Magic Trick**    | May or may not find your files            | Finds files you forgot existed — _instantly_                 |
| **Finds everything?** | Some things. Maybe. Depends.              | YES.                                                         |

---

## 🧪 Technical Magic: How It Works

Everything isn’t scanning every byte of every file. It’s smarter than that. It reads from the **NTFS Master File Table (MFT)** — the magical file system index Windows already keeps.

This means:

- It builds an index of **every single file and folder** in literal seconds.
- It updates in **real-time** (yes, really).
- Efficient CPU/RAM usage. (Even your 10-year-old laptop will cheer.)
- It doesn’t scan contents, just names — and it does that _flawlessly_.
- Blisteringly fast filename matches.

---

## 🧙‍♀️ Real-Life Use Cases

- Type `resume` → Instantly see all 47 versions you swore you'd delete last year.
- Type `*.mp4` → Every video, every folder. Instant movie night.
- Type `budget` → All your spreadsheets, including the final_final_v3_REAL.xlsx
- Use filters, bookmarks, wildcards, or even REGEX (you chaotic wizard).

---

## 💾 Integration with AutoHotKey (Optional, But Spicy)

Want to launch Everything with a single keystroke?  
Use this in your AHK script:

```ahk
^!e:: ; CTRL+ALT+E
    Run, C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Everything.lnk
```

---

## 🤓 Use Cases

- Find any file, instantly. (Obviously.)
- Jump to folders like a boss (e.g., type `Downloads` and teleport like a file system ninja 🥷)
- Dig up that obscure `.psd` file from 2017 your friend _swears_ they sent you
- Filter by file type like a wizard: `*.mp3` = instant music archive. `*.pdf` = academic panic mode.
- Rapidly rename, move, or open files like you're starring in a hacking montage
- Set bookmarks for your deepest, darkest folder paths (because `C:\Users\Bob\Stuff\MoreStuff\TaxStuff\WhyDoIEven\Ugh` is too long to remember)
- Use wildcards and regex to hunt down files with surgical precision (⚠️ Side effects may include feeling powerful)
- Instantly locate that rogue `.exe` you just downloaded and forgot where it went (your Downloads folder is a warzone, admit it)
- Debug your life: Search `final`, `backup`, or `latest` and marvel at the chaos
- Replace `Ctrl+F` anxiety with `Everything.exe` serenity
- Win every office competition of "who can find the file fastest" 🏆

---

## 🧘‍♂️ How It Makes You Feel

**Before Everything Search:**

> “Where the hell is that file?!” 😤  
> You: _panicking_  
> Windows: _indexing like it's decoding ancient Sumerian tablets_  
> Life: _flashing before your eyes_

**After Everything Search:**

> “Oh there it is.”  
> You: ☕ Calm, composed, maybe slightly smug  
> Keyboard: _still warm from that CTRL+ALT+E magic_  
> Life: _in 4K, 60fps, and perfectly indexed_

### Visual Guide:

| Situation                | You Before Everything  | You After Everything   |
| ------------------------ | ---------------------- | ---------------------- |
| Searching a file         | 😱 Sweaty mess         | 😎 Cool and confident  |
| Watching Windows Search  | 🐢 Emotional damage    | ✨ Instant results     |
| File organization system | 🌀 "It’s somewhere..." | 🎯 "Found it!"         |
| Productivity levels      | 📉 Below sea level     | 🚀 Elon-tier liftoff   |
| Confidence in humanity   | 🤡 Lost all hope       | 🧠 Restored completely |

---

## 🧨 Why Aren’t You Using It Yet?

- It’s free.
- It’s fast.
- It’s tiny.
- It works.

This isn’t just a tool. It’s a _lifestyle upgrade_.
Windows Search had its chance. It blew it.
It’s time to evolve.

---

## 🧬 Download It. Now.

👉 [https://www.voidtools.com/](https://www.voidtools.com/)

> No ads. No weird up-sells. Just pure, unadulterated **efficiency**.

---
