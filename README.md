mkdir new-project  
cd new-project  
git init  
cat "init" > README.md  
git add README.md  
git commit -m "init"
git branch -M main 
git checkout -b development
nano README.md
git add .
git commit -m "Add instruction to README.md"
git checkout main
git merge development
git remote add origin https://github.com/vit-um/new-project.git
git push
