# wyag: Write Yourself a Git

This project is an implementation of a Git-like version control system in Python. It's designed to help understand the internals of Git by recreating its core functionality. Huge thanks to Thibault Polge and his article https://wyag.thb.lt/ for making this happen! 

## Features

- Initialize a new repository
- Add files to the staging area
- Commit changes
- Create and manage branches
- View commit logs
- Check the status of the working directory
- Ignore files using .gitignore

## Commands

The following commands are implemented:

- `init`: Initialize a new, empty repository
- `add`: Add file contents to the index
- `cat-file`: Provide content of repository objects
- `check-ignore`: Check path(s) against ignore rules
- `checkout`: Checkout a commit inside of a directory
- `commit`: Record changes to the repository
- `hash-object`: Compute object ID and optionally creates a blob from a file
- `init`: Initialize a new, empty repository
- `log`: Display history of a given commit
- `ls-files`: List all the stage files
- `ls-tree`: Pretty-print a tree object
- `rev-parse`: Parse revision (or other objects) identifiers
- `rm`: Remove files from the working tree and the index
- `show-ref`: List references
- `status`: Show the working tree status
- `tag`: List and create tags

