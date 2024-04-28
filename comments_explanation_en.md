# Quick guide to Git commit messages (only 3 types)
## Comments
When committing, the following should be considered:

### Guys
- **feat** (feature): Adds new functionality. Ex: `feat:implements login with social networks`
- **fix**: Fixes a bug. Ex: `fix:remove image loading error`
- **chore** (task): Internal or maintenance changes. `Ex: chore:update dependencies`

### Importance
- Clear and concise messages that make it easy to understand development history.
- Types help filter and search for specific commits.
- Specific messages allow changes to be easily reverted if necessary.

### Tips
- Less than 50 characters in the summary.
- Use the imperative (e.g. "Implemente" instead of "Implemented").
- Be specific about the change made.

### Example
- feat:enable optional dark mode
- fix: fixes crash when saving files
- chore: reorganize the folder structure

### Optional

- Comments in English, thus avoiding the use of accents and special characters.
- You can add the app or component to which the change belongs.

  For example: `[chore](my_app):refactor of utility functions`

## Pull Requests (PR)

The idea is to make PR creation easier for developers, for this we can list the following reasons in the description:
- **Standardization and consistency**: They guarantee that all the necessary information is included in a uniform manner, facilitating the review and understanding of the proposed changes.
- **Guidance and clarity**: They offer a predefined scheme so that collaborators know exactly what information they should provide, improving the quality of communication.
- **Time savings**: They avoid the need to write the same details repeatedly, which speeds up the process of creating and reviewing pull requests.
- **Use of media files**: Add images in case of a visual bug to make the review faster, in some cases gifs can also be added.
- Add labels, reviewers and assigned to in the description.
- Do not make PR of more than 400 lines as it becomes difficult to review.
