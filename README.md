# Code for Dissonanssi.fi site

This repository contains the source code for the public website of https://dissonanssi.fi.

## How to do changes?

You will need to have a GitHub account to propose changes. If you don't have one, go to https://github.com/join and create one.

There are two main ways to do changes, with the easiest one using only your browser and not having to learn git.

### Changing the contents using GitHub UI

When you are logged in, locate the file you want to edit from the GitHub UI and click on the "Edit" icon (it looks like a pencil) right above the source code.

Do the changes you want and then propose a file change. Write a small note saying what you did, preferably in English but Finnish is OK too, and then click "Propose file change". Continue to to create a pull request.

Once a pull request is opened, [Netlify](https://www.netlify.com/) will post a unique URL in the pull request where your changes are visible. See https://github.com/Dissonanssi/dissonanssi.fi/pull/1 for an example pull request, where the changes were visible in [https://deploy-preview-1--dissonanssi.netlify.com/](https://deploy-preview-1--dissonanssi.netlify.com/)

You can do changes in your pull request using the UI as much as you want to. Netlify will update the deploy preview site after each new change is committed.

Now somebody with write access can check out your changes and merge your pull request if the changes look good. Once a pull request is merged, https://dissonanssi.fi will automatically update to contain the latest changes.

### Changing the contents using git

[Fork](https://help.github.com/en/articles/about-forks) the repository to your own GitHub account to do changes. Then checkout your own fork with something like [GitHub Desktop](https://desktop.github.com/) to your machine.

Open up `public/index.html` in your browser of choice. Do changes with any text editor (e.g. [Visual Studio Code](https://code.visualstudio.com/)) to that file. Reload your browser to see the changes.

Once you're content with your changes, [create a new branch for your changes](https://help.github.com/en/desktop/contributing-to-projects/creating-a-branch-for-your-work) and commit your changes. Push your changes to your own fork.

Now you should see a button to open a new pull request in https://github.com/Dissonanssi/dissonanssi.fi page. When you open a pull request, [Netlify](https://www.netlify.com/) will post a unique URL with your changes to the pull request as a new comment. See https://github.com/Dissonanssi/dissonanssi.fi/pull/1 for an example pull request, where the changes were visible in [https://deploy-preview-1--dissonanssi.netlify.com/](https://deploy-preview-1--dissonanssi.netlify.com/)

You can keep doing new changes and commits and push those commits to your branch. Netlify will update the deploy preview site every time new commits are pushed and the open pull request is updated.
