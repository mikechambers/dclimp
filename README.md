# dclimp
Python 3 based command line utility for checking and syncing the Destiny 2 Manifest SQLite database.

This project has been superseded by [dcli](https://github.com/mikechambers/dcli).

The utility can be used to:

* Download latest version of the manifest sqlite database file
* Query whether the manifest has been updated since it was last downloaded
* Query the latest URL and version for the remote manifest

## USAGE
```
usage: dclimp [-h] --key KEY --manifest_dir MANIFEST_DIR [--version]
             [--info {local.version,local.url,remote.version,remote.url}]
             [--check] [--force]
```

The `--manifest_dir` argument is required, and should point a directory where the manifest and manifest info file can be saved anand maintained.

The `--key` argument is required and specifies the API key from Bungie.mesh
