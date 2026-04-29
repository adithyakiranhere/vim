🧠 Vim Training – Session 1
Basics: Modes, Movement, Insert, Save/Quit

Welcome to your first Vim/Neovim practice session. This README is designed to help you build strong fundamentals through hands-on exercises.

📌 Exercise 1: Moving Around

Use the following keys to navigate:

h → move left
j → move down
k → move up
l → move right
Practice:

Move through the text and land on each *:

    *         *
        *
  *       *       *
      *         *

⚠️ Do NOT use arrow keys — train muscle memory!

✍️ Exercise 2: Entering Insert Mode
Steps:
Move cursor using h/j/k/l
Press i → enter INSERT mode
Type missing word
Press Esc → return to NORMAL mode
Fill in the blanks:
The capital of India is _____.
Neovim is a modern version of _____.
The four main modes are Normal, Insert, Visual, and _____.
The key 'j' moves the cursor _____.
To save a file, type :_____ in command mode.
⌨️ Exercise 3: Insert Mode Variations

Practice different ways to enter insert mode:

Use 'A' to append text at the END of this line -->
<-- Use 'I' to insert text at the START of this line
Use 'o' to open a new line BELOW this line
Use 'O' to open a new line ABOVE this line
Use 'a' to append text AFTER the cursor on this line
💾 Exercise 4: Saving and Quitting

Try these commands:

Command	Description
:w	Save file
:q	Quit (fails if unsaved changes)
:wq	Save and quit
:q!	Quit without saving
ZZ	Save & quit (shortcut)
ZQ	Quit without saving (shortcut)

🔁 Reopen file:

nvim session1_practice.txt
👀 Exercise 5: Mode Awareness

Check bottom-left of screen:

Mode	Indicator
Insert	-- INSERT --
Visual	-- VISUAL --
Normal	(no label)
Practice switching modes:
i → Esc → a → Esc → o → Esc → I → Esc → A → Esc → O → Esc

🔁 Repeat 10 times until automatic.

🧭 Exercise 6: The Golden Rule

Always return to NORMAL mode when done typing.

Think of modes like this:
Mode	Meaning
Normal	Standing (ready to act)
Insert	Sitting to write
Visual	Highlighting text
Command	Giving instructions

📊 Goal:
Spend 80% of your time in Normal mode

🎉 Congratulations!

You’ve completed Session 1.
