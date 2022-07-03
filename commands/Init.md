# git init

The git init command is used to create an empty git repsitory.

If you wanted to create a new directory and initialize a git repository, you can do so with the following commands:

```
mkdir NewDirectory
cd NewDirectory
git init
```


Once inisde a git repository, you can start using commands such as
[status](./Status.md),
[add](./Add.md),
[commit](./Commit.md),
[push](./Push.md)
and more.

Init will create the repository in the current directory and will encapsulate all content, including other directories.

## Resources

- [Git Init Documentation](https://git-scm.com/docs/git-init)

---

[Back to home](../README.md)
# git pull

Similar to a [git push](./PUSH.md), a git pull will interact with a remote repository. Only this time it will *pull** the changes it does not have from the remote down to the local repository.

This means any commits made that are on the remote repository will be pulled down and added to the local repository.

This can be done by adding the remote name and branch name:
git pull origin main


If there is any upstream connection established, you can use git pull without specifying a remote or branch.

## Resources

- [Git Pull Documentation](https://git-scm.com/docs/git-pull)

---

[Back to home](../README.md)