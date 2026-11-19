# Linux Exercise – Proof of Completion

**Student:** Luka Kit (`kit`)
**Environment:** GitHub Codespace (`codespaces-82d75e`)

---

## 1. Navigating the system

Commands used: `pwd`, `cd`, `cd ..`, `ls`, `mkdir linux-exercise`, `cd linux-exercise/`

![Navigating the system](images/1-navigating-the-system.png)

---

## 2. Working with files and directories

Commands used: `touch description.txt`, `mkdir test`, `mv description.txt test/`, `ls`, `cd test/`

![Working with files and directories](images/2-working-with-files-and-directories.png)

---

## 3. Moving and copying

Commands used: `mv description.txt my_profile.txt` (rename), `cp my_profile.txt ~/` (copy to home directory)

![Moving and copying](images/3-moving-and-copying.png)

---

## 4. Permissions and Sizes

Commands used: `du -sh` (size of the current directory), `chmod 444 my_profile.txt` (read-only for everyone)

![Permissions and Sizes](images/4-permissions-and-sizes.png)

---

## 5. View System Information

Commands used: `whoami` (username: `kit`), `du -sh ~` (home directory: 24K), `df -h` (available disk space)

![View System Information](images/5-view-system-information.png)

---

## 6. Extra task

Command used: `du -ah ~ | sort -rh | head -n 5`, which lists the 5 largest files and directories in the home directory

![Extra task](images/6-extra-task.png)
