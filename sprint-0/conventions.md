# Conventions

## Code Formatting

-   Define and follow consistent code formatting rules using tools like [Prettier](https://prettier.io/) or [ESLint](https://eslint.org/) to maintain a clean and readable codebase.

## Commit Message Conventions

-   Use [conventional commits](https://www.conventionalcommits.org/) to provide clear context about changes in a standardized format.

    -   Implement [commit hooks](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks) to ensure consistent formatting and conventions.

## Branching / Merging Strategy

-   Determine an effective [branching strategy](https://www.atlassian.com/git/tutorials/comparing-workflows) that suits your team's workflow and project needs. Two common approaches are:

    -   **Trunk-based development**: Keep the main branch always deployable and encourage frequent integrations.
    -   **Feature branch-based development**: Isolate features in separate branches for development, promoting parallel work.

## Branch Naming Conventions

-   Define meaningful [branch naming conventions](https://dev.to/couchcamote/git-branch-name-conventions-and-tips-36he) to enhance clarity and organization.

## Pull Requests

-   Use pull requests as a key part of the development workflow.

    -   Provide a PR template to ensure essential information is included.
    -   Decide whether to have a mandatory reviewer or allow asynchronous reviews.
    -   Set guidelines for PR size and avoid long-lived, "blessed" PRs.
    -   Establish PR checks to ensure code quality and functionality:
    -   Require at least one mandatory reviewer for each PR.
    -   Allow asynchronous reviews for faster feedback while considering [best practices](https://saltmarch.com/watch/code-review-you-said).

        -   Include [static code analysis](https://www.sonarqube.org/) tools.
        -   Build and run comprehensive [unit and integration tests](https://martinfowler.com/bliki/UnitTest.html).
        -   Consider [test impact analysis](https://www.mabl.com/blog/test-impact-analysis-101) tools.
        -   Measure and enforce [code coverage](https://codecov.io/).
        -   Address and respond to review comments effectively.

## Merge Strategy

-   Choose an appropriate merge strategy when integrating changes.

    -   Decide between [squashing commits](https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History) or maintaining them separately.
    -   Compare [rebase and merge](https://www.atlassian.com/git/tutorials/merging-vs-rebasing) strategies based on your project's needs.
