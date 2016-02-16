# GitHub web plus app workflow
My GitHub workflow for creating Pull Requests on other people's repos.

From: https://github.com/cclauss/GitHub-web-plus-app-workflow

These instructions should help when you want to contribute Pull Requests to a GitHub repository that you do _not have write access_ to.  This is a step-by-step process for using the http://github.com website and the [GitHub Desktop app][] to make a local __Fork__ of a repository and then make code or documentation changes and then __Commit__ those changes and send a __Pull Request__ to the repo's owner.  The approach here is just to use the GitHub web pages and the [GitHub Desktop app][] and not use git commands on the commandline which I find difficult to remember how to use.

I will assume that you have:
* a working webbrowser
* a GitHub ID
* [GitHub Desktop app][] installed and configured with your GitHub ID.

In your web browser:
* Navigate to the [GitHub webpage][] of a repo that you want to contribute to
* Click the "__Fork__" button at the upper right corner of the page
* Click the "__Save local__" icon (a computer with down arrow) below “Star" and “Fork" buttons and just to the left of the “Download ZIP” button

In the [GitHub Desktop app][]:
* In the Open Dialog:
  * Make a "__New Folder__" with a name to match the GitHub username of the repo owner
    * This is _optional_ but later on it will make things much easier to find
  * "__Save__" fork into user folder
* Click the "__Sync__" button (this is super important!!)
* Click the "__Add a branch__" button (this is super important!!) with a name appropriate to the kind of changes you intend to make
* Click the "__Update from master__" button (this is super important!!)
 
Ok...  You are now free to make and test changes to the files in the local directory with your favorate Editor or IDE.

Once your changes are complete and all your tests have passed...  In the [GitHub Desktop app][]:
* Add a comment to the Commit
* Click the "__Commit to <new branch>__" button (NOT to Master!”)
* Click the "__Pull Request__" button
* Add a comment to the Pull Request
* Click the "__Send Pull Request__" button

In your web browser:
* Navigate to the GitHub webpage of the repo and verify that the Pull Request is there and review all of the changes that you have made

If this does not work or is unclear, please [open an issue][].

[GitHub webpage]: http://github.com/
[GitHub Desktop app]: https://desktop.github.com/
[open an issue]: https://github.com/cclauss/GitHub-web-plus-app-workflow/issues/new
