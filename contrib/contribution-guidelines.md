# Elite Dangerous Pilot's Network - Contribution Guidelines

## What do I need to know to help?
As our organization spans multiple subprojects, each one uses its own unique technology stack, including various programming languages, frameworks, or tools. Familiarize yourself with the specific technologies used in the subproject you're interested in by checking the README file or the project's documentation.

## How do I make a contribution?
Here's a detailed overview of how to contribute code or documentation:

1. Find (or create) an issue that you are interested in addressing or a feature that you would like to add in the subproject you're focusing on. Refer to the [guidelines](#issue-creation-and-linking) for more information and check the GitHub issues page of the relevant project.
2. Fork the repository associated with the issue to your local GitHub organization. This means that you will have a copy of the repository under `your-GitHub-username/repository-name`.
3. Clone the repository to your local machine using `git clone https://github.com/github-username/repository-name.git`.
4. Create a new branch for your fix using `git checkout -b {issue-number}-branch-name-here`, make sure to include the issue number in your branch name.
5. Make the appropriate changes for the issue you are trying to address or the feature that you want to add. Make sure to comply with our git commit best practices, listed [here](https://github.com/trein/dev-best-practices/wiki/Git-Commit-Best-Practices).
6. Use `git add insert-paths-of-changed-files-here` to add the file contents of the changed files to the "snapshot" git uses to manage the state of the project, also known as the index.
7. Use `git commit -m "{issue-numer} Insert a short message of the changes made here"` to store the contents of the index with a descriptive message. Make sure to include the issue number as the first part of the message. This way we can more easily track which changes were made in function of which ticket.
8. Push the changes to the remote repository using `git push origin issue-number}-branch-name-here`.
9. Submit a pull request to the upstream repository.
10. Title the pull request with a short description of the changes made and the issue or bug number associated with your change.
11. In the description of the pull request, explain the changes that you made, any issues you think exist with the pull request you made, and any questions you have for the maintainer. It's OK if your pull request is not perfect (no pull request is), the reviewer will be able to help you fix any problems and improve it!
12. The pull request needs to be approved by at least two people, one of whom needs to be the relevant domain's workgroup lead or part of the steering committee.
13. Make changes to the pull request if the reviewing maintainer recommends them.
14. Celebrate your success after your pull request is merged!

If you are a project maintainer: You don't need to fork the repository. Instead, create a new branch on the project repository itself.

Before you contribute, please confirm that your contribution is made under the terms of the license found in the root directory of the relevant subproject’s source tree and that you have the authority necessary to make this contribution on behalf of its copyright owner.

## Issue Creation and Linking:
All significant changes should be linked to a relevant issue that explains the "what" and "why" of the change. Minor changes, like spelling corrections, are exceptions.

As a contributor, check if a relevant issue already exists before you start work on a change. If no appropriate issue exists, create one. If an issue does exist, mark it as in progress either by assigning yourself (if you're a project maintainer) or by commenting on it to mention that you've forked the project to work on it.

This approach ensures that all contributions are tied to specific objectives and provides context and rationale for the proposed changes.

## Where can I go for help?
If you need help, feel free to ask questions on our [Discord server](https://discord.gg/vAAT7cAjKx).

## What does the Code of Conduct mean for me?
Our Code of Conduct means that you are responsible for treating everyone on the project with respect and courtesy, regardless of their identity. If you are the victim of inappropriate behavior or comments as described in our Code of Conduct, we are here for you. We will do our best to ensure that the perpetrator is appropriately reprimanded. You can read our full Code of Conduct [here](https://github.com/ed-pilots-network/charter/blob/main/community/community-standards.md).
