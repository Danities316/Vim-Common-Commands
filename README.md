# Vim Common Commands

## Modes

- **Normal Mode:** The default mode for navigation and executing commands.  
  - Switch to Normal Mode: Press `Esc`.

- **Insert Mode:** Used for inserting or editing text.  
  - Switch to Insert Mode: Press `i`.
  - To append after the cursor: Press `a`.
  - To insert a new line below the cursor: Press `o`.

- **Visual Mode:** Used for selecting and manipulating text.  
  - Switch to Visual Mode: Press `v`.
  - To select lines: Press `V`.
  - To select a block: Press `Ctrl + V`.

## Navigation

- **Move Cursor:**
  - `h`: Move left.
  - `j`: Move down.
  - `k`: Move up.
  - `l`: Move right.

- **Word Navigation:**
  - `w`: Move to the beginning of the next word.
  - `b`: Move to the beginning of the previous word.
  - `e`: Move to the end of the current word.

- **Line Navigation:**
  - `0` (zero): Move to the beginning of the current line.
  - `$`: Move to the end of the current line.

- **Scrolling:**
  - `Ctrl + u`: Scroll up.
  - `Ctrl + d`: Scroll down.

## Editing

- **Inserting and Appending:**
  - `i`: Insert text before the cursor.
  - `I`: Insert text at the beginning of the line.
  - `a`: Append text after the cursor.
  - `A`: Append text at the end of the line.
  - `o`: Open a new line below the current line.
  - `O`: Open a new line above the current line.

- **Deleting:**
  - `x`: Delete the character under the cursor.
  - `dd`: Delete the current line.
  - `dw`: Delete from the cursor to the end of the current word.
  - `D`: Delete from the cursor to the end of the line.

- **Cut, Copy, and Paste:**
  - `yy`: Yank (copy) the current line.
  - `yw`: Yank from the cursor to the end of the current word.
  - `p`: Paste the yanked text after the cursor.
  - `P`: Paste the yanked text before the cursor.

## Undo and Redo

- `u`: Undo the last change.
- `Ctrl + r`: Redo the last undone change.

## Searching and Replacing

- `/`: Start a forward search.
  - Type the search term and press `Enter`.
  - Press `n` to find the next occurrence.

- `?`: Start a backward search.
  - Type the search term and press `Enter`.
  - Press `N` to find the previous occurrence.

- `:s/old/new/g`: Replace all occurrences of 'old' with 'new' in the current line.
- `:%s/old/new/g`: Replace all occurrences of 'old' with 'new' in the entire file.

## Saving and Exiting

- `:w`: Save the file.
- `:q`: Quit (close) the file.
- `:wq` or `:x`: Save and quit.
- `:q!`: Quit without saving.

## Visual Blocks (for column-wise selection)

- `Ctrl + v`: Start Visual Block mode.
- Move the cursor to select a block.
- Press `d` to delete the selected block or `y` to yank (copy) it.

