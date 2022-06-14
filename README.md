Repository for practising storing files using Github LFS.

List of commands used in terminal: 

* git init -b main
* git add test_file1.txt 
* git commit -m "first commit"
* git remote origin git@github.com:alex-dickinson/testing_lfs.git
* git remote add origin git@github.com:alex-dickinson/testing_lfs.git
* git remote -v
* git push -u origin main
* git lfs track large_test_file.csv 
* git add .gitattributes
* git add large_test_file.csv 
* git commit -m "adding lfs-tracked file large_test_file.csv"
* git push origin main
* git add .
* git commit -m "updating large file"
* git push origin main
* open test_file1.txt &
* git add .
* git commit -m "adding text to test_file1.txt"
* git push origin main

See 
https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github
for explanation of first few commands
