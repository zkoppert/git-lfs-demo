# Git Large File Storage

## What problem does it solve?
Git LFS provides a system where large files can be stored in git without reducing the performance of common git commands.

## How do I use it?
1. Download and install Git LFS on your machine since it does not come standard with git.

`https://git-lfs.github.com/`

2. Set up Git LFS on your system.

`git lfs install`

3. Track new files in Git LFS for file types that are typically larger

`git lfs track "*.pdf; git add .gitattributes`

4. Track existing large files in Git LFS

`git lfs migrate --above="5 MB"`
