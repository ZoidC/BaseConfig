# BaseConfig

This repository is meant to reflect my personal preferences.

The `.vscode` folder is only there to save my own VSCode setup and should not stay in any project.

## Setup

1. [Download](https://github.com/ZoidC/BaseConfig/archive/refs/heads/dev.zip) this repository as Zip, extract and rename

2. Open this folder with VSCode

3. Install the recommended extensions _(when it's done, you can delete the `.vscode/extensions.json` file)_

4. Update your VSCode Settings _(when it's done, you can delete the `.vscode/settings.json` file)_
    - Open the prompt: `CTRL + E`
    - Type: `settings.json` _(you should see 2 options)_
    - Paste the content of `.vscode/settings.json` in your local `settings.json` file
5. Delete the content of this `README.md`

6. Configure your project with `npm`

```bash
npm init
```

```bash
npm i -D eslint prettier prettier-eslint typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin
```

## Push your own Github project

1. Create a new repository on [Github](https://github.com/)

2. Open a new terminal in your local folder and follow the instruction to <strong>push</strong>

```git
git init
git remote add origin <your_https_or_ssh_github_link>
git branch -M dev
git add .
git commit -m "<your_commit_message>"
git push -u origin dev
```
