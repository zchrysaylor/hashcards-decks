---
name = "Vim"
---

Q: i
A: Switches to insert mode and allows you to edit text right before the current cursor position

---

Q: I
A: Switches to insert mode and places the cursor at the beginning of the line

---

Q: a
A: Switches to insert mode and allows you to edit text right after the current cursor position

---

Q: A
A: Switches to insert mode and places the cursor at the end of the line

---

Q: o
A: Switches to insert mode adding a line below the current one

---

Q: O
A: Switches to insert mode adding a line above the current one

---

Q: v
A: Switch to character-wise VISUAL mode

---

Q: V
A: Switch to line-wise VISUAL mode

---

Q: <C-v>
A: Switch to block-wise VISUAL mode

---

Q: zt
A: Move the screen to the top of the window

---

Q: zz
A: Move the screen to the middle of the window

---

Q: zb
A: Move the screen to the bottom of the window

---

Q: H
A: Move the cursor to the highest line on the screen

---

Q: M
A: Move the cursor to the middle line on the screen

---

Q: L
A: Move the cursor to the lowest line on the screen

---

Q: gg
A: Move the cursor to the beginning of the file

---

Q: G
A: Move the cursor to the end of file

---

Q: ``
A: Return to the previous place (repeating toggles between two most recent locations)

---

Q: <C-o> (NORMAL mode)
A: move backwards through the jump list

---

Q: <C-i> (NORMAL mode)
A: move forwards through the jump list

---

Q: '' (two single quotes)
A: Return to previous line (first non-blank character)

---

Q: ^
A: Move to the first character in the beginning of the line

---

Q: 0 (zero)
A: Move to the beginning of the line

---

Q: $
A: Move to the end of the line

---

Q: w
A: Move to the beginning of the next word

---

Q: W
A: Move to the beginning of the next WORD (any sequence of non-blank characters)

---

Q: e
A: Move to the end of the current word

---

Q: b
A: Move to the beginning of the current word

---

Q: ge
A: Move to the end of the previous word

---

Q: f{char}
A: Jump to the next character found

---

Q: F{char}
A: Jump to the previous character found

---

Q: t{char}
A: Jump to the character before the next character found

---

Q: T{char}
A: Jump to the character after the previous character found

---

Q: ;
A: Repeat a jump to the next character found

---

Q: ,
A: Repeat a jump to the previous character found

---

Q: *
A: Repeat a jump to the next word found

---

Q: #
A: Repeat a jump to the previous word found

---

Q: y{space}
A: Yank the character under the cursor

---

Q: yy
A: Yank the line under the cursor

---

Q: 2yy
A: Yank the two lines under the cursor

---

Q: yw
A: Yank the word under the cursor

---

Q: y$
A: Yank to the end of the line under the cursor

---

Q: p
A: Paste after the cursor

---

Q: P
A: Paste before the cursor

---

Q: dd
A: Delete the line under the cursor

---

Q: dw
A: Delete the word under the cursor

---

Q: x
A: Delete the character under the cursor

---

Q: X
A: Delete the character before the cursor

---

Q: xp
A: Transpose the current and next characters

---

Q: D
A: Delete to the end of the line under the cursor

---

Q: s
A: Delete the character under the cursor (disabled to <Nop> by mini.surround)

---

Q: S
A: Delete the line under the cursor and enter INSERT mode

---

Q: . (dot command)
A: Repeats the last change

---

Q: >G
A: increases the indentation from the current line until the end of the file

---

Q: u
A: Undo the last change in NORMAL mode

---

Q: <C-r>
A: Redo the last change in NORMAL mode

---

Q: db
A: Delete backwards from the previous character to the beginning of the current word

---

Q: <C-a>
A: Increment a number under the cursor

---

Q: <C-x>
A: Decrement a number under the cursor

---

Q: g~
a: Swap case in NORMAL mode

---

Q: gu
A: Make lower case in NORMAL mode

---

Q: gU
A: Make upper case in NORMAL mode

---

Q: >
A: Shift selection to the right

---

Q: >>
A: Indent in NORMAL mode

---

Q: <
A: Shift selection to the left

---

Q: <<
A: Unindent in NORMAL mode

---

Q: =
A: Autoindent

---

Q: gg=G
A: Autoindent the entire file

---

Q: !
A: Filter {motion} lines through an external program

---

Q: <C-h>
A: Delete back one character (backspace) in INSERT mode

---

Q: <C-w>
A: Delete back one word in INSERT mode

---

Q: <C-u>
A: Delete back to start of line in INSERT mode

---

Q: <C-[>
A: Switch to NORMAL mode from INSERT mode

---

Q: <C-o> (INSERT mode)
A: Switch to INSERT NORMAL mode

---

Q: <C-r>{register}
A: Inserts text from the register as if it were being typed one character at a time in INSERT mode

---

Q: <C-r><C-p>{register}
A: Inserts text literally and fixes any unindented indentation in INSERT mode

---

Q: <C-r>=
A: Insert the result from the expression register in INSERT mode

---

Q: <C-v>{123}
A: Insert character by decimal code in INSERT mode

---

Q: <C-v>u{1234}
A: Insert character by hexadecimal code in INSERT mode

---

Q: <C-v>{nondigit}
A: Insert nondigit literally in INSERT mode

---

Q: <C-k>{char1}{char2}
A: Insert character represented by {char1}{char2} digraph in INSERT mode

---

Q: gR
A: Triggers Virtual Replace mode (recommended instead of normal Replace mode, fewer surprises)

---
