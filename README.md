Getting Started
---------------

### Sync ###
```bash
# Initialize local repository
$ repo init -u https://github.com/vinoobubbly/android_manifest.git -b nougat

# Sync
$ repo sync -jX
```

### Preparing to Build ###
```bash
# Set up environment
$ source build/envsetup.sh

# Configure jack
$ export ANDROID_JACK_VM_ARGS="-Dfile.encoding=UTF-8 -XX:+TieredCompilation -Xmx4G"

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ croot
$ brunch DEVICE
```

### Build ###
```bash
#Install Build
$ cd $OUT
```
