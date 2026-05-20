

# Git Commit


## Commit Message Guidelines


### Commit Message Format

Each commit message consists of a header, a body and a footer. The header has a special format that includes a type, a scope and a subject:  

    <type>(<scope>): <subject>
    <BLANK LINE>
    <body>
    <BLANK LINE>
    <footer>

The type and subject of the header are mandatory. The scope of the header is optional.  


### Commit Type Prefix (must)

Prefix should be one of the following:  

-   `build:` A change that affect the build system or external dependencies
-   `ci:` A change to CI configuration files and scripts
-   `docs:` documentation change
-   `fix:` bug fix
-   `feat:` Adding new feature
-   `perf:` Performance improvements
-   `refactor:` A change that neither fixes a bug nor adds a feature
-   `style:` A change that do not affect the meaning of the code (white-space, formatting, missing semic-colons, etc)
-   `test:` Adding missing or correcting existing tests

-   `revert:` when you revert


### Commit Scope (optional)

The scope should be the name of the npm package affected (as perceived by the person reading the changelog generated from commit messages.  

The following is the list of supported scopes:  

-   animations
-   common
-   compiler
-   compiler-cli
-   core
-   elements
-   forms
-   http
-   language-service
-   platform-browser
-   platform-browser-dynamic
-   platform-webworker
-   platform-webworker-dynamic
-   router
-   service-worker
-   upgrade

There are currently a few exceptions to the "use package name" rule:  

-   packaging: used for changes that change the npm package layout in all of our packages, e.g. public path changes, package.json changes done to all packages, d.ts file/format changes, changes to bundles, etc.
-   changelog: used for updating the release notes in CHANGELOG.md
-   aio: used for docs-app (angular.io) related changes within the /aio directory of the repo
-   none/empty string: useful for style, test and refactor changes that are done across all packages (e.g. style: add missing semicolons)


### Commit Subject (must)

This is a very short description of the change.  

-   Use the imperative, present tense: "change" not "changed" nor "changes"
-   Don't capitalize the first letter
-   No period dot (.) at the end


### Commit Message Body (desired)

-   Use the imperative, present tense: "change" not "changed" nor "changes".
-   Explain the motivation for the change and contrast this with previous behavior.
-   When reverting, the body should be "This reverts commit <hash>", where the hash is the SHA of the commit being reverted.


### Commit Footer (if neccesary)

The footer should contain any information about Breaking Changes.  

The footer should contain references to GitHub issues that this commit Closes.  

Breaking Changes should start with the word BREAKING CHANGE: with a space or two newlines. The rest of the commit message is then used for this.  

-   `!` or  `BREAKING CHANGE:` A code that introduces a breaking change
-   `Closes #123`  or if there are multiple, `Closes #123, #456, #789`


### Reference

See more information:  

1.  <https://www.conventionalcommits.org/en/v1.0.0/>
2.  <https://docs.google.com/document/d/1QrDFcIiPjSLDn3EL15IJygNPiHORgU1_OOAqWjiDU5Y/edit>
3.  <https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines>

