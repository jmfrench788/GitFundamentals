# Git Commit

The `git commit` will take all tracked changes (items added with [git add](/Add.md)) and package them into what is called a commit.

Commits come with commit messages that are required. Add a message using the `-m` flag, followed by the message in quotes.

A commit message can be anything but best practice dictates that you should use the message to indicate changes included in the commit.

For example, if we have an application that we are working on where we just build out the ability to register new accounts, then you might have some variation of the following:

``` 
git add .
git commit -m "Added register functionality"
``` 

Then when viewing the history of a git repository, you can pinpoint where the registration functionality was added.

## Resources

- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

---

[Back to home](../README.md)