# Operations

*This document is still in draft stage!*

Documentation and common resources for development processes

# How Does This Work?

StarChart Labs is about creating a consistent process around development, and making it easier to "do things right". For us, "right" means libraries and tools that are easy to consume, stable, and make it easier to focus on the primary aim of the consuming project. Working towards this goal can be as simple as ensuring tests are written, or as complex as standardizing build and deployment processes.

Like many organizations, StarChart Labs is constantly tweaking how we operate, and rolling out changes we find helpful across our wide range of projects. Part of the process is also identifying the maturity of a project, and when it's worth the effort to apply certain practices. We are constantly trying to find ways to automate standards and checks, to improve consistency and let the humans get on with human work, instead of being bogged down in repetative work.

# Lab Procedure

Our current best-practice process(s)

## Writing Code

- Pull requests should be small and focused to specific issues or improvements
- Tests should be present for new functionality, and to ensure fixed bugs do not regress
- Source files should follow consistent formatting pattern(s)
- APIs meant for external consumption should be documented
- If breaking changes are made, the old and new methodologies should both exist at some point in time, and deprecation documentation on the old method should include details on how to migrate
- TODOs should not be added unless associated with an issue
- Code quality guidelines should be established and enforced prior to merge
- Change log entries for changes should be added at the time the change is applied
- Pull requests are compiled and tested prior to merge
- Pull requests will be assigned/commented on to/by a maintainer within a week of filing

## Documentation

All projects have some basic documentation

- A README which includes
  - A summary or one-line description of what the purpose of the project is
  - Information on licensing, including steps required by clients to use the library or it's source
  - Information on reporting vulnerabilities
- Guidelines for contributors on setting up for development and requirements for pull requests
- Guidelines for collaborators on handling pull requests, interacting with the community, and releasing the project
- A code of conduct which outlines what community members can expect and establishes an expectation of respect
- A Change log detailing the changes applied within each release of the project
- If breaking changes have been made in the project's history, information on how to migrate from older to newer versions

## Releases

- Projects follow semantic versioning: no breaking changes are made except across major release numbers, and with prior warning/documentation via deprecation or appropriate mechanisms
- Library releases should include source artifacts

## Communication

- Releases should be communicated in a designated channel with information on the changes made
- Social media actions should be notified in a channel to allow everyone to keep tabs on what is being done

# State of the Labs: How It's Implemented

TODO

## Documentation

- Files at the root of a project's repository
  - README
  - CHANGE_LOG
- Files in a `docs` folder
  - CONTRIBUTING
    - Details expectations for contributors and how to setup development
  - COLLABORATORS
    - Details information such as handling contributions and releasing the projects
  - Supporting documentation linked from the README

# Looking Forward: What Can We Improve

TODO
