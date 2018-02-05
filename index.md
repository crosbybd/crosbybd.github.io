# BIOL812 Assignment - Brody Crosby

## Questions

1 - Git should be used to manage project updates and retain all versions of a project in case
the developer needs to refer to or continue work at an earlier version.


2 - Git repositories should contain text-based files including code, scripts, text documents,
etc. Large-sized files, data, and files containing sensitive information should not be saved in
Git repositories.


3 - To undo a commit, either use

```{}
git checkout HEAD~1 <filename>
```

The user is now "looking at" the previous version of the file, and can work from there, or

```{}
git revert <commit_id>
```

This directly undoes the commit made prior to this file version.


4 - The "HEAD" state indicates your reference point within your project's version history. To
re-attach your head (i.e., return your reference point to the most recent version of the
project), use the command

```{}
git checkout master
```


5 - Git is a resource for version control, and it provides the user complete access to all
versions of a file. For written documents, scripts, and code, the user can track changes and
undo mistakes or unwanted changes. Git is based on a few simple commands, but understanding it
may take a lesson or two. Using online repositories on Github or other websites can be useful
to make the process of Git version control more user-friendly and allow multiple developers to
work on projects simultaneously. Online repositories are often public unless the user pays for
private space, so the user should be aware of what information is safe to push to an online
repository before using one.


