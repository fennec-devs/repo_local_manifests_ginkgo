# Ginkgo Local Manifest
Local manifest for the Xiaomi Note 8/8T crDroid repositories

To build, follow instructions from: https://github.com/crdroidandroid/android

However, before running `repo sync` make sure to add the `local.xml` to your `.repo/local_manifests/ginkgo/` folder.

Additionally, if building on a system with less than 16GB of ram: https://review.lineageos.org/c/LineageOS/android_build_soong/+/266411

Apply this patch when passing the metalava and make sure to build with the -j1 args.
