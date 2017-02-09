# practicegit
A toy project in which to practice version control skills.

This is the project you should clone to play along during the tutorial session.

We will practice editing existing files and adding new files to this project.

## Setup

1. Create a [GitHub](https://github.com/) account.
2. Request contributor access to this repository by contacting Barbara with you GitHub username.
3. Download the [GitHub Desktop](https://desktop.github.com/) application. This will install Git
   on your computer. Note that if you love the command line, you might want to follow different
   instructions to [install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

## Tutorial Steps

In this tutorial, we will practice downloading code, editing the downloaded files, and sharing
the edits with others.

### 1. Downloading code from GitHub

**Command line**: `git clone https://github.com/bfrewen/practicegit.git`

**GitHub Desktop**: Select **Clone or Download** and then **Open in Desktop**.

### 2. Creating a new file

Navigate to the *contributor_bios* directory and create a new file called `<yourname>.txt`.

Now add that file to your git history using a commit:

**Command line**:
```bash
git add contributor_bios/<yourname>.txt
git commit -m “Add contributor bio for <your name>”
```

**GitHub Desktop**:

1. Check off the filename `<yourname>.txt` in the changes column.
1. Enter `"Add contributor bio for <your name>"` in the Summary text box.
1. Press **Commit to master**.

You should now see a new circle along the line at the top representing this commit.

#### 3. Editing an existing file

Navigate to the *main_files* directory and edit the file called `poems.txt`. Adding a new
poem is encouraged.

**Command line**:
```bash
git add main_files/poems.txt
git commit -m “Add additional poem”
```

**GitHub Desktop**:

Almost the same as the previous step:

1. Check off the filename `poems.txt` in the changes column.
1. Enter `"Add additional poem"` in the Summary text box.
1. Press **Commit to master**.

#### 4. Sharing the new file and the edits

Now you want to share these two *commits* with the remote repository that you originally
downloaded the code from. To do this, you will *push* the data.

**Command line**: `git push`

**GitHub Desktop**: Press the **Sync** button in the upper right of the screen. Log in if
necessary.

#### 5. Seeing other people's edits

To see edits made by others to the remote (more poems! yay!) run the following commands:

**Command line**: `git pull`

**GitHub Desktop**: Press the **Sync** button in the upper right of the screen. Log in if necessary.

(Note that the **Sync** button in the GitHub desktop always does both Step 4 and Step 5.)
