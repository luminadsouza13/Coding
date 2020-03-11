git init 
- create .git directory in current , unversion directory 
- here example is .git directory is created under LearningJavaSkills
- this is always first command to execute if its git versioned directory 
- .git comtains other subdirectory says objects , referemnces and template files
- head is one of the subdirectory that points to last commit 
   - for example if you accidentally deleted the file you can always revert using below commands
     - git rev-list -n 1 HEAD => gives hash code encrypted value
     - git checkout <hashcode> gives you the details what versions were checked out or last version
   

git add <files or directories>

git commit -m "<Message>"



