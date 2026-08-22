# Documentation Git Report
```
PS C:\Users\Renz\Software-Versioning-Lab> git checkout -b feature-update
Switched to a new branch 'feature-update'
PS C:\Users\Renz\Software-Versioning-Lab> git add .
PS C:\Users\Renz\Software-Versioning-Lab> git commit -m "Updated README with laboratory information"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Renz@LAPTOP-IJBA0QOI.(none)')
PS C:\Users\Renz\Software-Versioning-Lab>  git config --global user.email "renzraphaeldestua@gmail.com" 
PS C:\Users\Renz\Software-Versioning-Lab> git push origin feature-update
info: please complete authentication in your browser...
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'feature-update' on GitHub by visiting:
remote:      https://github.com/renzraphaeldestua-byte/Software-Versioning-Lab/pull/new/feature-update
remote: 
To https://github.com/renzraphaeldestua-byte/Software-Versioning-Lab.git
 * [new branch]      feature-update -> feature-update
PS C:\Users\Renz\Software-Versioning-Lab> git status
On branch feature-update
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

PS C:\Users\Renz\Software-Versioning-Lab> git commit -m "Updated README with laboratory information"
[feature-update b91685b] Updated README with laboratory information
 1 file changed, 5 insertions(+), 1 deletion(-)
PS C:\Users\Renz\Software-Versioning-Lab> git push origin feature-update
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 445 bytes | 445.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/renzraphaeldestua-byte/Software-Versioning-Lab.git
   0eeeab1..b91685b  feature-update -> feature-update
```