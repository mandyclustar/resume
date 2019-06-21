# resume

install cv editing environment for MAC OS

### step 1

Download MacTex installer http://www.tug.org/mactex/downloading.html. MacTex is a free software distribution for the TeX typesetting system that includes major TeX-related programs, macro packages, and fonts.  

MacTex comprises a build-in editor TeXShop. You can use TextEditor or oher alternetives.

### step 2

Install macro package ctex or XeCJK for chinese supporting
```
sudo -i
tlmgr update --self
ltmgr update --all
```

### step 3

Set the encoding mode to utf-8 `(TeXShop-->preferences-->Unicode(UTF-8))` and choose XeLaTex compiler
