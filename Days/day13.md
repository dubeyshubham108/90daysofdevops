# Day 13 - Git Branching 

<p align="center">
   <img src="https://github.com/dubeyshubham786/90daysofdevops/blob/main/images/git%20branching.png" alt="Git Branching"/>
   </p>
   
   The diagram shows two isolated lines of development. When created a new branch data of existing branch is copied to new branch. 
 Some points on branching:
 1. You can create any number of branches.
 2. Changes are personal to that particular branch.
 3. Default branch is Master.
 4. This concept is useful for parallel development.
 5. After done with code, Merge other branches with Master.
 6. Files created in workspace will be visible in any of the branch workspace untill you commit. Once you commi, then that files belongs to that particular branch.
 7. When created new branch, Data of existing branch is copied to new branch.

## Git command for Branching 
| Command | Description |
| ------- | ----------- |
| `git branch` | Show in which branch you are present |
| `git checkout branch1` | To move to branch1 |
| `git branch -d branch1` | To delete branch1 |
   
## Merge 
1. We use pulling mechanism to merge branches.
2. You can't merge branches of diferent repositories.

| Command | Description |
| ------- | ----------- |
| `git log` | To verify the merge |
| `git push origin master` | To push to control repo like github |
   
   ## Resources
   
  1. <a href="https://www.atlassian.com/git/tutorials/using-branches/git-merge">Git Branching blog</a>
  2. <a href="https://www.youtube.com/watch?v=4MtsFAArXVU&list=PLBGx66SQNZ8aPsFDwb79JrS2KQBTIZo10&index=15&ab_channel=TechnicalGuftgu">Technical Guftgu youtube video</a>




