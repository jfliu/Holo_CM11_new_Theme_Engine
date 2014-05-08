Holo_CM11_new_Theme_Engine
==========================

here is the tamplate of the cyanogenmod 11 with the new theme engine ...
a big thanks to Esa <a href="https://plus.google.com/u/0/+EsaLaukkanen/posts/fchGpNFKyNy">Esa Laukkanen</a> for share Great Freedom apk.


### How it works ...
http://youtu.be/9SEDTtT93_0 <br>
<img src="https://lh6.googleusercontent.com/-Xe6PIcf5PH8/U2vr8RHPqXI/AAAAAAAAYmY/-0aCPmOU2F8/w355-h592-no/14+-+1">
<img src="https://lh3.googleusercontent.com/-U0xJUqfbP2U/U2vr8ZJouZI/AAAAAAAAYmk/arIMpoJF1Q4/w355-h592-no/14+-+2">
<img src="https://lh4.googleusercontent.com/-pOB-U3cXJbo/U2vMDVy9_bI/AAAAAAAAYlw/sbtwRYB3pJQ/w355-h592-no/14+-+2">

### Some documentations...
The directory structure looks like this:<br>
AndroidManifest.xml<br>
src/<br>
res/<br>
assets/<br>
  boot-animation/<br>
  fonts/<br>
  icons/<br>
    res/ (note: same dir structure as res/ in trebuchet icon packs)<br>
  wallpapers/<br>
  ringtones/<br>
  notifications/<br>
  alarms/<br>
  overlays/<br>
      [target-pkg-name1]<br>
          res/<br>
           drawable/<br>
           drawable-hdpi/<br>
           ...<br>
           layouts/<br>
           xml/<br>
      [target-pkg-name2]<br>
          res/<br>
      
A theme APK is identified by meta-value data in AndroidManifest.xml. Here is an example:<br>
<?xml version="1.0" encoding="utf-8"?><br>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"<br>
    package="com.me.andytheme2"<br>
    android:versionCode="1"<br>
    android:versionName="1.0" ><br>
    <uses-feature android:name="org.cyanogenmod.theme" /><br>
    <meta-data android:name="org.cyanogenmod.theme.name" android:value="My Blue Theme"/><br>
    <meta-data android:name="org.cyanogenmod.theme.author" android:value="John Doe" /><br>
</manifest><br>

Click <a href="http://review.cyanogenmod.org/#/c/62375/">here</a> to see the full documentation.

### Good theming guys !!
