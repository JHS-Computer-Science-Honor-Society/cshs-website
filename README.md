# Henry M. Jackson Computer Science Honor Society

## Set Up

### Prerequisites

You will need:

- [Node](https://nodejs.org/en)
- [Visual Studio Code](https://code.visualstudio.com)

### Set up

Open Terminal/CMD in your desired folder and run the following line of code:

```
git clone https://github.com/JHS-Computer-Science-Honor-Society/cshs-website.git
```

Go into the folder using the following command:

```
cd cshs-website
```

Type the following command to install all packages

```
npm i
```

## Collaboration

## Issues

Any work that has to happen on the website will be created into an issue. Issues are assigned to developers and their main focus is to work only on that part of the website.

Each issue is also linked to a GitHub branch. Make sure that all code is edited on that branch and it is the developer's responsiblity to make sure that branch is up to date with `main`.

## Pull Requests

Pull requests are the main way for your code to enter the production line. Once you have edited and pushed changes to your branch, please navigate to the Pull Requests tab and create a new pull request.

Here are the steps:

- Click on "New Pull Request"
- Select the branch you were working on (the same one linked to your issue)
- Click on "Create Pull Request"

From there, someone will review your code to make sure that it functions. Once the review passes, we will merge your code into the production branch.

### Why so complicated?

The `main` branch will be deployed into production. The consumer will see whatever the code in `main` is written to. If one bug from a "work in progress" assignment is deployed, it could bring down production and make it hard to revert. Protecting the `main` branch makes it a more pleasant experience for the consumer as well as the developer.
