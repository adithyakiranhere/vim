🧠 Vim Training Guide
🚀 Sessions 1 & 2 – Core Navigation & Editing Skills

This guide helps you master Vim step by step with hands-on exercises.
Follow actively inside nvim for best results.

📘 SESSION 1: Basics
Modes, Movement, Insert, Save/Quit
📌 Exercise 1: Moving Around

Use:

h ← left
j ↓ down
k ↑ up
l → right
    *         *
        *
  *       *       *
      *         *

👉 Land on each * without arrow keys.

✍️ Exercise 2: Insert Mode

Steps:

Move with h/j/k/l
Press i
Type text
Press Esc
The capital of India is _____.
Neovim is a modern version of _____.
The four main modes are Normal, Insert, Visual, and _____.
The key 'j' moves the cursor _____.
To save a file, type :_____ in command mode.
⌨️ Exercise 3: Insert Variants
Use 'A' to append text at the END of this line -->
<-- Use 'I' to insert text at the START of this line
Use 'o' to open a new line BELOW this line
Use 'O' to open a new line ABOVE this line
Use 'a' to append text AFTER the cursor on this line
💾 Exercise 4: Save & Quit
Command	Action
:w	Save
:q	Quit
:wq	Save & Quit
:q!	Force Quit
ZZ	Save & Quit
ZQ	Quit without saving
nvim session1_practice.txt
👀 Exercise 5: Modes
Mode	Indicator
Insert	-- INSERT --
Visual	-- VISUAL --
Normal	(none)

Practice:

i → Esc → a → Esc → o → Esc → I → Esc → A → Esc → O → Esc
🧭 Exercise 6: Golden Rule

Always return to NORMAL mode.

Normal = Control
Insert = Typing
Visual = Selecting
Command = Executing

🎯 Spend 80% time in Normal mode

📗 SESSION 2: Movement Mastery
Word, Line, Screen Navigation
🔤 Exercise 1: Word Movement

Commands:

w → next word
b → previous word
e → end of word
The quick brown fox jumps over the lazy dog near the river.
🔠 Exercise 2: word vs WORD
hello-world foo.bar test_name some-thing else.more stuff
w → stops at punctuation
W → skips punctuation
📏 Exercise 3: Line Navigation

Commands:

0 → start of line
^ → first non-blank
$ → end of line
g_ → last non-blank
    indented line with leading spaces and trailing spaces here    
        another deeply indented line of code goes here
this line starts at column 1 with no indentation at all here
    int x = 42;  // notice the difference between 0 and ^

👉 Practice: 0 → ^ → $ → g_

🔢 Exercise 4: Vertical Jumps
gg → top
G → bottom
50G → line 50
:100 → line 100
🔁 Exercise 5: Counts
one two three four five six seven eight nine ten eleven twelve

Examples:

3w
5w
2b
4e
📚 Exercise 6: Paragraph Jumps
{ → previous paragraph
} → next paragraph
🔗 Exercise 7: Bracket Matching

Use %:

function example() {
    if (condition) {
        return [1, 2, 3];
    }
}

array = [one, two, [nested, list], four]
result = (a + b) * (c - d)
🖥️ Exercise 8: Screen Movement
H → top of screen
M → middle
L → bottom
Ctrl-d → half down
Ctrl-u → half up
Ctrl-f → full down
Ctrl-b → full up
zz → center
🔀 Exercise 9: Combo Practice
apple banana cherry date elderberry fig grape honeydew kiwi lemon

Tasks:

2w → cherry
8w → kiwi
8b → back to apple
$ → end
0 → start
⚡ Exercise 10: Speed Drill

Navigate WITHOUT h j k l:

The cat [TARGET] sat on the mat. The dog [TARGET] ran in
the park. The bird [TARGET] flew over the trees. The fish
[TARGET] swam in the pond. The horse [TARGET] galloped
across the field with great [TARGET] speed and energy.
📜 Extra Lines (for jumping)
line 80
line 81
...
line 100  <-- try :100 or 100G
...
line 110
🎉 Progress

✅ Session 1 Completed
✅ Session 2 Completed
