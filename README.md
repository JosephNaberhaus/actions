# Actions
Collection of reusable Github Actions for personal use.

There are better alternatives to everything here. I just didn't like the practice of pull in random third-party actions into my projects. In this repo, I only use the actions provided by Github themselves. 

## release-go-binaries
Builds a go binary and uploads it as an artifact. Will also upload it to the release if that's what triggered the run.

[Example Usage](.github/workflows/test-release-go-binaries.yaml)g