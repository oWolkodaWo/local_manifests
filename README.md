# Local Manifests #
Just grab the manifest and sync to get device sources
### AOSP R ###

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/oWolkodaWo/local_manifests/main/eleven.xml --create-dirs

# Sync
repo sync -j24 --force-sync
```
