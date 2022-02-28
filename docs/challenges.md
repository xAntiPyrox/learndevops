# Challenges I've Solved

This document is intended to be an ongoing log of challenges I have faced over the course of this project and how I resolved them. The challenges are added as I encounter them and are updated as they get resolved. They are not organized in any other manner.

### (27-FEB-22) Authenticating with GitHub

**Problem:** When making my first push from my local machine to this repository with GitHub, I couldn't get authentication to work. Neither the automated system in VS Code to sync with my GitHub account nor manually typing in my username and password when prompted seemed to work as expected.

**Solution:** Adding an access token to the GitHub remote URL allowed for seamless authentication without the need of a username or password.

1. How to generate an access token in GitHub: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token
2. Solution found in Stack Overflow: https://stackoverflow.com/a/69662470

### (27-FEB-22) Markdown Highlighting

**Problem:** It appears GitHub does not recognize standard markdown for highlighting (e.g. "==text==") as described here: https://www.markdownguide.org/extended-syntax/#highlight. This makes the highlighting for integrated technologies in the [tech stack document](tech_stack.md) incorrect and leaves the "=" characters.

**Solution:** Changing the markdown to `<mark></mark>` (an alternative when the viewer supports HTML) resolved the issue. I also found the following VS Code extension helpful for previewing changes:
[Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)