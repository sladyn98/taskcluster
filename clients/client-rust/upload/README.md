# Taskcluster Upload Support

This library is a companion to the `[docs.rs](https://docs.rs/taskcluster)` Taskcluster client, with support for uploading objects.

## Usage

See [docs.rs](https://docs.rs/taskcluster) for detailed usage information.

## Compatibility

This library is co-versioned with Taskcluster itself.
That is, a client with version x.y.z contains API methods corresponding to Taskcluster version x.y.z.
Taskcluster is careful to maintain API compatibility, and guarantees it within a major version.
That means that any client with version x.* will work against any Taskcluster services at version x.*, and is very likely to work for many other major versions of the Taskcluster services.
Any incompatibilities are noted in the [Changelog](https://github.com/taskcluster/taskcluster/blob/main/CHANGELOG.md).
