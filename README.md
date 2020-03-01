# AndroidArtifactoryProvider

Step by step approach to share your good work to community using Github and Jitpack.

- Create new Android project.

- Create new Android library module which shares your code.
<img src="publish_config.png" width="750" height="400">

- perform gradle sync and push source code to github repo.

- Create a new release by creating a new version tag, as specified in second step ie., version_number.
<img src="add_gitgub_tag.png" width="450" height="400">

- Goto jitpack.io, copy github repo location lookup release tag
ie., https://github.com/LearnKotlin/AndroidArtifactoryProvider
Press "Get it" and wait till loading is complete and artifactory is built
<img src="build_artifactory_jitpack.png" width="450" height="400">





