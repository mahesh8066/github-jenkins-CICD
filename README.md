# github-jenkins-CICD
GitHub Actions workflows to automate testing and deployment of a simple web project.

Objective:
Create and configure GitHub Actions workflows to automate testing and deployment of a simple web project. By the end of this assignment, you should have:
A workflow to automate testing.
(Optional) Deployment of a static site to GitHub Pages.

Prerequisites:
1.A GitHub account.
2.A repository with a simple Node.js project or similar, including a test suite.
3.(Optional) A static website (HTML/CSS/JS) to deploy to GitHub Pages.

Part 1: Setup a Test Workflow
Requirements:
1.Trigger the workflow on pushes to the main branch.
2.Actions:
oCheck out the repository.
oConfigure the environment.
oInstall dependencies.
oRun tests.
Deliverable: A /.github/workflows/test.yml (or similarly named) file that defines the above workflow.


Part 2: Add a Build/Validation Step
Requirements:
1.Run a build step after the tests pass.
2.Fail the workflow if the build fails.
Deliverable:
Update the test workflow to include a build step after the test step.


Part 3: Deploy to GitHub Pages (Optional)
Requirements:
1.Deploy only if tests and builds pass and the branch is main.
2.Use GitHub Actions to deploy the static site.
Deliverable:
Extend the test workflow or create a new workflow /.github/workflows/deploy.yml that deploys the site whenever the main branch is updated and the tests/build pass.
