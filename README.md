The Alliance
=====================

Getting Started
---------------

To build Alliance from source, you'll need to be familiar with
[Git and Repo](http://source.android.com/download/using-repo).


To initialize your local repository, use this command:

	repo init -u https://github.com/AllianceRom/manifest.git -b AllianceN

Then to sync source, use this command:

	repo sync

After syncing is done, use these commands to build:

    1.) . build/envsetup.sh
    2.) brunch xxxx yyyy
    
    xxxx= device name aka shamu
    yyyy= build type (user,userdebug,eng)*

    *if no build type is specified "userdebug" is default
