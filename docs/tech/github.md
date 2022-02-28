# GitHub


## Summary

GitHub is a software repository version control web application using [Git](git.md) as a backend to enable remote repository management and collaboration. 

## Project Details

This technology was automatically chosen to be incorporated into this project as it is a requirement for my current job to use this to maintain and version application code. Therefore, no other remote version control technology will be considered for this project.

## Notes

**(27-FEB-22):** One of the things I want to do in the repository for this project is establish three main branches:

- prod: production branch intended to be the exact code that is executing in production
- qa: quality assurance/pre-production branch intended to be the next version of code to be released in production, with a dedicated pre-prod environment for testing
- dev: the most volatile branch with the latest changes of the code and testing performed on developer machines locally

All of these branches would be locked from pushing/merging and must be updated using a pull request. Developers would only branch from dev and submit a pull request to bring their changes back to dev when they complete them.

## Resources

- [Homepage](https://github.com/)
- [Documentation](https://docs.github.com/en)