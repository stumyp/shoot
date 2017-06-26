shoot-s3
=====

**Script for taking sreenshot of selected area and upload it to S3**

**Implemented in:** bash

**Dependencies:**
* awscli
* date
* scrot
* xclip
* libnotify-bin

**License:** GNU GPL v3

Derived from https://github.com/kodx/shoot

**Installation:**
```
wget -O ~/bin/shoot-s3 https://raw.githubusercontent.com/stumyp/shoot/master/shoot-s3  && chmod 755 ~/bin/shoot-s3
```

**Usage:**
```
~/bin/shoot-s3 -b my-bucket -P tim/shots -r us-east-1 -p cdn-tim -f ~/Pictures/ -c yes
```
![Setting for KDE shortcut](http://com-agilebits-users.s3.amazonaws.com/tim/shots/2017-06-26-16-27-21.png)

