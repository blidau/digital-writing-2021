# Create and Publish a Twine Story

## Prerequisites 

Install GitHub Desktop, open it and connect it to your GitHub account. Ideally use Twine locally so you don’t lose any of your work, but you can also use the online version.

### Accounts

Make sure you have set up accounts on the following sites. Use your GitHub account to sign up to Netlify.

* [GitHub account](https://github.com/)
* [Netlify account](https://www.netlify.com/)

### Install
* [GitHub Desktop](https://desktop.github.com/)
* [Twine](https://twinery.org/)

## Set Up a Local Repository

To save a history of your changes to your story and to allow you to easily publish it online you will need to set up a repository.

1. Create a local folder/directory for all your projects on your computer. Every time you start a new repository you will want to create it in this folder. Call it anything you like but easy to find like `digital-writing-projects`.
2. Go to GitHub Desktop and create a new repository. Give it the name `digital-writing-twine` and for the "Local Path" select the folder you created in the previous step. Select the "Initialize this repository with a README" checkbox and click "Create Repository".

## Create a Twine Story

In Twine you will need to create a story, add a passage and save the commit in GitHub Desktop.

1. Open Twine and select "+ Story". Call the story anything you want.
2. An "Untitled Passage" will be present. Double-click on the passage. 
3. Change the title from "Untitled Passage" to another name and edit the passage content. Close the passage.
4. In the bottom right of Twine click the title of your story to reveal the menu.
5. Select "Publish to File" and navigate to the repository that you created. There should only be a "README.md" in the directory. Save your file as `index.html` (this is very important as when the story is published on Netlify it will make it easier to navigate to).
6. Go to GitHub Desktop and your repository should show changes. Add the comment "Add first passage" where "Summary (required)" is shown and click "Commit to main".

## Add Another Twine Passage

Add one more passage to Twine.

1. Go back to your Twine story and open the first passage by double-clicking on it.
2. Select the text you want to link to the next passage and put two square brackets on either side. So if the text is "You are sitting in a park" and you want the link to be the word "park" the edited text should look like "You are sitting in a [[park]]" and then close the passage.
3. A second passage should now appear. Double-click on the second passage and add text to the passage.
4. Select "Publish to File". Select the `index.html` in your Twine story folder and save over it.
5. Go to GitHub Desktop and your repository should show changes. Add the comment "Add second passage" where "Summary (required)" is shown and click "Commit to main".

## Publish to GitHub

Publish your repository to GitHub.

1. Go to GitHub Desktop and in the top row select "Publish repository".
2. Uncheck "Keep this code private" (this should be public so that it can be part of your folio).
3. Click "Publish Repository".
4. Go to GitHub in your web browser and confirm that the repository is there.

## Deploy Via Netlify

We now use the repository on GitHub to deploy the site with Netlify.

1. Go to Netlify and select "New site from Git".
2. Select "GitHub" for your Git provider.
3. Under "Pick a repository" select your repository.
4. Under "Site settings, and deploy!" leave all settings as default and click "Deploy site"

Your Twine story should now be published. Every time you make a change, save over the `index.html`, commit the change and push to GitHub your Twine story will deploy the changes to Netlify.
