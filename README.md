![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Svendolin/All-about-GIT?style=for-the-badge) ![GitHub contributors](https://img.shields.io/github/contributors/svendolin/All-about-GIT?style=for-the-badge) ![GitHub forks](https://img.shields.io/github/forks/Svendolin/All-about-GIT?color=pink&style=for-the-badge) ![GitHub last commit](https://img.shields.io/github/last-commit/Svendolin/All-about-GIT?style=for-the-badge) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/Svendolin/All-about-GIT?color=yellow&style=for-the-badge)


***
<img align="left" alt="git logo" width="35px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" /> 

<img align="left" alt="git logo" width="35px" style="margin-left:10px" src="https://cdn-icons-png.flaticon.com/512/5968/5968896.png" /> 

<img align="left" alt="JavaScript" width="35px" style="margin-left:10px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/Github-desktop-logo-symbol.svg/1200px-Github-desktop-logo-symbol.svg.png" /> 

<img align="left" alt="JavaScript" width="35px" style="margin-left:10px" src="https://github.githubassets.com/images/modules/site/copilot/copilot.png" /> 

# &nbsp;- ALL ABOUT GIT / GITHUB / GITHUB DESKTOP / GITHUB COPILOT - ✔

This "All-about-GIT"-repository catches up its focus on all the USEFUL GIT COMMANDS I did during my projects through the years as a **SAE-Web Development** student with exercise lessons every week as well as tutorial videos on _Youtube_.

<br />

👍GOOD TO KNOW:🤗

=> `GIT` is a free and open source distributed version control system (TOOL) designed to handle everything from small to very large projects.

=> `Terminal` is an electronic hardware device that can be used for entering data (transcribing data) from a computer or a computing system. It's an interface on our computer to type in text commands.
* In Visual Studio Code you can either click on "Terminal" > "New Terminal" (CTRL + SHIFT + ö) to OPEN A NEW TERMINAL
* or you can right-click on your explorer file and OPEN IN INTEGRATED TERMINAL (that means you open a terminal with the desired path)

=> `CLI` is known as Command Line Interface. Some programs require to interact with them via text commands (typing in some explicit text to run or make changes to the application).

=> `GITHUB` is a network-based version management service (WEBSITE TO HOST) for software development projects. It was named after the version management system Git.

=> `VERSION CONTROL` is basicall what we do with GIT. We track our code changes as programmer and save an initial code in GIT until we update or undo some changes to it. After all we can control and see the whole history of changes.

=> `.git` stores all of the files that saves the history of your project from commit to commit. It's a hidden folder in your project folder. With "$ ls -la" you can see all the hidden files and folders in your project folder.

=> `.gitignore` is a file that tells Git which files (or patterns) it should ignore. It's a hidden file in your project folder. With `"$ ls -la"` you can see all the hidden files and folders in your project folder. Create a new file called .gitignore and write in the files you want to ignore.

=> `Q` cleans the actual command of the terminal while `CTRL + C` stops the process and `$ git clear` clears the terminal from all the text.

=> `TAB` is your friend! If you type in a command and press TAB, it will autocomplete the command for you. If you press TAB twice, it will show you all the possible commands that start with the letters you typed in.

        
<br />
<br />

***
## Technologies and Installation ✅
***

GIT BASH (for Windows) - INSTALLATION:
* (BASIC variant to pull, add, commit, push and merge code to your projects)
* https://gitforwindows.org/

GITHUB DESKTOP (for Windows) - INSTALLATION:
* (SIMPLIFIED variant to pull, add, commit, push and merge code to your projects)
* Explenations futher down below!
* https://desktop.github.com/

GITHUB COPILOT (for Windows) - INSTALLATION:
* (AI pair programmer which uses OpenAI Codex to suggest code and entire functions)
* You can use natural language (either write it directly or describe it as a comment) to compile it
* https://github.com/features/copilot (download)
* https://docs.github.com/en/copilot (documentations)



<br />
<br />

***
<img align="left" alt="JavaScript" width="35px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" /> 

## &nbsp;How to START: ✅ (Create a repo and initialize it in git)
***
| STEP | COMMAND | EFFECT  | 
|:--------------| :--------------| :--------------|
|1| https://github.com/ | Create repository > Add description and tags > Copy HTTPS of your repo (#) |
|2| Create Folder | Open with VSC to start working > Open your Terminal (look that it says "BASH") |
|3| $ git init | Initialize git in the terminal (click the arrow beside the + to see if "BASH" is default) |
|4| $ git config user.name "" | OPTIONAL: configurate the terminal with your name (useful if you work on different computers) |
|5| $ git config user.email "" | OPTIONAL: configurate the terminal with your email (useful if you work on different computers) |
|6| readme.md | Write a readme.md in your explorer of VSC as a first commit to make |
|7| $ git add readme.md | ADD your change to the git (ready to track in GIT) - Stages the changes to your index |
|8| $ git commit -m "first commit" | COMMIT your first change |
|9| $ git branch -m main | OPTIONAL: Change the branch name from master to main |
|10| $ git remote add origin (#) | REMOTE them with the github HTTPS link  |
|11| $ git push -u origin master | PUSH your changes - (If you did step 9, master would be main) -u means "set upstream" |
|12| $ git status | STATUS check to make sure everything went right (shows what was updated, deleted etc but havent been saved in a commit yet) |
|13| $ git log | LOG shows your structure |
|14| Now its time to make some changes: | (...)

<br />
<br />

***
<img align="left" alt="JavaScript" width="35px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" /> 

## &nbsp;How to UPDATE: ✅ (Successfully commit changes)
***


| STEP | COMMAND | EFFECT  | 
|:--------------| :--------------| :--------------|
|1| FOLDER CHECK | Check if you are in the right output folder where git has been initialized |
|2| $ cd ../ or: dollar ld | CHANGE directory or SHOW the CONTENT of your directoy to adjust your folder output if necessary |
|3| $ git pull | CHECK of undone changes (conflicts) and decide which change you want to make if necessary. A pull request will synchronise your remote data (code review before we merge changes in) |
|4| $ git add . | ADD what you changed (ready to track in GIT) The "." means "ADD ALL FILES", but you can also name an exact file from the explorer if you wish like "add index.html" |
|5| $ git commit -m "" | COMMIT a message to say what you changed (Write a desctiption between "", like what and why btw you can add a second one for the description) - It saves your files in GIT |
|6| $ git push -u origin master | PUSH your changes (means upload GIT commits to a remote repository like GITHUB) - (btw master if your branch is named "master", otherwhise say the right name) |
|7| $ git status | STATUS check to make sure everything went right |


<img text-align="center" alt="Github" width="" src="https://w3cschoool.com/public/file/Git/git-pull2.png" /> 

<br />

| TERM | MEANING  | 
|:--------------| :--------------|
| Workspace| Your local computer > "adds" the changes to the index > "commits" the changes with a message to your repo |
| Index | Stages changes: The added changes will be stored in a personal index "lokaler Zwischenspeicher" to make it ready for tracking the changes to the Repo (your project)  |
| Repository| Project / Folder place "Ablage bzw Schublade / Aufbewahrungsort" where your project is kept > "push" the changes to the remote |
| Remote| Remote Repository like GITHUB where your projects are hosted / placed on an external server (like Dropbox, but for Code) |
| PULL | Download change from the REMOTE (Github) to your WORKSPACE (local machine) which is the opposite of push. It's also a CHECK of undone changes (conflicts) A pull request will synchronise your remote data (code review before we merge changes in)  |
| PUSH | Upload GIT commits from your REPOSITORY to a REMOTE which is the opposite of pull |
| CLONE | Clone a repository (Project) from a REMOTE (hosted hub) to your WORKSPACE (local machine) |
| MERGE | Joins two or more development histories together. It is used by the git pull command to incorporate changes from a different repository and can be used by hand to resolve conflicts. |

<br />
<br />

***
<img align="left" alt="JavaScript" width="35px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" /> 

## &nbsp;GIT BRANCHING: How to MAKE, ADD + PUSH and MERGE BRANCHES: ✅ (Working non-destructive)
***
**EASY WAY WITH TERMINAL IN VSC (step 1 - 5), GITHUB INTERFACE (step 6 - 7.1) AND BACK IN VSC for (step 8 - 10)**
* Step 1 to 5.1: Create, add, commit and push your code changes into a new branch locally in VSC
* Step 6 to 7.1: Create a pull request to merge your branch into the main branch (master)
* Step 8 to 10: Update your master branch locally on your workspace by pulling the changes from the remote master branch and delete the feature branch.

| STEP | COMMAND | EFFECT  | 
|:--------------| :--------------| :--------------|
|1| $ git branch | SHOWS how many branches are made in this project (green coloured branch name and *) |
|2| $ git checkout -b feature | CREATES a new branch which is called "feature" and also CHECKOUTS to your new branch (you switch over from your master branch to your "feature" branch which is independant to your other branches)  |
|2.1| $ git checkout master | OPTIONAL: CHECKOUTS back to your master branch. TO CONTINUE: Switch back to feature with "$ git checkout feature" |
|2.2| $ git status | OPTIONAL: STATUS check to make sure everything went right (and if there way something modified) |
|3| $ git add . | ADD what you changed (. means ALL, but you can also name an exact file from the explorer) Note: your changes will be only added (and also SEEN) to your feature branch |
|4| $ git commit -m "" | COMMIT to say what you changed (Write a desctiption between "") Note: This will be ONLY commited and saved to your feature branch |
|5| $ git push -u origin feature | PUSHES your changes from the repository to the GITHUB remote. BUT Github will now inform you about COMPARING and PULLING the changes => Code from FEATURE BRANCH is ready to be pulled into the MASTER BRANCH |
|5.1| "push command" | You can push as many changes if you want to your feature branch by repeating step 3 to 5 after you made some coding changes |
|6| GITHUB Interface => Able to Merge | Go to your repository on GITHUB and open a pull request > compare the feautre branch with the base branch (in this case "master") and be sure that "able to merge" is checked |
|6.1| Conversation / Commits and Checks | OPTIONAL: You can also check the conversation, commits, checks and "files changed" sections (also comment lines and resolve conversations) before you merge it |
|7| Merge Pull Request | Click the button and confirm it > PR (Pull Request) should be sucessfully merged! |
|7.1| Delete branch | OPTIONAL: Github will inform you that pull request is successfully merged and closed so the feature branch can be safely deleted OR do it at the end with step 10 |
|8| $ git checkout master | CHECKOUTS back to your master branch to see that your local changes from the master branch haven't been updated yet |
|9| $ git pull | PULLS the changes from the remote repository to your local machine (workspace) |
|10| $ git branch -d feature | DELETES the feature branch |

<br>
<br>

**REGULAR FAST-FORWARD WAY WITH TERMINAL USE IN VSC:**
* Step 1 to 4.1: Create, add and commit your code changes into a new feature branch
* Step 5 to 7: Merge, pull and push your feature branch into the master branch (fast-forward from your master branch)


| STEP | COMMAND | EFFECT  | 
|:--------------| :--------------| :--------------|
|1| $ git branch | SHOWS how many branches are made in this project (green coloured branch name and *) |
|2| $ git checkout -b feature | CREATES a new branch which is called "feature" and also CHECKOUTS to your new branch (you switch over from your master branch to your "feature" branch which is independant to your other branches)  |
|2.1| $ git checkout master | OPTIONAL: CHECKOUTS to your master branch |
|2.2| $ git checkout feature | SWITCHES BACK to feature with "$ git checkout feature" |
|2.3| $ git status | OPTIONAL: STATUS check to make sure everything went right (and if there way something modified) |
|3| $ git add . | ADD what you changed (. means ALL, but you can also name an exact file from the explorer) Note: your changes will be only added (and also SEEN) to your feature branch |
|4| $ git commit -m "" | COMMIT to say what you changed (Write a desctiption between "") Note: This will be ONLY commited and saved to your feature branch |
|4.1| $ git diff master | SHOWS MASTER vs FEATURE changes: which files got a change, so basically what's new and what's old |
|5| $ git checkout master | Go back to your master branch. Now you'll stay there! |
|6| $ git merge feature | FAST FORWARD: JOIN the changes from the feature branch into master branch |
|6.1| $ git pull | OPTIONAL: If there have been made some possible changes in between (especially if you have pushed some changes before). It PULLS the Changes from the remote (Github) to your local machine (Workspace) to show you the conflict (current vs incoming change) - Decide if you want to accept the current change, the incoming change or both |
|7| $ git push -u origin master | Push your desired changes from your repository to the remote (Github) / Thats actually the part where you synchronize everything together to be up todate on remote as well as on your workspace |

<br>

**NOTE FOR "STAGING":**

*If you have made changes to the same line of code in both the Feature Branch as well as the Master Branch, you can no longer switch from the Master Branch to the feauture branch! ADD and COMMIT on the master first > Checkout to your feature branch > check the changes with "git diff master" in feature branch and stay there > Keep your personal feature branch upt to date by "$ git merge master" > Merge Conflict (current = changes from feature branch, the branch where you lastly checkouted btw VS Incoming changes from the master branch) > Then do add and commit again*

<br>
<br>


<img text-align="center" alt="Github" width="" src="https://docs.wavemaker.com/learn/assets/branching-model.png" />

* **MASTER BRANCH**: Your main working tree. It's the default branch when you create a repository. You can think of it as the "production" branch. It's where you MERGE changes from other branches. 

* **FEATURE BRANCH**: A branch that you create to work on a new feature. It's where you ADD changes to your project. All changes are made, added, committed and pushed in a feature branch until you MERGE them into the master branch when they're ready.

* **MERGE**: means to combine the changes from one branch into another branch. You can also think of it as a "release" branch. 
Usually you merge a feature branch (in this example its called "feature") into the master branch.

* **BUGFIX BRANCH**: A branch that you create to fix a bug (like a hot fix) which is done seperately on its own branch. But GENERALLY this branch is not needed anymore and can be deleted.


<br />
<br />

***

<img align="left" alt="JavaScript" width="35px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" /> 

## &nbsp;How to UNDO MERGE if you accidentally made a mistake: ❌
***

* **IMPORTANT GENERAL NOTE**: Merge is only the first command. After the merge, it needs an add, commit and push as usual. Your last commit is super important for the following case 0
* Please note: Step 1.1 is going to be used if you want to make a reset on a CERTAIN STAGE!
* CHECK OUT the "commits" section in your github repo to get an overview of the amount of commits you've done in the chosen project. Each commit has its own ID-Number which is important for the upcomig process:
* 🔴-Lines show deleted content in this commit
* 🟢-Lines show added content in this commit
* ⚪-Lines show that these parts weren't changed through this commit

| STEP | COMMAND | EFFECT  | 
|:--------------| :--------------| :--------------|
|0| $ git reset --merge HEAD~1 | Reverts to the last commit in your repository you've made (refers to the current state as it was right before)  |



| STEP | COMMAND | EFFECT  | 
|:--------------| :--------------| :--------------|
|1| $ git reset --merge a9fdeb5 | This command resets our repository to the state it was at in the a9fdeb5 commit on the master branch. NOTE: Use YOUR ID at step 2|
|2| REPLACE a9fdeb5 with the ID  | Github > Repository (of your project) > click "commits" > Copy the ID of the state you want > paste it at STEP 1 and hit ENTER - Now your repo is staged based on your selcted ID |
|3| Add > commit > push  | Process as usual |


<br />
<br />

***
<img align="left" alt="JavaScript" width="35px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" /> 

## &nbsp;How to DELETE BRANCHES: ❌
***
| STEP | COMMAND | EFFECT  | 
|:--------------| :--------------| :--------------|
|1| $ git branch -d feature | CAREFUL: Deletes your "feature" branch  |


<br />
<br />

***
<img align="left" alt="JavaScript" width="35px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" /> 

## &nbsp;How to CLONE a repository (a repo hosted from someone else to your local machine)👨🏼‍🤝‍👨🏻
***

* If you want to get a copy of an existing Git repository — for example, a project you’d like to contribute to — the command you need is git clone.

* Git receives a full copy of nearly all data that the server has. Every version of every file for the history of the project is pulled down by default when you run git clone.

* In fact, if your server disk gets corrupted, you can often use nearly any of the clones on any client to set the server back to the state it was in when it was cloned

* **It is therefore not necessary to download the repository as a ZIP file, then unpack it and paste it into the code editor.**


| STEP | COMMAND | EFFECT  | 
|:--------------| :--------------| :--------------|
|0| First Step | Create a new folder > Open VSC > Open your Terminal|
|1| $ git clone (#) | (#) Copy the "https:Link" of the desired Repository when you click on the "code"-button (The third button beside "Go to file" and "Add file") and paste it behind the command |

<br />
<br />

***
<img align="left" alt="JavaScript" width="35px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/Github-desktop-logo-symbol.svg/1200px-Github-desktop-logo-symbol.svg.png" /> 

## &nbsp;GITHUB DEKSTOP 👨🏼‍🤝
***

* ...is the simplified version (desktop based as the name already reveals) of github beside the regular version on github.com
* ...relies on simple click commands and drag and drop mechanisms instead of the usual commands via terminal
* ...must be downloaded locally to your computer which is linked to the Github account. The projects and repositories are synchronized and retrieved from the Github server at any time.

| STEP | COMMAND | EFFECT  | 
|:--------------| :--------------| :--------------|
|1| ... | ... |


<br />
<br />

***
## Collaboration ✅
***
> Feel free to contact me if you've seen something wrong, found some errors or struggled on some mistakes! Always happy to have a clean sheet here! :)


<br />
<br />

***
## FAQs ✅
***
0 Questions have been asked, 0 answers have been given, 0 changes have been made.

| Questions | Anwers | Changes |
|:--------------|:-------------:|--------------:|
| 0 | 0 | 0 |


