firefox_local_manifest
======================

local manifest files for a Firefox OS build on a ZTE V9 based on cm10

start from a working cm10 v9 build tree, clone the B2G repository into it, replace .repo/local_manifests/* with the above xml files, apply normal build patches from device/zte/v9/{patches,patches_v9} and the new patches from device/zte/v9/patches_b2g/, then build like a normal b2g. eg. ./config.sh v9 ; ./build.sh
