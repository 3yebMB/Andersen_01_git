0. cd ./Documents/Andersen/Andersen_01_git
1. git init
2. git config user.name Michael
3. git config user.email michael@andersen.net
4. git config --global core.excludesFile ~/.gitignore
5. *add ".idea" to global .gitignore
4. *Create project in AS
5. git add .
6. git commit -m 'init: empty Android Studio project'
10. git show 253c6dc --pretty=fuller
11. git remote add origin https://github.com/3yebMB/Andersen_01_git.git
12. git push -u origin master
13. *Create README.md file and put history fo commands into it
--new branch--
14. git branch feature/branch_01
15. git checkout feature/branch_01
16. *edit "AndroidManifest.xml" files
17. git commit -am 'add: permission to AndroidManifest.xml'
18. *Edit "MainActivity.kt"
19. git commit -am ''update: class MainActivity.kt'
20. *Edit "build.gradle" 
21. git add .
22. git commit -m 'update: min version SDK to 23'
23. git add README.md
24. git commit -m 'update: README.md'
25. git commit -am 'add: commands history to README.md'
26. git checkout master
27. git merge feature/branch_01