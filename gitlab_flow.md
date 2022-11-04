# GitLab Flow

## What is GitLab Flow?
GitLab Flow is a simpler alternative to GitFlow and combines feature driven development and feature branches with issue tracking. With GitLab Flow, all features and fixes go to the main branch while enabling production and stable branches. GitLab Flow includes a set of best practices and guidelines to ensure software development teams follow a smooth process to ship features collaboratively.

## How does GitLab Flow work?
With GitFlow, developers create a develop branch and make that the default, while GitLab Flow works with the ‘main’ branch right away. GitLab Flow incorporates a pre-production branch to make bug fixes before merging changes back to main before going to production. Teams can add as many pre-production branches as needed — for example, from main to test, from test to acceptance, and from acceptance to production.

## Essentially, teams practice feature branching, while also maintaining a separate production branch. Whenever the ‘main’ branch is ready to be deployed, users merge it into the production branch and release. GitLab Flow is often used with release branches. Teams that require a public API may need to maintain different versions. Using GitLab Flow, teams can make a v1 branch and a v2 branch that can be maintained individually, which can be helpful if the team identifies a bug during code reviews that goes back to v1.

## What are the benefits of GitLab Flow?
GitLab Flow offers a simple, transparent, and effective way to work with Git. Using GitLab Flow, developers can collaborate on and maintain several versions of software in different environments. GitLab Flow decreases the overhead of releasing, tagging, and merging, which is a common challenge encountered with other types of Git workflows, to create an easier way to deploy code. Commits flow downstream to ensure that every line of code is tested in all environments. Teams of any size can use GitLab FLow, and it has the flexibility to adapt to various needs and challenges.
