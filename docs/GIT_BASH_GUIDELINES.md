# Using GitBash

## Contents

* [Getting started](#getting-started)
* [Creating a local folder to store clones](#writing-code)
* [Git Bash Terminal basics](#testing-code)
* [Creating new branch to add changes to](#opening-a-pull-request)
* [Pushing changes](#code-of-conduct)

## Getting started

* Start by downloading Git, which includes GitBash:
    * https://git-scm.com/downloads

## Creating a local folder to store clones

* Open GitBash, then, create a folder to store clones. Here is an example.
    ```GitBash
    # Check what directory you are currently in
    pwd

    # An example out may look like this -> "Users\Sheldon"
    # Next, navigate to where you wish to store your clone, this example will use the Desktop.
    cd Desktop

    # Create the folder
    mkdir gitrepo

    # Navigate to the newly created directory
    cd gitrepo

    # Clone your fork of the repo into this directory
    git clone https://github.com/<your-username>/PimaInterns-Iot.git

    # Assign the original repo to a remote called "upstream", this allows 
    you to make your own changes.
    git remote add upstream https://github.com/rlop20/PimaInterns-Iot.git
```


