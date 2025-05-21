
 
```bash
$ git init
Reinitialized existing Git repository in E:/Code/Bundle 1/.git/

 
$ git add README.md

 
$ git commit -m "first commit"
On branch main
nothing to commit, working tree clean

 
$ git branch -M main

 
$ git remote add origin https://github.com/Anifa-hub/Gym-Git-Exercise-Solutions.git
error: remote origin already exists.

 
$ git push -u origin main
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (11/11), 1.14 KiB | 36.00 KiB/s, done.
Total 11 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Anifa-hub/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

 
$ git add .

 
$ git commit -m "main has been deleted "
[main 0f5929f] main has been deleted
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 main

 
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 271 bytes | 67.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Anifa-hub/Gym-Git-Exercise-Solutions.git
   1e1e671..0f5929f  main -> main -->
   <!-- git branch dev
   <!-- git switch dev --> 
    
<!-- $ git branch test
   $ git branch -d test


    ```bash
    
  229  git status
  230  cd Bundle2/
  231  git add .
  232  git commit -m " I have already merged my branches ft.bundle2 and main"
  233  git push
  234  git checkout ft/service-redesign
  235  git push
  236  git push --set-upstream origin ft/service-redesign
  237  git branch
  238  git checkout -d
  239  git checkout ft/bundle-2
  240  git checkout -b ft/service-redesign
  241  git branch
  242  git checkout -d ft/service-redesign
  243  git branch
  244  git branch -d ft/service-redesign
  245  git branch
  246  git checkout ft/bundle-2
  247  git branch ft/service-redesign
  248  git branch
  249  git checkout ft/service-redesign
  250  git add .
  251  git commit -m "new branch made"
  252  git push
  253  git push --set-upstream origin ft/service-redesign
  254  git pull
  255  git push
  256  git push --set-upstream origin ft/service-redesign
  257  git diff
  258  git merge
  259  git merge origin main
  260  git merge main
  261  git push
  262  clear
  263  git branch ft/team-page
  264  git branch
  265  git checkout ft/team-page
  266  touch team.html
  267  git add .
  268  git commit -m "team.html doc"
  269  git push
  270  git push --set-upstream origin ft/team-page
  271  git checkout main
  272  git branch ft/contact-page
  273  git branch
  274  git checkout ft/team-page
  275  git log
  276  git checkout ft/contact-page
  277  git cherry-pick
  278  git cherry-pick e1603c2d3fdc1dfbc987aae422bdb74423ca3e8c
  279  git add/rm <pathspec>
  280  git add .
  281  git cherry-pick --continue
  282  git commit -m "getting the changes"
  283  git cherry-pick git add/rm <pathspec>
  284  git cherry-pick e1603c2d3fdc1dfbc987aae422bdb74423ca3e8c
  285  git cherry-pick --abort
  286  git cherry-pick e1603c2d3fdc1dfbc987aae422bdb74423ca3e8c
  287  git status
  288  git cherry-pick --continue
  289  git add .
  290  git commit -m "services"
  291  git push
  292  git push --set-upstream origin ft/contact-page
  293  git branch ft/faq-page
  294  git checkout ft/faq-page
  295  touch faq.html
  296  git add .
  297  git commit -m"faq file"
  298  git push
  299  git push --set-upstream origin ft/faq-page
  300  git revert e1603c2d3fdc1dfbc987aae422bdb74423ca3e8c
  301  git add .
  302  git revert --continue
  303  git commit -m "reverting"
  304  git push
  305  git branch ft/home-page-redesign
  306  git checkout main
  307  git add.
  308  git add .
  309  git commit -m "new changes made"
  310  git push
  311  git checkout ft/home-page-redesign
  312  git rebase
  313  git rebase main
  314  git commit -m " no conflit"
  315  git add .
  316  git rebase --continue
  317  git rebase --continue
  318  git add .
  319  git rebase --continue
  320  git add .
  321  git commit -m "reabase"
  322  git push
  323  git push --set-upstream origin ft/home-page-redesign
  324  git checkout main
  326  history 
   ```
