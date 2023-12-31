## Table of Contents
- [Introduction to Wordoid](#introducing-Wordoid)
- [Demo](#live-demo)
- [Local Setup](#how-to-set-up-Wordoid-for-development)

## Introducing Wordoid
It's a tool for reading github code in the brower using Monaco editor. It helps in skimming the codebase with ease and have features like multiple open files.
## Live Demo
Here is the link for the live demo, give it a try
> [Wordoid](https://wordoid-1.netlify.app/)

### Install dependencies
```
cd wordoid
npm install
npm start
```
<p align="right">(<a href="#top">back to top</a>)</p>
<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------- -->

## How to Set up `Wordoid` for Development?
###  Fork and Clone the Repo

First, you need to fork the `Wordoid` repo. You can do this by clicking the `Fork` button on the top right corner of the repo. If you are new to forking, please watch this [YouTube Guide](https://www.youtube.com/watch?v=h8suY-Osn8Q) to get started.
Once forked, you can clone the repo by clicking the `Clone or Download` button on the top right corner of the forked repo.
Please change the directory after cloning the repository using the `cd <folder-name>` command.

> **Note:** Create a `.env.local` file. Update your `env variable` like `VITE_GITHUB_TOKEN`. If you don't know how to get token follow this [article](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens).
### Install Dependencies
Next, install the dependencies by running the following command in the `Wordoid` repo. we recommend using `yarn` but you can install using `npm` too
```bash
yarn install
```
Or
```
npm install
```
if you don't have `yarn` installed on your PC, follow the steps below to install it..
**Windows**
1. open your command prompt as administrator.
2. write `corepack enable` and hit enter.
3. then `npm install --global yarn`
**Linux**
1. open terminal and hit `npm install --global yarn`
**MacOS**
1. open terminal and hit `npm install --global yarn`
   or
   `brew install yarn`
**Or Download Package**
If you are unable to install yarn following the above-mentioned process, then you can simply download the package and install it. Visit the official website of Yarn; there you can just expand the "Alternative" section and it will ask for the version to download for Windows, Linux, or Mac.
`https://classic.yarnpkg.com/en/docs/install#windows-stable`
> **Note**: `Wordoid` runs on React 18. However, some of the dependencies are yet to upgrade to version 18. So please use the following command when you face difficulties installing the dependencies. Also, ensure to use Node.js version >= 16.x
### Start the Development Mode
Use the following command to start the app in the development mode:
```bash
yarn run dev
```
or if you installed dependencies using `npm` use below command
```
npm run dev
```
It runs the app in development mode. Open [http://localhost:5173](http://localhost:5173) to view it in your browser.

The page will reload when you make changes.

## Github Beginner Guide
You can refer to the following articles on the basics of Git and Github and also contact me, in case you are stuck:
- [Forking a Repo](https://help.github.com/en/github/getting-started-with-github/fork-a-repo)
- [Cloning a Repo](https://help.github.com/en/desktop/contributing-to-projects/creating-an-issue-or-pull-request)
- [How to create a Pull Request](https://opensource.com/article/19/7/create-pull-request-github)
- [Getting started with Git and GitHub](https://towardsdatascience.com/getting-started-with-git-and-github-6fcd0f2d4ac6)
  


	 <p align="right">(<a href="#top">back to top</a>)</p>


<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------------ -->
