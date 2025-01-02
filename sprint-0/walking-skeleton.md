# Setup Walking Skeleton

Before diving into development, set up a "walking skeleton" – a minimal end-to-end implementation of your software that encompasses the core architecture and necessary integrations. This helps identify and resolve setup-related challenges early.

## Setup Tools and Integration

-   Utilize essential development tools and integrations to streamline your workflow.

    -   Choose a reliable [Source Code Repository (SCM provider)](https://www.atlassian.com/git/tutorials/what-is-version-control).
    -   Utilize a [Container Registry](https://cloud.google.com/container-registry) for storing and distributing Docker images.
    -   Implement Continuous Integration ([CI](https://www.thoughtworks.com/continuous-integration)) pipelines to automate building and testing code.

## MonoRepo vs Individual Repos

-   Decide between using a [Monorepo](https://www.toptal.com/front-end/guide-to-monorepos) or maintaining individual repositories for your projects.

## Static Analysis

-   Integrate [static analysis tools](https://www.sonarqube.org/) to identify code quality issues early in the development process.

## Testing

-   Implement thorough [testing practices](https://martinfowler.com/testing/) to ensure the functionality and reliability of your software. [Read more](../sprint-1-n/testing.md). A walking skeleton needs to have just enough testing to start with.

## Coverage

-   Measure and enforce [code coverage](https://codecov.io/) to ensure your tests cover a significant portion of your codebase.

## Standardized Local Development Environment

-   Establish a standardized [local development environment](https://www.docker.com/resources/what-container) using tools like Docker to ensure consistency across the team.

## Deployment

-   Set up a development deployment environment to facilitate continuous integration and testing.

## Database Migration Tool

-   Utilize a [database migration tool](https://flywaydb.org/) to manage schema changes and updates seamlessly.
