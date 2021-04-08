# Local Manifests #
Just grab the manifest and sync to get device sources
### AOSP R ###

```bash

# Grab Local Manifest
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/oWolkodaWo/local_manifests/main/eleven.xml --create-dirs

# Sync
repo sync -j24 --force-sync
```


# kernel dream
git clone --depth=1 --single-branch https://github.com/JamieHoSzeYui/dream -b ten kernel/xiaomi/mt6768

# Script Script from henloboi
wget https://cheems.mirrorbomt.workers.dev/mt6768.sh && bash mt6768.sh
