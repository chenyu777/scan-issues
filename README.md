We periodically stress test [`webhint`][site] by scanning a large
number of URLs.

If something fails during that process (e.g.: `webhint` crashes,
timeouts, etc.), issues will be automatically created in this
repository.

When the stress tests are run again, existing issues will be
automatically updated or closed depending on whether the problems
they refer to still exist or not.

<!-- Link labels: -->

[site]: https://webhint.io
