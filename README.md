### Editing and publishing a2go.github.io

We use [Hugo](https://gohugo.io) for building https://a2go.github.io.

The source and published site are both found in the `master` branch. The published site is served from the
[`docs`](docs) directory.

Making changes/running locally:

* Clone this repo
* Run `go run -tags extended github.com/gohugoio/hugo serve -D` to serve locally (this will live reload)
* Once you are happy with any local changes, `go run -tags extended github.com/gohugoio/hugo --cleanDestinationDir`
* Create a PR, and check that the github action passes
* Merging the PR to `master` will cause https://a2go.github.io to be rebuilt
