 <p align="center">
<img src="https://raw.githubusercontent.com/Rpingat/wall/master/1(1).png"> 
 </p>

Credits
-------

* [**TeamSubstratum**](https://github.com/Substratum)
* [**LineageOS**](https://github.com/LineageOS)
* [**ColtOS**](https://github.com/ColtOS)
* [**DirtyUnicons**](https://github.com/DirtyUnicorns)
* [**AospExtended**](https://github.com/AospExtended)

How to Build?
-------------

To initialize your local repository using the PolyOS sources, use a 
command like this:

```bash
repo init -u https://github.com/Poly-OS/The_fucking_manifest -b nougat
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
