# PitchBlack Recovery Project for the Samsung Galaxy J7 2017

### How to build ###

```bash
# Create dirs
$ mkdir pbrp ; cd pbrp

# Init repo
$ repo init --depth=1 -u git://github.com/PitchBlackRecoveryProject/manifest_pb.git -b android-10.0

# Clone my local repo
$ git clone https://github.com/TeGaX/android_device_samsung_j7y17lte.git -b pitchblack device/samsung/j7y17lte

# Sync
$ repo sync --no-repo-verify -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j16

# Build
$ . build/envsetup.sh
$ lunch omni_j7y17lte-eng
$ mka recoveryimage
```

## Credits
2020 @Astrako @Tenshi2112

## Contact
Telegram support group: https://t.me/joinchat/D1Jk_VbieGBXOWZt2y8O7A
