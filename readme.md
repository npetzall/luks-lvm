### LUKS-LVM

These scripts are provided/linked from https://help.ubuntu.com/community/ManualFullSystemEncryption  

You should probably not use these scripts but the supplied from link above.
I've made changes that have ZERO guarantees of working.  

Sadly the files did not contain any type of license so I've assumed that they follow the wiki.

So this work is base of the work that has been contributed by Contributors to the Ubuntu documentation wiki.  

Specifically Paddy Landau https://launchpad.net/~paddy-landau
And David Pires https://launchpad.net/~slickymaster

## Modifications

* Added home lv
* Added docker lv with xfs and d_type=1
* Reduced root to use on 60%FREE instead of 100%
