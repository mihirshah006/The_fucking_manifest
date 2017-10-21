
<p align="center">
<img src="https://preview.ibb.co/eKxAD6/logo.png" width="640px" height="640px" > 
</p>

Credits
-------

* [**TeamSubstratum**](https://github.com/Substratum)
* [**LineageOS**](https://github.com/LineageOS)
* [**ColtOS**](https://github.com/ColtOS)
* [**DirtyUnicons**](https://github.com/DirtyUnicorns)

How to Build?
-------------

To initialize your local repository using the PolyOS sources, use a 
command like this:

```bash
  repo init -u git://github.com/PolyOS-CAF/android.git -b nougat
```
  
Then to sync up:
----------------

```bash
  repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```
EG:
---
```bash
  repo sync -c -j8 --force-sync --no-clone-bundle --no-tags
```
