## Open Source Debugging Project

- Project: [`hub4j/github-api`](https://github.com/hub4j/github-api)
- Issue: [#2035 GHCommitPointer throws NPE on null repository](https://github.com/hub4j/github-api/issues/2035)
- My PR: [#2265 Fix GHCommitPointer null repository path and add regression test](https://github.com/hub4j/github-api/pull/2265)

What I did:
- Traced root cause for null repository path
- Added regression test `GHCommitPointerTest#nullRepoNpe`
- Implemented null check fix in `GHCommitPointer#getCommit`
- Verified targeted test passes
