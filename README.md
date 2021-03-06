# C
## How to Start?

#### If you don't have git on your machine, [install](https://help.github.com/articles/set-up-git/) it.

### :metal: Star The Repo

Star the repo by pressing the topmost-right button to start your wonderful journey.

### :metal: Fork The Repo

You can get your own fork/copy of this repo by using the <b>Fork</b> button present at top-right of your screen.

### :metal: Clone it

`NOTE: commands are to be executed on Linux, Mac, and Windows`

You need to clone (download) it to local machine using

```sh
$ git clone https://github.com/<Your_Github_Username>/C.git
```

### :metal: Create a new branch

Whenever you are going to contribute. Please create a separate branch using command and keep your `main` branch clean (i.e. synced with remote branch).

```sh
# It will create a new branch with name Branch_Name and switch to branch Folder_Name
$ git checkout -b BranchName
```
Do the changes according to the issue that you want to solve

To add the changes to the branch. Use

```sh
# To add all files to branch Folder_Name
$ git add .
```

Type in a message relevant for the code reviewer using

```sh
# This message get associated with all files you have changed
$ git commit -m 'relevant message'
```

Now, Push your awesome work to your remote repository using

```sh
# To push your work to your remote repository
$ git push -u origin BranchName
```

Finally, go to your repository in the browser and click on `compare and pull requests`.
Then add a title and description to your pull request that explains your precious effort.
