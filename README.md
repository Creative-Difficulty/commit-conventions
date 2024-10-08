# Alex' commit message convention

## Type of change / Prefix
***The type of change, which is applied by the commit. The emoji is the first part of the commit message.***

🛠 - A change to do with configuration files or nonspecific code changes

⚠ - A change, which is unfinished or breaks the codebase (***usually only pushed to the "dev" branch***)

⬆ - Upgrading / updating an existing dependency

🌸 - A change concerning aesthetics (e.g changing the projects name, changing icons etc.)

✨ - A small change improving developer experience or user experience

🧪 - The creation or modification of tests

✒ - Renaming a file is (one of) the only change(s) in this commit

➕ - Adding a new feature or dependency

🎉 - Something to celebrate (e.g. A new release of the project, the first x of the project etc.)

### Custom Types
Custom emojis can be used for libraries, whose icon closely resembles an emoji (e.g. 🪐 for the popular Apollo GraphQL server library).

## Message
Write your commit message in the imperative: "Fix bug" and not "Fixed
bug" or "Fixes bug." This convention matches up with commit messages
generated by commands like git merge and git revert.
