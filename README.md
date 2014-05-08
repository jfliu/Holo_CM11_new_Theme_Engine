Holo_CM11_new_Theme_Engine
==========================

here is the tamplate of the cyanogenmod 11 with the new theme engine ...
a big thanks to Esa <a href="https://plus.google.com/u/0/+EsaLaukkanen/posts/fchGpNFKyNy">Esa Laukkanen</a> for share Great Freedom apk.


### How it works ...
<a href="http://www.youtube.com/watch?feature=player_embedded&v=9SEDTtT93_0
" target="_blank"><img src="http://img.youtube.com/vi/9SEDTtT93/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a> <br>
<img src="https://lh6.googleusercontent.com/-Xe6PIcf5PH8/U2vr8RHPqXI/AAAAAAAAYmY/-0aCPmOU2F8/w355-h592-no/14+-+1">
<img src="https://lh3.googleusercontent.com/-U0xJUqfbP2U/U2vr8ZJouZI/AAAAAAAAYmk/arIMpoJF1Q4/w355-h592-no/14+-+2">
<img src="https://lh4.googleusercontent.com/-pOB-U3cXJbo/U2vMDVy9_bI/AAAAAAAAYlw/sbtwRYB3pJQ/w355-h592-no/14+-+2">

### Some documentations...
The directory structure looks like this:<br><pre>
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
          res/</pre><br>
      
A theme APK is identified by meta-value data in AndroidManifest.xml. Here is an example:<br>
<pre><div class="line" id="LC1"><span class="nt">&lt;manifest</span> <span class="na">xmlns:android=</span><span class="s">"http://schemas.android.com/apk/res/android"</span></div><div class="line" id="LC2">&nbsp;&nbsp;&nbsp;&nbsp;<span class="na">package=</span><span class="s">"com.botty.testcm11"</span><span class="nt">&gt;</span></div><div class="line" id="LC3"><br></div><div class="line" id="LC4">&nbsp;&nbsp;&nbsp;&nbsp;<span class="nt">&lt;uses-feature</span> <span class="na">android:name=</span><span class="s">"org.cyanogenmod.theme"</span> <span class="nt">/&gt;</span></div><div class="line" id="LC5">&nbsp;&nbsp;&nbsp;&nbsp;<span class="nt">&lt;meta-data</span> <span class="na">android:name=</span><span class="s">"org.cyanogenmod.theme.name"</span> <span class="na">android:value=</span><span class="s">"My Test Theme"</span><span class="nt">/&gt;</span></div><div class="line" id="LC6">&nbsp;&nbsp;&nbsp;&nbsp;<span class="nt">&lt;meta-data</span> <span class="na">android:name=</span><span class="s">"org.cyanogenmod.theme.author"</span> <span class="na">android:value=</span><span class="s">"Botty Ivan"</span> <span class="nt">/&gt;</span></div><div class="line" id="LC7"><br></div><div class="line" id="LC8">&nbsp;&nbsp;&nbsp;&nbsp;<span class="nt">&lt;application</span> <span class="na">android:allowBackup=</span><span class="s">"true"</span></div><div class="line" id="LC9">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="na">android:label=</span><span class="s">"@string/app_name"</span></div><div class="line" id="LC10">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="na">android:icon=</span><span class="s">"@drawable/ic_launcher"</span></div><div class="line" id="LC11">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="na">android:theme=</span><span class="s">"@style/AppTheme"</span><span class="nt">&gt;</span></div><div class="line" id="LC12"><br></div><div class="line" id="LC13">&nbsp;&nbsp;&nbsp;&nbsp;<span class="nt">&lt;/application&gt;</span></div><div class="line" id="LC14"><br></div><div class="line" id="LC15"><span class="nt">&lt;/manifest&gt;</span></div></pre>
Click <a href="http://review.cyanogenmod.org/#/c/62375/">here</a> to see the full documentation.

### Good theming guys !!
