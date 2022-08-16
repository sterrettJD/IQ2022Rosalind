# IQ 2022 Rosalind Exercises

## Instructions
### Setting up GitHub keys on your device
1. Log in to [CSEL](https://coding.csel.io/).
2. Check for a ssh key ([instructions](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/checking-for-existing-ssh-keys))
3. If there isn't an ssh key already, generate one ([instructions](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent))
4. Add the ssh key to your GitHub account ([instructions](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account))



### Using the git repo

5. Clone this git repository to your computer. You can do this with the command `git clone` followed by the ssh cloning key found by clicking the green "Code" button at the top right of the repository.
6. Move into this repository with the command `cd IQ2022Rosalind`.
7. On your computer, make a new branch titled "add-[your name]-readme" (you can do this using the `git branch` command)
8. Switch over to that branch (try the `git checkout [branch-to-checkout]` command). You can make sure you're on the right branch by using `git branch`
9. Open the README (on your computer), and add your name to this list:
  - Emma Aldrich
  - Name 2
  - Name 3
  - Name 4
  - Name 5
  - John  
  - Hope

10. Stage your changes to git (`git add README.md`)
11. Commit these changes (`git commit -m "[YOUR COMMIT MESSAGE]"`)
12. Push your changes to GitHub (`git push`; if this is the first time this branch has been pushed, you'll need to use `git push --set-upstream origin add-[your name]-readme`)
13. Open the repository on GitHub, and create a pull request to merge your branch to the main branch. Make a little note to let others know what you hanged :smile:
14. Accept someone else's pull request! Write them a note to let them know they did a good job (or maybe let them know if there's a typo).


### Rosalind
15. Navigate to the [Rosalind website](https://rosalind.info/problems/list-view/).
16. Make an account on Rosalind. 
17. Checkout the main branch, make sure you're on the main branch, and use `git pull` pull any changes.
18. Make a branch for your group, titled "[group name]-DNA-counting". Then, checkout that branch.
19. As a group, write a script titled `DNA-counting.py`, which solves the first problem on the list, and test it. 
20. Commit and push your changes. Make sure to write helpful commit messages, and you can repeat this process multiple times!
21. We'll try to regroup after the first problem, do a short code review, and then merge one version of `DNA-counting.py` to our main branch. 
22. Checkout the main branch, and use `git pull` pull any changes.
23. If time permits, pick another problem that looks fun, and work on that as a group, using the same "branch -> checkout -> write code -> commit -> push -> merge" process.
