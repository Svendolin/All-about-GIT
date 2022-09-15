![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Svendolin/All-about-GIT?style=for-the-badge) ![GitHub contributors](https://img.shields.io/github/contributors/svendolin/All-about-GIT?style=for-the-badge) ![GitHub forks](https://img.shields.io/github/forks/Svendolin/All-about-GIT?color=pink&style=for-the-badge) ![GitHub last commit](https://img.shields.io/github/last-commit/Svendolin/All-about-GIT?style=for-the-badge) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/Svendolin/All-about-GIT?color=yellow&style=for-the-badge)


***
<img align="left" alt="git logo" width="35px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" /> 

# &nbsp;- ALL ABOUT GIT and GITHUB - ✔

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

        
<br />
<br />

***
## Technologies and Installation ✅
***

GIT BASH (for Windows) - INSTALLATION:
* https://gitforwindows.org/


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
|7| $ git add readme.md | ADD your change to the git (ready to track in GIT) |
|8| $ git commit -m "first commit" | COMMIT your first change |
|9| $ git branch -M main | OPTIONAL: Change the branch name from master to main |
|10| $ git remote add origin (#) | REMOTE them with the github HTTPS link  |
|11| $ git push -u origin master | PUSH your changes - (If you did step 9, master would be main) |
|12| $ git status | STATUS check to make sure everything went right |
|13| $ git log | LOG shows your structure |
|14| Now its time to make some changes:

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
|3| $ git pull | CHECK of undone changes (conflicts) and decide which change you want to make if necessary. A pull request will synchronise your remote data |
|4| $ git add . | ADD what you changed (ready to track in GIT) The "." means "ADD ALL FILES", but you can also name an exact file from the explorer if you wish |
|5| $ git commit -m "" | COMMIT a message to say what you changed (Write a desctiption between "") - It saves your files in GIT |
|6| $ git push -u origin master | PUSH your changes (means upload GIT commits to a remote repository like GITHUB) - (btw master if your branch is named "master", otherwhise say the right name) |
|7| $ git status | STATUS check to make sure everything went right |

<br />
<br />

***
<img align="left" alt="JavaScript" width="35px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/terminal/terminal.png" /> 

## &nbsp;How to MAKE, ADD + PUSH and MERGE BRANCHES: ✅ (Working non-destructive)
***
| STEP | COMMAND | EFFECT  | 
|:--------------| :--------------| :--------------|
|1| $ git branch test | CREATE a new branch which is called "test" |
|2| $ git checkout test | CHECKOUT to your new branch (you switch over from your other branch to your "test" branch) |
|3| $ git status | OPTIONAL: STATUS check to make sure everything went right |
|4| $ git add . | ADD what you changed (. means ALL, but you can also name an exact file from the explorer) |
|5| $ git commit -m "" | COMMIT to say what you changed (Write a desctiption between "") |
|6| $ git push -u origin test | PUSH your changes to your "test"-branch (*) |
|7| $ git checkout master | OPTIONAL: checkout to your other branch (must exist and name must match) |
|8| $ git merge test | CAREFUL: Only works if you are in the source branch (like "master") and "drag in" the changes.  |

(*) If every went well => While "checkouting between branches" you're only going to see your pushed content of your specific branch!

<img text-align="center" alt="Github" width="" src="https://w3cschoool.com/public/file/Git/git-pull2.png" /> 

<br />

| TERM | MEANING  | 
|:--------------| :--------------|
| Workspace| Your local computer > "adds" the changes to the index > "commits" the changes with a message to your repo |
| Repository| Project / Folder place "Ablage / Aufbewahrungsort" where your project is kept > "push" the changes to the remote |
| Remote| Remote Repository like GITHUB where your projects are hosted / placed on an external server (like Dropbox, but for Code) |
| PULL | Download change from the REMOTE to your WORKSPACE (local machine) which is the opposite of push |
| PUSH | Upload GIT commits from your REPOSITORY to a REMOTE which is the opposite of pull |

<br />
<br />

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

## &nbsp;How to DELETE: ❌
***
| STEP | COMMAND | EFFECT  | 
|:--------------| :--------------| :--------------|
|1| $ git branch -d test | CAREFUL: Deletes your "test" branch with all your adjustments inside |


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


