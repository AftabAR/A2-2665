# M2-E1
Exercise 1 of Module 2. Which was changed recently.

## How to clone it
Follow these steps:
1. Install git on your machine: https://git-scm.com/download/win
2. Clone this repository:
```sh
    git clone https://github.com/intro-do-riu/M2-E1
```

## How to build it
This is an npm package that can calculate Tax for given salary. You'll need following to be installed:

1. Node.js which you can get from: https://nodejs.org/en/download/
2. Optional: Install Visual Studio Code as your IDE.

Once you have setup the above, do the following steps to build and run tests:

1. Launch command prompt.
2. Go to the folder where repo was cloned.
```sh
    cd Documents\M2-E1
```
3. Install npm dependencies:
```sh
    npm install
```
4. Build code:
```sh
    npm run build
```
5. Run tests:
```sh
    npm test
```
## Package.json
It has details about the project, like license, dependencies, repo URL etc. For example, it has a dependency on TypeScript which is a superset of Javascript.

## Basic pull and push workflow
You'll need to do a 'git pull' to get changes form remote.
And in case you need to create a branch, you can do 'git checkout'
Some changes on branch
