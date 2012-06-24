Getting Started
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

Big thanks goes to AOKP team for base and TeamNDVRu for HTC OneX fixes


To initialize your local repository using the IceColdAOKP trees, use a command like this:

    repo init -u git://github.com/IceColdAOKP/platform_manifest.git -b ics

Then to sync up:

    repo sync -j16

To build:

    . build/envsetup.sh
    lunch aokp_endeavoru-userdebug
    make -j6 bacon

OR if you have installed ccache use this build script for faster compilation

    . vendor/lord/build.sh
