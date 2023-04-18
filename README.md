# Getting started with collaborating and contributing to open source projects
This project is built by former students of The Last Mile. If you are looking to make your first contribution, follow the steps below.

#### If you don't have git, node, and/or vscode on your machine, [here is a helpful tutorial to do so](https://drive.google.com/file/d/11fnb_uE8SO9H1gnvOt_u5sRaBqIZu8nT/view?usp=sharing).

To make open source contributions, you’ll need to be comfortable using git.

## What is git?
Git is a tool that is used for all projects on Github (including this one) to make it easier to track changes that are made to a coding project. Tracking changes not only makes it easier for you to manage your own revisions to a project, but it also enables easier collaboration with other people who are simultaneously working on the same project. Tools like git are examples of version control systems.

Version control systems not only let you track your own changes to software, but let you work on your own code independently from other people without affecting their own changes. Once you’ve made your changes, you can request that your changes be made part of the “main” version of the project.

Git link
https://www.learnenough.com/git-tutorial#sec-exercises_initializing_the_repo
https://www.udemy.com/course/git-complete/

Git docs
https://git-scm.com/docs
Git jargon

TODO: Add explanations/definitions of all the technical jargon used on this Readme
- Fork
- Clone
- Git
- Branch
- Merge
- “git status”
- “git add”
- “git commit”
- “git push”
- “git pull”
- “git log”
- “git diff”

(adding “git rebase”? Maybe? Something people should eventually know, maybe not immediately for this)

- SSH
- Repository
- remote
- auth/sign in key (pick auth always)
- Pull request
- ‘git help’ command



## Fork this repository

![Black and Blue Dark Mode Modern Shoes Inspiration Instagram Post](https://user-images.githubusercontent.com/56654391/230608866-83905702-ce93-4b36-bb12-671f76b51d42.png)


Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

![Screenshot 2023-04-07 5 30 37 AM](https://user-images.githubusercontent.com/56654391/230609297-e46192d5-9d9f-45f6-afa6-628bb9d87d96.png)


## Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone https://github.com/TLM-Alumni/getting-started.git 
```


## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd getting-started
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b carrie-murchison
```

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
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

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

Now submit the pull request.

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll encounter often as a contributor! Feel free to contribute in other areas on this project, right now I am hoping for MERN project to be added that all alumni can contribute to. Now that you are comfortable with the process feel free to "branch" out, and look for any other of the millions of projects on GitHub that you can contribute to.
