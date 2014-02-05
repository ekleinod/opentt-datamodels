# OpenTT Data Models

Here you can find data models for table tennis applications.
These resources are meant to help developing programs or apps without having to think about a suitable data model.

Remarks, suggestions, improvements, or help are welcome.

Part of the project "OpenTT", open documents and programs for table tennis.

License: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License

See file LICENSE.

### Git Repository

Details about the Git repository:
The used branches are based in the "successful git branching model" of http://nvie.com/posts/a-successful-git-branching-model/.

This means, there always are at least three branches:

1. `master` - contains deploy ready versions
2. `develop` - main development branch for merges, no active development here, just for synchronzation of the feature, release, and hotfix branches
3. `feature-<model>-work` - main working branch, one for each data model

Additionally, the following branches are used, if needed:

- `feature-<model>-*` - for developing a special feature
- `release-<model>-*` - synchronization of ready made versions between `develop` and `master`
- `hotfix-<model>-*` - hotfixes
