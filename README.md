# Actions
Collection of reusable Github Actions for personal use.

There are better alternatives to everything here. I just didn't like the practice of pulling in third-party actions into my projects. In this repo, I only use the actions provided by Github themselves. 

## go-check-formatting
Ensures that the code has been formatted with [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports).

[Example usage](.github/workflows/test-go-check-formatting.yaml)

## go-test
Runs all go unit tests and makes sure that they pass.

[Example usage](.github/workflows/test-go-test.yaml)

## release-go-binary
Builds a go binary and uploads it as an artifact. Will also upload it to the release if that's what triggered the run.

[Example Usage](.github/workflows/test-release-go-binary.yaml)