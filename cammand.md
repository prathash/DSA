echo # DSA >> README.md

git init

git add README.md

git commit -m first commit

git branch -M main

git remote add origin git@github.com:prathash/DSA.git

git push -u origin main

git add . → Stage changed files.
git commit -m "message" → Save a snapshot locally.
git push origin main → Upload commits to GitHub.

for setup
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/<public key>
ssh -T git@github.com
