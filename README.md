# Custom Git Commands
This repository, `custom-git-commands`, provides a set of custom commands to enhance and extend the functionalities of the Git version control system.

## Installation
1. **Clone the Repository:**
    Clone this repository to your local machine using the following command:

    ```bash
    git clone git@github.com:sobitoks/custom-git-commands.git
    ```
2. **Move the Folder: (Optional)**
    Move the cloned folder to the desired location on your system. For example:

    ```bash
    mv custom-git-commands /wherever/you/want
    ```
3. **Execution Permissions:**
    Grant execution permissions to the files you want to use.
    You can grant permissions to all files in the directory as follows:

    ```bash
    chmod +x /wherever/you/want/custom-git-commands/*
    ```
    Or you might only want to use one of them:

    ```bash
    chmod +x /wherever/you/want/custom-git-commands/git-sand
    ```

4. **Add to PATH:**
    Add the folder to your system's PATH so that the commands are globally available. You can do this with the following command (make sure to adjust the path):

    ```bash
    export PATH=$PATH:/wherever/you/want/custom-git-commands
    ```
   
    Alternatively, you can add each individual command to the PATH according to your preferences.


## Usage

Once you have completed the installation, you can use the custom commands in your Git repository.
These commands follow the file naming convention git-WHATEVER, and you can execute them directly as Git commands.
Here is an example:

```bash
git stash push -m "MY_CUSTOM_NAME"
git sand MY_CUSTOM_NAME
```
```bash
git stash push -m "MY CUSTOM NAME"
git sand "MY CUSTOM NAME"
```

## Available Commands

**git san:**
The git-san command stands for git stash apply name. 
It facilitates the retrieval of changes from a stash, 
based on the specified name used when saving a stash with the command ```git stash push -m "NAME"```. 
This command streamlines the process of applying stashes, providing a seamless way to recover changes associated with a particular stash name.

**git sand:**
The git-sand command stands for git stash apply name drop.
It facilitates the retrieval of changes from a stash,
based on the specified name used when saving a stash with the command ```git stash push -m "NAME"```.
This command streamlines the process of applying stashes, providing a seamless way to recover changes associated with a particular stash name.
It will drop the used stash once retrieved.

## Contributions
Feel free to contribute to this project. You can suggest new features, report issues, or submit pull requests. Any help is appreciated!

## Mentions
Thanks to https://gitbetter.substack.com/p/automate-repetitive-tasks-with-custom

## License
This project is under the MIT License.