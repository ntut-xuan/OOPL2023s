# Git Practice

When you finished the game framework practice, you should start to practice Git.

**A repository per team.**



## Create Github Account

Skip it if you already have Github account.

Create an account in sign up page.

<img src="https://i.imgur.com/r2Z53MF.png" alt="image-20230224144512789" style="zoom:50%;" />



## Create Github Repository (repo)

Go to profile page, click "Repositories" tab.

![image-20230225020112972](https://i.imgur.com/02Rmpwx.png)



Click "New" to create new repository (repo). 

![image-20230225020130708](https://i.imgur.com/AOj9uH3.png)



Input your repo name, and click "Create repository" to create the repository.

**Remember setup the repo permission to private.**

![image-20230225020230123](https://i.imgur.com/lpVz8Yf.png)



After these step, you should have a private repo like the following image.

Do the next step for setup the collaborator.

![image-20230225020242994](https://i.imgur.com/2ZuDJQT.png)



## Setup the collaborator

In this step, you should **setup your teammate account and TA account** to be the collaborator.

**The action only the repo owner can do it.**



Click the settings tabs

![image-20230225020549088](https://i.imgur.com/D9PBCE5.png)



Click the Collaborators tab on the left-side toolbar.

![image-20230225020614408](https://i.imgur.com/D6Jz7J1.png)



Click "Add people" to add your teammate account and TA account.

**TA account: ntut-xuan (username) or t109590031@ntut.org.tw (e-mail)**

![image-20230225020639138](https://i.imgur.com/I5W9cdF.png)



Your teammate and TA should receive the invate mail, notify them to receive the mail and confirm the invitation.

![image-20230225020651085](https://i.imgur.com/tnvpNEW.png)



## Initialize the repo and create the branch

The following step will show you how to initialize the repo and create the branch.

If you are the leader of the team, you should initialize the repo and create the branch for your teammate.

If you are the teammate of the team, you should clone the repo.

**This is not only one way to initialize your repo, just make sure the branch specified in requirement should exists.**



Create a new folder, doing these command to initialize your repo with README.md

![image-20230225020901872](https://i.imgur.com/AUx9TTj.png)



After these step, you should have a new branch `main` in your repo.

(Ignore the content in `README.md` since you can type anything on it.)

![image-20230225021223245](https://i.imgur.com/Qn5sg6A.png)



## Create practice branch and push your code to branch

Click "branch" to create the practice branch.

![image-20230225021246384](https://i.imgur.com/uoC82nk.png)



Click "New branch" to create the branch.

![image-20230225014347803](https://i.imgur.com/LYCTkpr.png)



Create the new branch `game-framework-practice` branch to submit your `game-framework-practice` code.

![image-20230225014420977](https://i.imgur.com/12sL43r.png)

![image-20230225021324871](https://i.imgur.com/W4THBlI.png)



Back to the local folder, use `git fetch origin` to get the branch info and use `git checkout game-framework-practice` to switch the branch.

![image-20230225021507335](https://i.imgur.com/QGzTos4.png)



Place your practice code to the folder and commit your changes.

![image-20230225021537905](https://i.imgur.com/JyKP7ew.png)

![image-20230225021945136](https://i.imgur.com/rb5IOTA.png)



After these step, you should find out your practice code on `game-framework-practice` branch.

![image-20230225022022943](https://i.imgur.com/G3cLUwf.png)



## Create pull request

In this step, you should create the Pull Requests and *intent* to merge the game-framework-practice branch to master branch.

This step should setup the reviewer to `ntut-xuan` (TA account), and TA will verity your practice is good or not.



Click "Compare & pull request"

![image-20230225022049495](https://i.imgur.com/cMgFwmK.png)



We intent to merge the `game-framework-practice` branch to `main` branch.

The base branch should be `main` and the compare branch should be `game-framework-practice`.

You can type the title and description to open a pull request, **remember to setup the reviewer to ntut-xuan**.

![image-20230225022211958](https://i.imgur.com/zcl2odK.png)



Click "Create pull request", you should see the following page.

![image-20230225022255349](https://i.imgur.com/IdLvQJ1.png)



After setup`ntut-xuan` to reviewer, TA will review your practice, and create his review (approved changes or leave the message to describe why fail).

Once you have approved these changes by `ntut-xuan`, your **practice part will be approved.**

After get approved, you can:

- Close this PR, and place the purified game-framework code to have purified develope environment.
- Merge this PR to `main` branch, and reuse the practice code to develope your game. 

![image-20230225022440395](https://i.imgur.com/UpRcVlN.png)



## Note

Your PR should get approved before 3/3.

If you setup reviewer to `ntut-xuan` but still doesn't get any review, contact TA immediately.

