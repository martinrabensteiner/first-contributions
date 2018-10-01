[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[<img align="right" width="150" src="assets/join-slack-team.png">](https://join.slack.com/t/firstcontributors/shared_invite/enQtMzE1MTYwNzI3ODQ0LTZiMDA2OGI2NTYyNjM1MTFiNTc4YTRhZTg4OWZjMzA0ZWZmY2UxYzVkMzI1ZmVmOWI4ODdkZWQwNTM2NDVmNjY)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source Helpers](https://www.codetriage.com/roshanjossey/first-contributions/badges/users.svg)](https://www.codetriage.com/roshanjossey/first-contributions)

# First Contributions

|<img alt="Visual Studio 2017" src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/Visual_Studio_2017_logo_and_wordmark.svg/2000px-Visual_Studio_2017_logo_and_wordmark.svg.png" width="200">|Visual Studio 2017 Edition|
|---|---|

Aller Anfang ist schwer. Gerade dann, wenn wir gemeinsam an etwas arbeiten, will niemand etwas Falsches tun. Aber Open Source dreht sich um Kooperation und lebt von den Beiträgen von vielen Freiwilligen. Deshalb haben wir es uns zur Aufgabe gemacht, neuen Mitgliedern in der Open-Source-Gemeinde ihre ersten Schritte so einfach wie möglich zu machen.

Natürlich helfen die vorhandenen Artikel und Videoanleitungen. Aber was kann besser sein, als es einfach einmal auszuprobieren mit dem Wissen, dass man nichts kaputt machen kann? Diese Projekt will Anfängern zeigen, wie sie möglichst einfach ihren ersten Beitrag leisten. Bedenke: Je entspannter du bist, desto besser lernst du. Wenn du deinen ersten Beitrag leisten möchtest, folge diesen einfachen Schritten. Wir versprechen dir, es wird Spaß machen.

Wenn du Visual Studio 2017 noch nicht installiert hast, kannst du es [hier](https://www.visualstudio.com/downloads/) downloaden.

## Repository forken

<img align="right" width="300" src="assets/fork.png" alt="fork this repository" />

Forke das Repository durch das Anklicken der Schaltfläche "Fork". Dadurch erhältst du deine eigenen Version des Projektes in deinem Profil.

GitHub behält die Änderungen zwischen dem Original und dem kopierten Repository in deinem Profil, es ist wie eine Arbeitskopie für dich alleine.

Änderungen an den meisten GitHub-Repositorys können nur von wenigen, dazu privilegierten Contributern committed werden. Alle anderen Benutzer müssen das Repo forken und die Änderungen in diesem Fork machen, dann einen Pull Request absenden um so eine Änderung im Original-Repository vor zu schlagen. Wenn ein Administrator des Projekts deinem Änderungsvorschlag zustimmet, wird dieser ins Original übernommen - du wirst berühmt und erntest die Lorbeeren für deinen Beitrag! Später mehr dazu.

## Repository klonen

<img align="right" width="300" src="assets/clone.png" alt="clone this repository" />

Der nächste Schritt ist, dein Repository zu klonen. Das bedeutet, eine Kopie deines Online-Repos auf deinem Computer zu machen. Git behält die Änderungen im Überblick (That's the magic!). Visual Studio braucht dazu die URL davon, dafür klickst du auf "Clone or download" und dann auf das Zwischenablagen-Icon.

**ACHTUNG:** Ein klassischer Anfängerfehler ist es, das Original-Repo und nicht den extra dazu angelegten Fork zu klonen. Commits kannst du nur auf deinen Fork machen (dazu ist er da). Schau auf die URL, da drin muss dein Username enthalten sein, wenn es sich um deines handelt.


It is now time to jump in to Visual Studio 2017!  You will be working in the Team Explorer tab for most of this tutorial.  If it is not open by default, click `View > Team Explorer` to open it.

<img src="assets/vs2017-01-clone1.png" alt="Team Explorer" />

Team Explorer has many views and there are navigation buttons located at the top to help you find the different areas.  To clone a repo, you need to be on the Connect view, which should be the default.  If you do not see the 'clone' button, click the green plug at the top.

Click the `Clone` option under **Local Git Repositories** and paste the URL to your repo in the text box.  This should be the URL you copied to your clipboard from GitHub previously.

Click the `Clone` button to initiate the process.

<img src="assets/vs2017-02-clone2.png" alt="Clone repo" />

When the process is complete you will be moved over to the Solution Explorer tab where you can see the contents of your repo.  Yours will look different than the screenshot below because things change!

<img src="assets/vs2017-03-clone3.png" alt="Solution Explorer" />

## Create a branch

Click back to the Team Explorer tab and use the main navigation dropdown to open the Branches view.

<img src="assets/vs2017-04-branch1.png" alt="Branches view" />

You should see the **first-contributions** repo and the default branch, which is called `master`.  Right-click on `master` and choose `New Local Branch From...`.

<img src="assets/vs2017-05-branch2.png" alt="New branch" />

Give your branch a name like `add-<your_name_here>`, for example: `add-alonzo-church`.

Leave the `Checkout branch` box checked and click the `Create Branch` button.

<img src="assets/vs2017-06-branch3.png" alt="Create branch" />

You should see your new branch in the list.

<img src="assets/vs2017-07-branch4.png" alt="See new branch" />

## Make necessary changes

Open `Contributors.md` and add your name to the end of the list. This file contains GFM (GitHub Flavored Markdown) which is a proprietary flavor of the <a href="https://en.wikipedia.org/wiki/Markdown">markdown</a> syntax.

Copy one of the other contributors&apos; lines and modify it with your name to make sure you get the syntax right - it can be picky.

<img src="assets/vs2017-08-change1.png" alt="Add your name" />

## Commit & Push changes to GitHub

Switch back to Team Explorer and navigate to the Changes view.

<img src="assets/vs2017-09-commit1.png" alt="Changes" />

Enter the information you want to post with your commit and click `Save`. Visual Studio will remember it for future commits.

<img src="assets/vs2017-10-commit2.png" alt="Git user information" />

**NOTE:** Visual Studio uses a hidden folder called `.vs` to store your personal settings and preferences.  The contents of this folder **should not be saved in Git**.
If it has not been ignored already, you may need to tell Git to ignore this folder so it does not send it up to the repo.

This folder has already been ignored in this repo, so you should not have to perform this step...it is just here for your reference for future projects.

<img src="assets/vs2017-11-commit3.png" alt="Ignore vs folder" />

Now you should see a list of changed files and a textbox to type a commit comment.  Comments should be in brief but thorough.  There is nothing worse than reading through commit comments and seeing this: `"I updated some stuff"`. Take a few seconds to outline your commit.  Your team will thank you later, and you might even thank yourself!

Click `Commit All and Push` to perform a local commit and push your changes back up to your repo, all in one step.

**NOTE:** Commit can be performed separately from Push.  We do both here for convenience. Commit logs your changes locally but they will not be reflected in your GitHub repo until you Push.

<img src="assets/vs2017-12-commit4.png" alt="Commit and Push" />

The first time you Push to GitHub, Visual Studio will ask for your GitHub credentials.  They will be cached so you should not see this very often.

<img src="assets/vs2017-13-commit5.png" alt="Login" />

After the Push operation completes, open your repo in GitHub and you should see a message indicating a recently pushed branch.

You can view your changes by opening the `Branch: master` dropdown and selecting your new branch. Congratulations, you can share the branch URL with the world to show your progress!

<img src="assets/vs2017-14-commit6.png" alt="View pushed branch on GitHub" />

## Submit your changes for review

At this point you have completed your change but it still only resides in your repo.  This step will show you how to submit a request to the administrator of the top-level repo to merge your change.

In your repo on GitHub you'll see the `Compare & pull request` button next to the new branch notification. Click on that button.

<img src="assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img src="assets/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats!  You have just completed the standard _fork -> clone -> edit -> PR_ workflow that you'll encounter often as a contributor!

Celebrate your contribution and share it with your friends and followers by going to [web app](https://roshanjossey.github.io/first-contributions/#social-share).

You can join our slack team in case you need any help or have any questions. [Join slack team](https://join.slack.com/t/firstcontributors/shared_invite/enQtMzE1MTYwNzI3ODQ0LTZiMDA2OGI2NTYyNjM1MTFiNTc4YTRhZTg4OWZjMzA0ZWZmY2UxYzVkMzI1ZmVmOWI4ODdkZWQwNTM2NDVmNjY).

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on. Check out [the list of projects in web app](https://roshanjossey.github.io/first-contributions/#project-list).

### [Additional material](additional-material/git_workflow_scenarios/additional-material.md)


## Tutorials Using Other Tools

|<a href="README.md"><img alt="Command Line" src="http://cdn.osxdaily.com/wp-content/uploads/2014/08/terminal-icon-osx-150x150.png" width="100"></a>|<a href="github-desktop-tutorial.md"><img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"></a>|<a href="gitkraken-tutorial.md"><img alt="GitKraken" src="/assets/gk-icon.png" width="100"></a>|
|---|---|---|
|[Command Line](README.md)|[GitHub Desktop](github-desktop-tutorial.md)|[GitKraken](gitkraken-tutorial.md)|


## Self-Promotion

If you liked this project, star it on [GitHub](https://github.com/Roshanjossey/first-contributions).
If you're feeling especially charitable, follow [Roshan](https://roshanjossey.github.io/) on
[Twitter](https://twitter.com/sudo__bangbang) and
[GitHub](https://github.com/roshanjossey).

<a href="http://saasgrids.com"> <img alt="http://saasgrids.com" src="assets/saasgrids-banner.png" width="500"></a>

