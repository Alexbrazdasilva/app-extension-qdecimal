# Contributing guide

Hey! We are very excited about your interest in contributing to this extension.
Before submitting your contribution, please read this short guide:

- [Workflow dev](#workflow-dev)
- [Patterns for commits](#patterns-for-commits)
- [Issue reporting guidelines](#issue-reporting-guidelines)
- [Project structure](#project-structure)

# Workflow dev

To start developing new features or fixing issues in the extension, you need to:

- Check if there is an issue. If not, you can create one.
- Fork this repository;
- Clone the project in your favorite IDE;
- Develop your improvement, correction, etc;
- Add the files you changed;
- Run the command `yarn commit`

```bash
cd ./ui
yarn install
yarn dev
```

# Patterns for commits

We use git-cz, for semantic commits and a pretty changelog. It is based on the
principles of [semver](https://semver.org/). After adding your changes, you can
run `git add [files]` and `yarn commit`. Sample:

```
feat: 🎸 add new feature
```

If your commit contains many fixes or enhancements you can use description, for
example:

```bash
fix: 🐛 fix old problem
# More lines
Description: ... # Add your description here
```

> Do not add the `dev/` folder in your commits. This folder should be used as a
> sandbox for reproducing bugs and new implementations.

&nbsp;

# Issue reporting guidelines

When reporting an issue, please follow these guidelines to ensure effective
communication and efficient problem resolution:

1. **Search for existing issues**: Before submitting a new issue, search the
   issue tracker to check if a similar issue has already been reported. This
   helps avoid duplication and allows us to focus on unresolved problems.

2. **Clear and concise title**: Provide a clear and descriptive title that
   summarizes the issue. Avoid generic titles like "Help needed" or "Bug report"
   and be specific about the problem you're experiencing.

3. **Reproducible steps**: Include detailed steps to reproduce the issue. This
   helps us understand the context and reproduce the problem on our end, leading
   to quicker identification and resolution.

4. **Expected and actual behavior**: Clearly state what you expected to happen
   and what actually happened. This information helps us understand the
   deviation from expected behavior and narrow down the root cause.

5. **Environment details**: Include relevant information about your environment,
   such as the operating system, browser version, or any other dependencies
   involved. This information assists in identifying potential compatibility
   issues.

6. **Error messages or logs**: If applicable, provide any error messages,
   warnings, or relevant logs related to the issue. This can provide valuable
   insights into the problem and facilitate troubleshooting.

7. **Screenshots or code snippets**: If visual artifacts or code are relevant to
   the issue, include screenshots or code snippets that help illustrate the
   problem. This can help us better understand the context and provide targeted
   solutions. the changes visually but is not required > It can sometimes be
   very beneficial to include a code reproduction that shows

8. **Additional context**: If there is any additional information or context
   that you think might be helpful, feel free to include it. Any relevant
   details about your setup, configurations, or other factors can assist in
   resolving the issue efficiently.

We appreciate your effort in reporting issues and helping us improve the
extension. Following these guidelines will ensure that your issue is addressed
promptly and accurately. Thank you!

# Project structure
