# Assignment 12: CI & CD 

## Instructions
In this assignment you'll be using GitHub actions to check your code for errors (i.e. "linting"), invite collaborators into your project and have them approve your development work before merging it with the main code. Please complete the following steps and review the rubric before getting evaluated.

---

- If you don't already have a GitHub account, please create a free one.
- Create a new repository and name it anything you like, but keep it professional.
- Follow the steps from the following video to add a Super-Linter GitHub action that checks your code anytime it is merged or committed.
  - Instead of using the YAML action code from the video (it's outdated), please simply copy and paste the example code from here and you shouldn't have to change anything for it to work.
  - Commit the GitHub action code to the "main" branch.
  - Verify that Super-Linter runs successfully.
  - This is only ONE example of the types of actions you could run on your code as part of continuous integration. You could just as easily run your code through a series of unit tests in addition to linting, as part of a CI workflow.
- Create a new "dev" branch off the main branch. This is where all development should take place, then any changes should be approved by other team members before being merged back into the "main" branch, where they'll be linted.
- Invite at least one of your classmates into your project as a collaborator and make sure they have accepted the invitation before proceeding.
- Watch this video to gain a better understanding of the peer review workflow.
- Add a new README.md file and write something in it, then commit it to the "dev" branch.
- Create a pull request and add your classmate as the reviewer.
- Your classmate should review the file and accept the changes, adding any comments they like.
- Merge the pull request back into the "main" branch, which should then trigger the Super-Linter.
- Verify the Super-Linter process completed successfully. If there are issues, resolve them before getting evaluated.
- Ask your classmates or your instructor if you're stuck on something.
- During evaluation, show your instructor the actions history for your project, the pull requests page and the collaborators page.
