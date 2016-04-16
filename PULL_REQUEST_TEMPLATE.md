## Hubble PR Checklist

- [ ] Are there migrations? 
  - [ ] Are they in a separate PR?
  - [ ] Can they be rolled back?
- [ ] Are data validations required?
  - [ ] Are they on the model?
  - [ ] Are they on the DB table(s)?
  - [ ] Are they handled with informative errors or validated in the client?
- [ ] Has this been tested?
  - [ ] Added new unit tests?
  - [ ] Tested in staging?
  - [ ] Was the [regression test plan](https://docs.google.com/document/d/1k31xIaA0Et7lD8L-TD3HlYNwrlqkfFMrGtm_DwS3isk/edit) executed (and updated if necessary)?
  - [ ] Does your change affect more than one application e.g. ss web, ss mobile, wework.com, salesforce etc… and if so have they been tested?
- [ ] Are there UI changes?
  - [ ] Are there screenshots?
- [ ] Are there two thumbs?
- [ ] Does this PR depend on any other PRs/tasks?

#### Release

- [ ] Have sanity tests been run in production?
- [ ] Honeybadger monitoring
