## Prerequisite Skills to Contribute

### Contribute in public/Profile

- [Git](https://git-scm.com/) 
- [JSON](https://www.json.org/json-en.html)

### Contribute in Documents

- [Markdown](https://www.markdownguide.org/basic-syntax/)

### Contribute in Components/CSS

- [React](https://reactjs.org/)
- [Prime React](https://www.primefaces.org/primereact/)

# How to Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/SuperAayush/TWTCORD/pulls)

- Take a look at the existing [Issues](https://github.com/SuperAayush/TWTCORD/issues) or [create a new issue](https://github.com/SuperAayush/TWTCORD/issues/new/choose)!
- [Fork the Repo](https://github.com/SuperAayush/TWTCORD/fork). Then, create a branch for any issue that you are working on. Finally, commit your work.
- Create a **[Pull Request](https://github.com/SuperAayush/TWTCORD/compare)** (_PR_), which will be promptly reviewed and given suggestions for improvements by the community.
- Add screenshots or screen captures to your Pull Request to help us understand the effects of the changes proposed in your PR.

## HOW TO MAKE A PULL REQUEST:

**1.** Clone your new fork of the repository in the terminal/CLI on your computer with the following command:

```bash
git clone https://github.com/<your-github-username>/petwyse
```

**2.** Navigate to the newly created LinkFree project directory:

```bash
cd petwyse
```

**3.** Set upstream command:

```bash
git remote add upstream https://github.com/chandankumar1307/petwyse.git
```

**4.** Create a new branch:

```bash
git checkout -b YourBranchName
```

**5.** Sync your fork or your local repository with the origin repository:

- In your forked repository, click on "Fetch upstream"
- Click "Fetch and merge"

### Alternatively, Git CLI way to Sync forked repository with origin repository:

```bash
git fetch upstream
```

```bash
git merge upstream/main
```

### [Github Docs](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github) for Syncing

**6.** Make your changes to the source code.

**7.** Stage your changes and commit:

⚠️ **Make sure** not to commit `package.json` or `package-lock.json` file

⚠️ **Make sure** not to run the commands `git add .` or `git add *`. Instead, stage your changes for each file/folder

```bash
git add public
```

```bash
git commit -m "<your_commit_message>"
```

**8.** Push your local commits to the remote repository:

```bash
git push origin YourBranchName
```

**9.** Create a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)!

**10.** **Congratulations!** You've made your first contribution to [**PETWYSE**](https://github.com/chandankumar1307/petwyse/graphs/contributors)! 

**_:trophy: After this, the maintainers will review the PR and will merge it if it helps move the LinkFree project forward. Otherwise, it will be given constructive feedback and suggestions for the changes needed to add the PR to the codebase._**

## Run automated tests

After making changes make sure that tests passes

**1.** Start the Petwyse application by typing this command:

```bash
npm start
```

## Style Guide for Git Commit Messages :memo:

**How you can add more value to your contribution logs:**

- Use the present tense. (Example: "Add feature" instead of "Added feature")
- Use the imperative mood. (Example: "Move item to...", instead of "Moves item to...")
- Limit the first line (also called the Subject Line) to _50 characters or less_.
- Capitalize the Subject Line.
- Separate subject from body with a blank line.
- Do not end the subject line with a period.
- Wrap the body at _72 characters_.
- Use the body to explain the _what_, _why_, _vs_, and _how_.
- Reference [Issues](https://github.com/SuperAayush/TWTCORD/issues) and [Pull Requests](https://github.com/SuperAayush/TWTCORD/pulls) liberally after the first line.

## Issues

In order to discuss changes, you are welcome to [open an issue](https://github.com/SuperAayush/TWTCORD/issues/new/choose) about what you would like to contribute. Enhancements are always encouraged and appreciated.

## All the best! 👍🏻
