# First Contributions

It's always hard to get started. So we wanted to simplify the way students learn about git and github.

This project aims at providing guidance & simplifying the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

#### If you're not comfortable with command line, you can find tutorials on how to use the GUI tool but we recommend using the command line interface(cli).


If you don't have git on your machine, [install it]( https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

<img align="center" width="40%" src="assets/fork.png" alt="fork this repository" />
<br>

## Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the *copy to clipboard* icon.

<img align="center" width="40%" src="assets/clone.png" alt="clone this repository" />
<br>

Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

For example:
```
git clone https://github.com/your-user-name/first-contribution-github.git
```
where `your-user-name` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

<img align="center" width="40%" src="assets/cloning.png" alt="cloning" />

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contribution-github
```
Now create a branch using the `git checkout` command:
```
git checkout -b <add-your-new-branch-name>
```

For example:
```
git checkout -b t-bugfix
```
(The name of the branch can be anything you want but it is recommended to use a name that explains the purpose of the branch.)


## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning. Put it anywhere below the heading. Now, save the file.

<img align="right" width="450" src="assets/git-status.png" alt="git status" />


If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md just to add Contributors.md to staging or you can use git add . to stage all the changes.
```

Now commit those changes using the `git commit` command:
```
git commit -m "Add <your-name> to Contributors list"
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

Soon we'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard github workflow that you'll often encounter as a contributor!

You can follow this link to find more begineer friendly projects to contribute, [List of projects]( https://github.com/MunGell/awesome-for-beginners ).
