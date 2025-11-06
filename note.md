# File types
Untracked - Git dosen't record edit history
Tracked - use "git add [file name]' to put files into storage area
Staged - use "git commit -m [Your concise commit message]" add files
Committ
# How to review the history
"git log" or "got log --oneline"(simplify version)
# Check difference: "git diff" + file ID
# Restore file
"git checkout" + file ID (the version you want) -- file name
"git reset" --hard + files ID (the version you want) [warning: Be careful while using this command, it'll make all the files restore to that ID history version]
# Status
A - added
M - files have changed
# Delete files
Even if we delete one of the files, it still needs to be added into storage area and use commit command to let git history know that we delete that file. Otherwise the file which is deleted woulf keep stay in the  working tree.
# The files i don't want to record the history
Using ".gitignore" folder to place these files. Input the names of files in this folder then git would ignore it.