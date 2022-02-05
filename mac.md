# Setting Up Your Computer

Welcome to day 1 at BloomTech, today we are going to spend time setting up your computer and learning the tools that you will be using to complete this program. Just like day 1 at a job, you will need to get your environment set up to build and run your code. Complete the set up tasks below and then get started on the research questions. Once you have finished check out the submission instructions in the `README.md` file to turn in your assignment for the day. 

## Set Up Tasks 
1. [ ] [Download xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12) - these are your developer tools for mac 
2. [ ] sign up for a [GitHub account](https://github.com/join) - please use a professional username. We recommending using your `firstname` `lastname`
3. [ ] [Set up your SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) - GitHub uses SSH to keep their files secure. You will need to set up one SSH key for every computer that you want to access your GitHub account on. Please ensure you go through all of the steps to generate a new key, add a new key and test your connection.
4. [ ] [Download Zoom](https://zoom.us/download) - make sure your zoom display name is your `first name` `last name`
5. [ ] [Download Slack](https://slack.com/help/articles/207677868-Download-Slack-for-Mac) - make sure your slack display name is your `first name` `last name` 
6. [ ] [Download VS code](https://code.visualstudio.com/download) - this will be the tool you use to write all of your code. We recommend installing the following extensions: 
- [ES Lint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
7. [ ] [Download Node.JS](https://nodejs.org/en/) - Please download the latest stable version. We will be using Node.JS to run the tests in all of our javaScript assignments. Test driven development is a common practice in the world of web dev. You can read more about it [here](https://www.freecodecamp.org/news/test-driven-development-what-it-is-and-what-it-is-not-41fa6bca02a2/) 
8. [ ] Sign up for a free [codepen account](https://codepen.io/accounts/signup/user/free)
9. [ ] Sign up for a free account on [Lucid Chart](https://www.lucidchart.com/pages/landing?utm_source=google&utm_medium=cpc&utm_campaign[…]tTwOoXp_lCeLTC97pikTFa5cE58FWHwjjpTSGsGPRqR2AAaAh-MEALw_wcB)

## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You can type your answer below the questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en) doc short for documentation are the instructions on how to use a languge, or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your google skills. 

1. What is git? What is the difference between git and GitHub?

  Git is an open source distributed version control system. It is software for tracking changes in any set of files over time. What makes git open source is that its source code is made freely available and may be redistributed or modified. What makes git distributed is that these files and all their versions can exist in many machines at once.
  GitHub, on the other hand, is a cloud-based hosting service that lets you manage files which are version-controlled by git. It is also a great tool for collaboration amongst developers.


2. Why do we create a branch? 

  A branch is a separate line of development. We need branching because it isolates our work from the rest of our team members. We can work on new features and bug fixes without interfering with other people’s code and the main/master branch. 


3. What is the purpose of a pull request? 

  Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch. Pull requests allow multiple developers to collaborate and communicate more effectively.


4. What is the command you can use to switch between branches? For example you are working on a feature branch and you want to switch back to main. 

  To switch to main branch: git checkout main
  To switch to a different branch: git checkout <existing_branch>
  To switch to a new branch: git checkout -b <new_branch>


5. Explain the difference between `git fetch`, `git merge` and `git pull` what does each command do? 

  Git fetch downloads remote code from a repository's remote URL to your local computer. This code is saved as remote branches separate from the local branches in our repo. This allows us to review the commits before integrating them in our local working branches. Git merge merges that code into our local branch. Git pull does a git fetch followed by a git merge all in one command. 


6. What is a merge conflict? How do you resolve a merge conflict? 

  Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge. A competing commit is when two individuals make different changes to the same line of the same file on different branches in your Git repository. 
  To resolve a merge conflict, we must manually edit the conflicted file to select the changes that we want to keep in the final merge. We also have tools to help us such as the conflict editor in GitHub and git command line tools.