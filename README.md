# # Rebellion-OS 

-----------------------------------------------------------------------------

<p align="center">
 <img src="https://github.com/Rebellion-Hub/Rebellion_Xtras../blob/ten/Logo/rebellion_manifest_logo.png" > 
</p>

-----------------------------------------------------------------------------

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**Havoc OS**](https://github.com/Havoc-OS)
 * [**MSM-Xtended**](https://github.com/Project-Xtended)

-----------------------------------------------------------------------------

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
    repo init -u https://github.com/Rebellion-Hub/Manifest_Rebellion.git -b ten
```

Then to sync up:-
================

```bash
    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

Start the build:-
=================

```bash
  . build/envsetup.sh
  lunch rebellion_<devicecodename>-userdebug
  mka rebellion or brunch <device>
```
-----------------------------------------------------------------------------

Some Links:-
============

* [**Telegram Public Chat**](https://t.me/RebellionHub)
* [**Telegram Channel**](https://https://t.me/rebellionAnnouncements)

 To Apply for Official:-
=========================

* [**Here you GO..**](https://github.com/Rebellion-OS/Rebellion_Xtras../tree/ten/Maintainers)

----------------------------------------------------------------------------
