-----------------------------------------------------------------------------

<p align="center">
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-1.png" > 
</p>
<p >
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-3.png" > 
</p>

-----------------------------------------------------------------------------
Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**ABC**](https://github.com/ezio84?tab=repositories)
 * [**Shakthivel Nadar**](https://github.com/Sonic-sakthivel123) - Builder
 * [**Dan Santos**](https://github.com/linusdan) - Developer/Fork contribuitor of dotOS for i9300
 * [**Shilin Victor**](https://github.com/ChronoMonochrome) - Developer of Lineage 15.1/16.0 for i9300

-----------------------------------------------------------------------------
Warning!:
==========
Do not use these sources without our consent, if an thread is posted on XDA and you use our sources, you will be reported to moderators of XDA!

Getting Started:
==============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
    repo init -u git://github.com/DotOS/manifest.git -b dot-p
    git clone https://github.com/konuss/dot-manifests.git -b dot-p-alpha .repo/local_manifests
```

Then to sync up:
================

```bash
    repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

Additionally, you can define the number of parallel download repo should do:

```bash
    repo sync -f -jX --force-sync --no-clone-bundle --no-tags ( X is the number of parallel download repo should do choose depending on your cpu )
```

Compilation of Dot OS:
====================
From root directory of Project, perform following commands in terminal

```bash
Altering the subject line to reflect your information:

subject='/C=US/ST=California/L=Mountain View/O=Android/OU=Android/CN=Android/emailAddress=android@android.com'
mkdir .android-certs
for x in releasekey platform shared media testkey; do \
    ./development/tools/make_key .android-certs/$x "$subject"; \
done

source build/envsetup.sh
lunch dot_i9300-userdebug
make bacon
```
-----------------------------------------------------------------------------

Some Links:-
============
* [**Website**](https://www.droidontime.com)
* [**Telegram Public Chat**](https://t.me/dotos)
* [**Telegram Channel**](https://t.me/dotOSchannel)
* [**Facebook Page**](https://www.facebook.com/dotosofficial)
* [**Twitter**](https://twitter.com/dotosofficial)

<p align="center">
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-4.png" > 
</p>
