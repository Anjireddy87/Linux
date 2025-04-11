Nice! You've compiled a solid cheat sheet of essential Linux/Unix command-line basics. This is super useful for beginners or even for quick reference. Here's a slightly cleaned-up and organized version (optional), just to make it easier to scan and remember if you're planning to share or keep for future use:

---

## 🔐 User & Permissions

### `whoami`
- Shows current logged-in user.

### `sudo`
- Run commands with superuser privileges.

### `sudo su`
- Switch to root user.
- Exit with `exit`.

---

## 🧼 Terminal Basics

### `clear`
- Clears the terminal screen.

### `history`
- Shows command history.
- `history 10` – shows last 10 commands.
- `!17` – runs command at line 17 in history.
- `history -d 12` – deletes line 12 from history.

### `man <command>`
- Shows manual for a command.
- Example: `man whoami`

---

## 🖥 System Info

### `uname`
- System information.
- `uname -a` – all details.

### `umask`
- Shows default file permission mask.

---

## 📂 Navigation & File Handling

### `pwd`
- Print working directory.

### `cd`
- Change directory.
- Examples:
  - `cd ..` – go up one level.
  - `cd ../..` – go up two levels.
  - `cd ~` – go to home directory.
  - `cd -` – go to previous directory.

### `ls`
- List directory contents.
- Options:
  - `-l` – long listing.
  - `-h` – human-readable sizes.
  - `-a` – show hidden files.
  - `-r` – reverse order.
  - `-t` – sort by time.
  - `-i` – show inode numbers.
  - Example: `ls -lrtha`

---

## 📁 Directory & File Operations

### `mkdir <dir>`
- Create a directory.

### `rm <file>`
- Remove file.
- `rm -rf <dir>` – forcefully remove non-empty directory.

### `rmdir <dir>`
- Remove an empty directory.

### `mv <src> <dest>`
- Move (cut) or rename files/directories.

### `cp <src> <dest>`
- Copy files.

---

## 📄 Working with Files

### `cat`
- View contents of a file.
- `cat > file.txt` – overwrite file.
- `cat >> file.txt` – append to file.
- `cat -n file.txt` – show with line numbers.
- `cat file1 file2 > file3` – merge files.

### `tac file.txt`
- View file contents in reverse.

### `head -n file.txt`
- Show first N lines.

### `tail -n file.txt`
- Show last N lines.
- Combine: `tail file1 -q file2 > file3`

### `more file.txt`
- Paginated view of file content.

### `> filename`
- Clears file content.

---

## 📝 Editing Files

### `nano filename`
- Opens simple editor.

### `vi filename`
- Opens vi editor.
- Press `i` to insert.
- Press `Esc`, then `:wq` to save and quit.

#### Vi Editing Tips:
- `dd` – delete line.
- `dw` – delete word.
- `0` – go to beginning of line.
- `k` – move up.

---

## 🔢 Sorting & Columns

### `sort file.txt`
- Sort contents.

### `sort -r file.txt`
- Reverse sort.

### `sort -k 2 data.txt`
- Sort based on 2nd column.

---

Let me know if you'd like this in a PDF, Markdown, or something printable!
