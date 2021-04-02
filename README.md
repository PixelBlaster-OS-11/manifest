# PixelBlaster #
<img src="">

Credits:
=======
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**RevengeOS**](https://github.com/RevengeOS)
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**ABC**](https://github.com/ezio84?tab=repositories)
 * [**Project-Awaken**](https://github.com/Project-Awaken)
 * [**PixelExtended**](https://github.com/PixelExtended)
 * [**WaveOS**](https://github.com/Wave-Project)
 * [**HyconOS**](https://github.com/HyconOS)
-----------------------------------------------------------------------------

### Getting Started: ###

To initialize your local repository, use a command like this:

```bash

repo init -u https://github.com/PixelBlaster-OS/manifest -b eleven

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```

### Submitting Patches ###

Patches are always welcome! Fork any of the repos and make pull requests. Maintain Proper Authorship if picking someone else's commits.
