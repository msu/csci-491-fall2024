# CSCI 491 - Advanced Web Development

This is the base upstream repository for CSCI 491: Advanced Web Development  

It contains the homework assignments, as well as the class project information.

## Getting Your Private Copy

Please use the following steps to create a *private* copy of this repo for your work:

- Create a *private* repository in your own account by
    - Going to <https://github.com/new>
    - Enter the name `csci-491-fall2024-private`
    - Select `Private`
    - Navigate to the `Settings` -> `Manage Access` section
    - Add `1cg` as a collaborator
Once your repository is initialized, you can pull it down to your local machine:

```bash
$ git clone <your github repo url>
```

You can find the github repo url when you look at the repository in github.

Next, you should add the class repository as an upstream git repo:

```bash
$ cd csci-491-fall2024-private
$ git remote add upstream https://github.com/msu/csci-491-fall2024.git
$ git pull upstream main
$ git push origin main
```
This will synchronize your private repository with the class repository.

When you want to get an update from the public class repository you can run this command:

```
$ git pull upstream main
```