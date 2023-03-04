# BaseConfig

This repository is meant to reflect my personal preferences.

The `.vscode` folder is only there to save my own VSCode setup and should not stay in any project. 

## Setup
1. [Download](https://github.com/ZoidC/BaseConfig/archive/refs/heads/dev.zip) this repository as Zip, extract and rename
2. Create a new repository on [Github](https://github.com/)
3. Open a new terminal in your local folder and follow the instruction to <strong>push</strong>
```git
git init
git remote add origin <your_https_or_ssh_github_link>
git branch -M dev
git add .
git commit -m "<your_commit_message>"
git push -u origin dev
```
4. Configure npm
```bash
npm init
```
```bash
npm i -D prettier eslint 
```
Only for <strong>TypeScript</strong> projects
```bash
npm i -D @typescript-eslint/parser typescript
```
Only for <strong>Vue</strong> projects
```bash
npm i -D vue-eslint-parser
```
