# Custom Rom Builder For Samsung Galaxy A11/M11

<br>⚬ This tool can create full flashble zip with any gsi</br>
⚬ This tool support both arm32 and arm64
⚬ Arm64 still not supported

# If you want to build arm32 custom rom
<br>⚬ You MUST use PHH based GSI above android 12</br>
⚬ You can use GSIs Upto 3GB due limitaion of 

# If you want to build arm64 custom rom, (Still not Possible)

<br>⚬ You MUST use PHH based GSIs above android 10</br>
<br>⚬ You can use Erfan/Nippon GSIs android 10/11/12 only</br>
<br>⚬ Still tested only MIUI android 11/OOS 11/PIXEL 12</br>

# How to Use this

<br>⚬ Fork into your github and use via github actions</br>

<br>1. Add Direct link of GSI</br>

if you use link form sourceforge.net ,
<br>⚬ copy downlad link from your gsi then you will get link like this,</br>
 ```sh
https://sourceforge.net/projects/andyyan-gsi/files/lineage-19.x/lineage-19.1-20230715-UNOFFICIAL-a64_bgN.img.xz/download
 ```
<br>⚬ then delete the /download then it will be like below</br>
 ```sh
https://sourceforge.net/projects/andyyan-gsi/files/lineage-19.x/lineage-19.1-20230715-UNOFFICIAL-a64_bgN.img.xz
 ```
<br>⚬ the link must be end with .xz .img .7z .gz</br>

<br>2. Add Architecuter</br>
<br>⚬ then add the arch as 32 or 64</br>

<br>3. Add Rom Name</br>
<br>⚬ then add the gsi name it should be [rom_name]_[version]_[sdm430]_[arm64_or_32]_[gapps_or_vanila]<br>
like this LineageOS_19.1_SDM439_ARM32_Gapps



