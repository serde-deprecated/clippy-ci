[![Build Status]][travis]

[Build Status]: https://api.travis-ci.com/serde-rs/clippy-ci.svg?branch=master
[travis]: https://travis-ci.com/serde-rs/clippy-ci

Repos under the serde-rs org do not fail their continuous integration builds
when a Clippy lint is triggered. This is because we do not want unrelated PR
builds to fail when Clippy adds new lints.

This repo runs builds that fail on Clippy for the purpose of notification of
when there is a Clippy lint that needs to be resolved in Serde code.
