Hermit versioning is a mix of `version` and `channel`.

**Version**

Hermit's package version comes from the packge's original git tag. The version is
an extension to semver, with an extra build number to accomondate package
versions from OpenJDK, which has a value `15.0.1_9`.

**Channel**

[Channel](https://cashapp.github.io/hermit/packaging/reference/#channels) could be hermit generated or user defined.
Channel is considered unstable version and normally won't upgrade.
If you would like to get out of Channel, you could replace the Channel with a given version number and let it managed by Renovate ongoing.
