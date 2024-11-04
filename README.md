<img  width="480" src="https://raw.githubusercontent.com/openmv/openmv-media/master/logos/openmv-logo/logo.png">

# OpenMV IDE Version

This repo contains the version number files which OpenMV IDE uses to detect when a new release is available.
* [openmv-ide-version.txt](openmv-ide-version.txt) tells OpenMV IDE what the newest released version of the IDE is.
* [openmv-ide-resources-version-v2.txt](openmv-ide-resources-version-v2.txt) tells OpenMV IDE what the newest released verison of resources for the IDE are. OpenMV IDE can update its resources without requring a full update of the entire IDE which makes it easier to push updates to the firmware, documentation, etc.
* [openmv-ide-resources-version.txt](openmv-ide-resources-version.txt) last resources for OpenMV IDE v4.5.2. Future resources are incompatible.

## About this Repo

Do not include this repo as a submodule in any other repo. The version numbers here should be able to be changed at any time to push/pull-back OpenMV IDE updates. This repo should not have any other branches, releases, tags, etc. Just one main branch which is modified to inform OpenMV IDE what the latest versions are.
