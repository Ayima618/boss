echo "# boss" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Ayima618/boss.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/Ayima618/boss.git
git branch -M main
git push -u origin main



===== AFTER SET UP (DURING UPDATE) =====
git add .
git commit -m "your commit message"   
git push -u origin main  