**Pre-Creation Checklist**
- [ ] All pre-PR checks have been run and they're passing:
  - The code is linted (running `npm run lint` produces no errors or warnings).  Appending `-- --fix` to the command fixes most JavaScript problems
  - The code passes unit tests (`npm run test`)
  - The code passes e2e tests (`npm start` in one terminal and `npm run e2e` in another)
  - Modifications to the project configuration files (e.g. `package.json`) were tested by executing `rm -rf node_modules && npm i && npm start` prior to executing the above tests.
- [ ] All git commits are tidy and formatted properly:
  - The code was committed using [Commit Message Guidelines](https://github.com/angular/angular/blob/master/CONTRIBUTING.md)
  - Extraneous commits were [squashed](https://github.com/1OneTeam/1OneApp/wiki/How_to-_squash_-commits) from the log via `git rebase -i` (or equivalent)
- [ ] All changes are covered by automated tests (if applicable):
  - Unit tests:
    - The positive or 'happy' path is covered. 
    - Negative or 'sad' paths are covered (typically there are multiple sad-paths)
  - E2E tests have been updated (if applicable)
  

**Provide information that will benefit those doing this review:** _(The actual description of the code changes, including new features or relevant links, should be in the code-commit-messages under the 'long description' section, so that we retain an accurate record of the work in the codebase, not the PRs)_



**Applicable screenshots:**

