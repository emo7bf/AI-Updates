# 1. Move into the repo you just cloned
cd path/to/your/repo

# 2. Copy or move the files you want to track into this folder
#    (use your OS file manager or commands like cp / mv)
#    Example:
cp ~/Downloads/my_script.py ./           # macOS/Linux
# or
move C:\Users\You\Downloads\my_doc.txt . # Windows

# 3. Tell Git to start tracking the new / changed files
git add .                    # add everything that’s new/modified
# or, to be explicit:
git add my_script.py my_doc.txt

# 4. Record those changes in a local commit
git commit -m "Add initial project files"   # still 100 % offline

# 5. (Optional) Repeat steps 2-4 as often as you like; each commit is local.

# 6. When you regain an internet connection and you’re ready to upload:
git push origin main        # pushes all your local commits to GitHub
