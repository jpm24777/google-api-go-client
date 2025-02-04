# v0.9.0

- Small fix to chunking retry logic such that each chunk has its own retry
  deadline, instead of unbounded retries.
- Various updates to autogenerated clients.

_Please note:_ the release version is not indicative of an individual client's
stability or version.

# v0.8.0

- Various updates to autogenerated clients.

_Please note:_ the release version is not indicative of an individual client's
stability or version.

# v0.7.0

- Various updates to autogenerated clients.

_Please note:_ the release version is not indicative of an individual client's
stability or version.

# v0.6.0

- Add support for GCP DirectPath.
- Various updates to autogenerated clients.

_Please note:_ the release version is not indicative of an individual client's
stability or version.

# v0.5.0

- Better support for google.api.HttpBody.
- Support for google.api.HttpBody in the healthcare API.
- Various updates to autogenerated clients.

_Please note:_ the release version is not indicative of an individual client's
stability or version.

# v0.4.0

- Includes a re-pin of opencensus, greatly reducing the transitive
dependency list.
- Deletes photoslibrary/v1. The photoslibrary team hopes to fully support Go in
the near future, but this autogenerated library is ready to be sunset. If you
rely on this client, please vendor this library at v0.3.2.
- Various updates to autogenerated clients.

_Please note:_ the release version is not indicative of an individual client's
stability or version.

# v0.3.2

This patch releases re-builds the go.sum. This was not possible in the
previous release.

_Please note:_ the release version is not indicative of an individual client's
stability or version.

# v0.3.1

This patch release removes github.com/golang/lint from the transitive
dependency list, resolving `go get -u` problems.

_Please note_: this release intentionally has a broken go.sum. Please use v0.3.2.

_Please note:_ the release version is not indicative of an individual client's
stability or version.

# v0.3.0

go.mod modifications, including removal of go 1.12 statement and update of
opencensus dependency.

_Please note_: the release version is not indicative of an individual client's
stability or version.

# v0.2.0

General improvements.

_Please note:_ the release version is not indicative of an individual client's
stability or version.

# v0.1.0

Initial release along with Go module support.

_Please note:_ the release version is not indicative of an individual client's
stability or version.
