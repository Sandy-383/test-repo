# test-repo
practice

md(mark down)(changes)


ls(list files)
ls -Force(list all the files including hidden files)

cd(change directory)

untracked(new files that git doens't know yet)

modified(changed the existing file)

staged(file is ready to committed)

unmodified(unchanged)
remote(the one on the internet  (here github))


git push origin main( this tells that we are pushing the changes to the main branch of the origin remote(the cloned repository))


👉 Your GitHub repo already has some commits (like README, license, etc.)
👉 Your local repo doesn’t have those commits
👉 So Git refuses to overwrite them

🔧 Fix (Recommended Way)

Run this:

git pull origin main --rebase


Alternative (Force Push – risky)

If you don’t care about what's on GitHub (like empty README), you can overwrite:

git push -f origin main

PS C:\Users\HP\OneDrive\Desktop\git demo\test-repo\Localrepo> cd .. (this is used to go to the previous folder)

🚀 Real-world analogy

git add . → select all files

git commit -m → save with note

git branch -M main → rename your working line

git push -u origin main → upload + connect to GitHub

workflow (clone->changes->add->commit->push)