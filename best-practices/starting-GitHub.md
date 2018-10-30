# Best practices

## How to start on GitHub & OpenSource pull requests

Sometimes is hard to know how to start in GitHub since many people has different ways to do it. Your friends could suggest you start directly and do not get much documentation to avoid information overhead. But don't get worry you could start just HERE.



* Check the GitHub guides

  These guides are amazing explained and have images for every step.

  [GitHub guides](https://guides.github.com/)

* Look out the GitHub help

    This is a wonderful list of almost everything you can do or ask when you're starting, it has concepts and well explained steps for almost everything. Do not hesitate and check it.

    [GitHub help](https://help.github.com/)

* Try Git

    The Git initial mastering is on the Try Git page. You could practice every git command advised by the page itself, so you'll never lose an step while you're trying git commands.

    [Try Git](https://try.github.io/levels/1/challenges/13)

* Pull request steps for open source contributions
  - Do a fork of the project you want to contribute
  - Clone your repository to your local machine  
  ```
   > git clone [remote-repo-url]
  ```
  - Create a new branch to start doing challenges
  ```
   > git branch [branch-name]
  ```
  - Checkout the new branch
  ```
   > git checkout [branch-name]
  ```
  - DO your changes
  - Once you have tour changes done, add them
  ```
   > git add [files]
  ```
  - Now, a commit
  ```
   > git commit -m "[message]"
  ```
  - PUSH to your remote repository
  ```
   > git push [alias] [branch]
  ```
  - On github do the suggested compare & pull request
  - Add a Title and Description. Hint, if you're solving an issue you could add the number of the issue using #[issue-number] to refer that issue.
  - Click **pull request**

### YOU ROCK in OPEN SOURCE :sunglasses: :octocat:


* Other commands

```
 > git blame
```
- Show what revision and author last modified each line of a file


```
 > git rebase
```
- Rebasing is the process of moving or combining a sequence of commits to a new base commit.
- Rebasing is most useful and easily visualized in the context of a feature branching workflow.




- **Commit early and often**

- Git only takes full responsibility for your data when you commit. If you fail to commit and then do something poorly thought out, you can run into trouble. Additionally, having periodic checkpoints means that you can understand how you broke something.
