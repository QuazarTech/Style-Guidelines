## Submitting a Pull Request:

The following guidelines need to be followed while submitting a pull request:

- Ensure that each PR contains only one particular feature. Different PRs are to be opened for different features. The goal is to limit the number of changes in each PR to make the review process easier. 

- Make your changes in a new git branch
`git checkout -b my-feature-branch master`

- It is recommended that you open the PR after your 1st commit to the branch. This way the commits that come in are tracked and don't result in a deluge at the end

- Make sure to include test cases for the added patch(wherever possible).

- Follow our [code guidelines](https://github.com/QuazarTech/Style-Guidelines/tree/master/code_guidelines)

- Make sure changes use a descriptive commit message. Do not use vague comments like 'Bug Fixed'. Rather ensure that the commit message also includes information about the file in which the bug was found, along with a brief description of the issue.
