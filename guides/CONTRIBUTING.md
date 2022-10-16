# Contributing Guidelines
First off, thank you very much for visiting and taking the time to contribute.

## How Can I Contribute?

### Suggestions
This section guides you through submitting an enhancement suggestion, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion and find related suggestions.

Since GitHub Issue forms we only suggest you to include most information possible.

You can see issues to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

> **Note**: If you find a Closed issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

### Pull Requests
The process described here have several goals:

* Maintain the project quality
* Fix problems that are important to users
* Engage the community in working toward the best possible outcome!
* Enable a sustainable system for maintainers to review contributions.

## Style Guide for Git Commit Messages

* Use the present tense. (Example: "Add feature" instead of "Added feature")
* Use the imperative mood. (Example: "Move item to...", instead of "Moves item to...")
* Limit the first line (also called the Subject Line) to 50 characters or less.
* Capitalize the Subject Line.
* Separate subject from body with a blank line.
* Do not end the subject line with a period.
* Wrap the body at 72 characters.
* Use the body to explain the what, why, vs, and how.
* Reference [issues](https://github.com/ankerapp/anker-app/issues) and [pull requests](https://github.com/ankerapp/anker-app/pulls) liberally after the first line.
* Follow the [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) guidelines

## How to Contribute
* Please create an [issue](https://github.com/ankerapp/anker-app/issues) before creating a pull request.
* Fork the repository and create a branch for any issue that you are working on.
* Create a pull request which will be reviewed and suggestions would be provided.
* Add Screenshots to help us know what changes you have done.

## How to Make a Pull Request

1. Fork the right repository
    * Fork [this](https://github.com/ankerapp/anker-app) repository
    * If you want to work on the main repo then fork the repository
        above
    * If you want to make only SCSS themes then also fork [this](https://github.com/ankerapp/anker-themes) repo

2. Clone the forked repository
```bash
git clone https://github.com/<your-username>/anker-app.git
git clone https://github.com/<your-username>/anker-themes.git
```

3. Navigate to the project directory
```bash
cd anker-app
```

4. Create a new branch
Kindly give your branch a more descriptive name like `feat-add-dropdown` instead of `patch-1`.

You could follow this convention. Some ideas to get you started:
* Feature Updates: `feat-<2-3-Words-Description>-<ISSUE_NO>`
* Bug Fixes: `fix-<2-3-Words-Description>-<ISSUE_NO>`
* Documentation: `docs-<2-3-Words-Description>-<ISSUE_NO>`
* And so on...
```bash
git checkout -b your-branch-name
```

5. Add your changes, please follow the following guidelines
* Search previous Pull Requests or Issues before making new one, as yours may
    be a duplicate.
* There are two things you can work on the [main
    app](https://github.com/ankerapp/anker-app) and [themes](https://github.com/ankerapp/anker-themes)
* Changes to the main app will be reviewed thoroughly so make sure you only
    make changes if there is an Issue for it. The Issues are created by the
    maintainers. Please don't make any Issue regarding the main app before
    discussing it with the maintainers.
* If you have an idea for a theme you can create an Issue for it without
    discussing it with the maintainers. Following guidlines apply to submitting
    a theme:
    * At the moment only SCSS based themes can be made
    * Please make sure your theme follow the instructions mentioned
        [here](https://github.com/ankerapp/anker-app#how)
    * When you're done with the theme please follow guidelines below:
        * Give your theme a name e.g `_example.scss`. For reference see [this](https://github.com/ankerapp/anker-themes/tree/master/hacktoberfest-2022) repository
        * Create a directory for your theme with that name
        * Put the theme file in the directory
        * Take screenshots for different devices
        * Create a `README.md` file
        * Put your screenshots in `README.md` file also your instructions
            if needed
        * For reference see [this](https://github.com/ankerapp/anker-themes/tree/master/hacktoberfest-2022) repository

6. Stage your changes and commit
```bash
git add . # Stages all the changes
git commit -m "<your_commit_message>"
```
Follow our commit guide from above!

7. Push your local commits to the remote repository
```bash
git push origin <your-branch-name>
```

8. Create a new [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) from `<your-branch-name>`

9. Congratulations! You've made your first pull request! Now, you should just wait until the maintainers review your pull request.

# Important

### Good Practice
* Comment on the issue to get assigned
* Create an issue before you make a Pull Request

### Bad Practice
* Creating Pull Requests without assignments will not be accepted and will be
    closed.
