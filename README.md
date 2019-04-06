LineageOS by Koboldo
====================

This is an Android ROM based on LineageOS with a few add-ons from other ROMs those are:
1. Battery Info in Lockscreen while charging ([1](https://github.com/koboldo81/android_frameworks_base/commit/7f144dc02c2780214a95d6d383b9f2fc31e26eb4)) ([2](https://github.com/koboldo81/android_system_core/commit/3cd36816852e7f28bbbd68e9e93ee47403a3e743))
2. Magisk ([1](https://github.com/koboldo81/android_vendor_koboldo/commit/f20629e085467187f1a7ffdc5649953771496cc1)) ([2](https://github.com/koboldo81/android_build/commit/e68a88f4396daf4585ca56e3f6eca2ba03bd4a07))
   
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
