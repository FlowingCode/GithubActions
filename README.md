# GithubActions

### check-commits

- Check commits against [Flowing Code Conventional Commits guidelines](https://github.com/FlowingCode/DevelopmentConventions/blob/main/conventional-commits.md) (see 
[action-conventional-commits](https://github.com/FlowingCode/action-conventional-commits) for details).

- Verify that the Semantic Versioning change level is consistent with the version in POM:
	- Pull Requests with breaking changes must target a new MAJOR version (x.0.0).
	- Pull Requests with new features or deprecations must target a new MINOR version (x.y.0).
