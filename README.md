LineageOS for Redmi Note 8/8T (ginkgo/willow)
===========

Getting started
---------------

To get started with Android/LineageOS, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).

To initialize your local repository using the LineageOS trees, use a command like this:
```
repo init -u https://github.com/LineageOS/android.git -b lineage-22.1 --git-lfs
```
After initialize clone local manifest for Redmi Note 8/8T
```
git clone https://github.com/mnasibzade/local_manifest -b lineage-22.1 .repo/local_manifests
```
Then to sync up:
```
repo sync
```
Build ROM
```bash

# Set up environment
$ . build/envsetup.sh

# Build the code
$ lunch lineage_ginkgo-ap4a-<build_variant>  
$ make bacon

```

# Credits:
- [ghostrider-reborn](https://github.com/ghostrider-reborn)
- [kutemeikito](https://github.com/kutemeikito)
- [DarkJoker360](https://github.com/DarkJoker360)
- [tejas101k](https://github.com/tejas101k)
- [ozturkmutlu65](https://github.com/ozturkmutlu65)
- [wrdn28](github.com/Wrdn28)
- All developers of Redmi Note 8
- All authors whose commits I use
