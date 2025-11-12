# Git note

## 📁 File Types
- **Untracked**: Git dosen't record edit history
- **Tracked**: Use "git add [file name]" to put files into staging area
- **Staged**: Use "git commit -m [Your concise commit message]" to commit files which in staging area.
- **Committ**: Files have been saved into repository history.

### 🔼 Update Files to GitHub
- Use "git push" command uploading local files to GitHub.

---

## 🕓 Review History
- **Full history**: "git log"
- **Simplify version**: "got log --oneline"

---

## 🔍 Check Differences
- "git diff" [file ID]

---

## Restore file
- "git checkout" [file ID] (the version you want) -- [file name]
- "git reset" --hard [files ID] (the version you want) [⚠️ **Warning**: Be careful while using this command, it'll make all the files restore to that ID history version and it's **irreversible**]

---

## Status
- **A** - added
- **M** - modified

---

## 🗑️ Delete files
- Even if we delete one of the files, it still needs to be added into storage area and use commit command to let git history know that we delete that file. Otherwise the file which is deleted woulf keep stay in the  working tree.
## The files i don't want to record the history
- Using ".gitignore" folder to place these files. Input the names of files in this folder then git would ignore it.
## Git vs. GitHub
- Git is a version control system. GitHub is a cloud platform for storing, sharing and collaborating on Git repositories.
update files from git to Github - use "git push" command
