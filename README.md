# 🧠 AHK-Vimmy-Navigator 🚀

**"The keyboard is your sword. Master it."**

Welcome to your new favorite AHK script that brings **Vim-style navigation**, **superpowered text selection**, and **lazy habits detox**—right to your fingertips. Whether you're a Vim nerd moonlighting on Windows or just want smoother keyboard mojo, this script is here to give you ninja-like control over your cursor (and more).

# :warning: I'm currently using a more complete alternative script, you cand find it [here](https://github.com/visconttig/vim-navigation).

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

---

## 🖥 Terminal Text Expansions

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
- **AltGr fix**: When active in any window, `AltGr` becomes regular `Alt`. Helpful for typing special characters or fixing layout bugs.

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
