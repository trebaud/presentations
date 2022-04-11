# Learn VIM

---

## Introduction

---

- Vim is a "modal" editor from the 90's.
- Comes from its precursor vi
- Voted 3rd most popular editor in a 2015 Stack Overflow survey (https://insights.stackoverflow.com/survey/2015#tech-editor)
- New popular fork called Neovim
- Usually used within the terminal, but also with GUI clients or within other IDEs as plugins

**Important disclaimer**: Vim won't make you a better developer or writer
but it will make your typing experience more pleasurable

### Why learn Vim?

#### CONS

- 😕 steep learning curve (mostly muscle memory)

#### PROS

- 🤟 Vim is a language (no need to learn a bunch of ad-hoc IDE commands by heart)
- 🤟 Vim optimizes for editing text not just writing new text, because most of the time writers are changing
  existing text
- 🤟 Free and open source
- 🤟 Ubiquitous in many different types of environments, learn once use it everywhere
- 🤟 Customizable (might be a con for some people)
- 🤟 Ergonomics and typing efficiency (no more 🐭!)

---

## Fundamentals

---

### Modes

- Normal mode (Esc)
- Insert mode (i)
- Command mode (:)
- Visual mode (v)

- Visual Block (Ctrl-v)
- (Search) (/)

### Normal mode

#### Verbs, Modifiers and Nouns

**Verbs** are actions that be performed on nouns

- c - Change
- d - Delete
- v - Visual
- y - Yank (aka copy)

**Nouns**:

- w - forward word
- b - backward word
- ) - parenthesis block
- } - curly brace block
- gg - top of file
- Shift-g - end of file
- 0 - beginning of line
- $ - end of line

**Modifiers** stand between verbs and nouns to specify how
you might do a change

- i: inside
- a: around
- NUM: number (e.g.: 1, 2, 10)
- t: searches for something and stops before it
- f: searches for that thing and lands on it

❓ Quizz time ❓:

- dw = ?
- cw = ?
- c2w = ?
- ci( = ?
- c$ = ?
- ^ gg d Shift-g = ?

#### Basic motions

- any noun can be used for motion

⬅ h
⬇ j
⬆ k
➡ l

❓ Quizz time ❓:

- ^ gg d Shift-g = ?

#### Additionnal actions and useful stuff

- u - undo
- p - paste
- Ctrl-z: close vim as a background process and go back to terminal

### Command mode

#### Useful stuff

:w - Save current open buffer
:q - Quit vim
:wq - Save and quit
:split - Open new split window
:2 - Move to line number 2
:e [file] open a new file

Also any terminal command using !

### Insert mode

Just type, aka any other editor. To enter it just type i

Can also be entered by other normal commands or verb/nouns combinations:

- Shift-i: go into insert mode at the beginning fo the line
- Shift-a: go into insert mode at the end of the line
- cw: delete forward word and go into insert mode

---

## Vim or Neovim in 2022

---

- Asynchronous
- Embeded terminal
- Plugins, lots of plugins

---

## Sources

---

### Web

- [Learn Vim For the Last Time: A Tutorial and Primer](https://danielmiessler.com/study/vim/)
- [Mastering the Vim Language](https://www.youtube.com/watch?v=wlR5gYd6um0)

### Books

- Practical Vim: Edit Text at the Speed of Thought - Drew Neil
