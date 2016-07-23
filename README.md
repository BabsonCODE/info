# Babson CODE Development Workflow

	## Setting Up Your Local Environment
	All of our projects currently use a LAMP stack (Linux, Apache, MySQL, and PHP). [MAMP](https://www.mamp.info) for Mac and [WAMP](http://www.wampserver.com/en/) for Windows are easy ways to set up a local development environment.

	We use GitHub for version control (obviously), so you'll also need to [set that up](https://help.github.com/articles/set-up-git/). To get a better understanding of git and version control, Atlassian has [some awesome written tutorials](https://www.atlassian.com/git/tutorials/) and [Code School has a great interactive one](https://www.codeschool.com/courses/try-git).

	## Making Changes to a Project
		### Branching
		No code should be changed directly on the master branch. Always branch off of master to make your changes so you can open a pull request later on. You can create and check out a new branch in one step with `git checkout -b your_branch_name_here`.

		### Pull Requests
		When you are satisfied with the code you've written, push your local branch to a remote branch of the same name. If your branch is called `make_code_great_again`, you would then `git push origin make_code_great_again`). When you go to the repository on GitHub, you should see a prompt to open a pull request. Enter a brief description of what you changed so people reviewing your code know what the objective was. We don't currently have agile scrum software set up, but if we did you could paste a link to the relevant story. Also, be sure to address any merge conflicts.

		### Code Reviews
		No code is merged to master without first going through a code review. This consists of other developers going through the code in your pull request to make sure it's solid. This is one of the most effective ways for all of us to improve as we are forced to give and receive constructive feedback. Once another developer has given the okay (such as by leaving a comment with a thumbs up), you are good to merge. Also be sure to delete the branch after merging to keep the repository clean.

	## Deployment (TODO)
	We are very fortunate to be sponsored by Digital Ocean, which we use to host many of our projects.