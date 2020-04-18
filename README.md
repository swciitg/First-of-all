<!-- <img align="centre" width="100%" src="assets/icon1.jpeg"> -->
[<img align="right" width="150" src="assets/discord.png">](https://discord.gg/HCdctrz)

# First Contributions

How can we be locked down when we have an infinite things to learn? We will make our first imprint in "Build From Home" module by coping up with github.

Github is one of the primary tool that we use while working as a team and making collabrations.
We wanted to make all of our budding developers learn & contribute for the first time.

Reading articles & watching tutorials can help, but what's better than actually doing the stuff in a practice environment? This tutorial aims at providing guidance & simplifying the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

<img align="right" width="300" src="assets/fork.png" alt="fork this repository" />

If you don't have git on your machine, [install it]( https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="assets/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url you just copied" (without the quote marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:
```
git clone https://github.com/this-is-you/First-of-all.git
```
where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd First-of-all
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-new-branch-name>
```

For example:
```
git checkout -b add-alonzo-church
```
(The name of the branch does not need to have the word *add* in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

Now open `swc_team.md` file in a text editor, add all the details as per the sample provided in file. Now, save the file.

<img align="right" width="450" src="assets/git-status.png" alt="git status" />


If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

```
git add swc_team.md
```

Now commit those changes using the `git commit` command:
```
git commit -m "Uploaded <your-name>'s details to swc_team list"
```
replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:
```
git push origin <add-your-branch-name>
```
replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.

<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="assets/submit-pull-request.png" alt="submit pull request" />

Congratulations, You have successfully submitted your first contribution.

We will be analysing your details and assign you projects accordingly.
Once your pull request is accepted, you will be receiving a mail containing the details of your project and discord invitation.

Stay Safe....
