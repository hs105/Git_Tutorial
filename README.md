# Git_Tutorial


## Use Cases
After adding ignored file patterns into the .gitignore file, you want to see it make an effect: on github should now delete these files. The solution is 
```
git rm -r --cached .
git commit -am "deleting cached"
git push -u origin master
git add .
git commit -am "now repository should reflect the new .gitignore file"
git push -u origin master
```

