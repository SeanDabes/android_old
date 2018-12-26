LineageOS by Koboldo
====================

This is an Android ROM based on LineageOS with a few add-ons from other ROMs those are:
1. Battery Info in Lockscreen while charging:
    * https://github.com/koboldo81/android_frameworks_base/commit/f581eae33f192a88183a5a7608108750b82a6afd
    * https://github.com/koboldo81/android_system_core/commit/bd2ff191912543bd1238710291a6a2a6bb28cd6c
2. Magisk:
   * https://github.com/koboldo81/android_vendor_koboldo/commit/1aba3bf9e0797c0110232aa3c8d01cd93ebb35d8
   * https://github.com/koboldo81/android_build/commit/8ad2cda0ffdbe4250e0421f8fb8410410380363f

To-Do list:
* Change launcher to [Lawnchair](http://www.lawnchair.info)
* Change camera to OpenCamera
* Add Forecastie


Getting Started
---------------

To get started with Android/LineageOS, you'll need to get
familiar with [Git and Repo](https://source.android.com/source/using-repo.html).

To initialize your local repository using the LineageOS by Koboldo trees, use a command like this:

    repo init -u git://github.com/koboldo81/android.git -b lineage-16.0

Then to sync up:

    repo sync

Please see the [LineageOS Wiki](https://wiki.lineageos.org/) for building instructions.
