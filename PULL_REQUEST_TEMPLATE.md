## Hubble PR Checklist

#### validation
- [ ] Has this been tested?
- [ ] Tested in staging?
- [ ] Are there two thumbs?

#### migration
- [ ] Are there migrations?
- [ ] Are they in a separate PR?
- [ ] Can they be rolled back?
- [ ] Was the regression test plan executed (and updated if necessary)?

#### dependencies
- [ ] Does your change affect more than one application e.g. ss web, ss mobile, wework.com, salesforce etc… and if so have they been tested?
- [ ] Does this PR depend on any other PRs/tasks?

#### testing
- [ ] Added new unit tests?

#### UI
- [ ] Are there UI changes? If so, please include screen shots in the PR
- [ ] Are there screenshots if this is a UI related change?

#### data integrity
- [ ] Are data validations required?
- [ ] Are they on the model?
- [ ] Are they on the DB table(s)?
- [ ] Are they handled with informative errors or validated in the client?

## Release

- [ ] Have sanity tests been run in production?
- [ ] Honeybadger monitoring
