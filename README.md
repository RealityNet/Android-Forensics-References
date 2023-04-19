# Android Forensics References
<p>Last update: September 6th 2022</p>
<p>
<h1>USERDATA Partition</p></h1>
<p>
<h2 style="text-align: left;"><b><span style="font-size: medium;">"/log" folder</span></b></h2>
</p>
<div>
   <ul>
      <li><b>/log/wifi/iwc/iwc_dump.txt</b></li>
      <li><b>/log/netstats</b></li>
      <li><b>/log/batterystats</b></li>
      <ul>
         <li><b>Cellebrite CTF 2021 - Heisenberg's Android</b><br /><a href="https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-heisenbergs-android.html">https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-heisenbergs-android.html</a></li>
         <li><b>Part 1: Walk-Through of Answers to the 2021 CTF – Investigating Heisenberg’s Android Device</b><br /><a href="https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/">https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/</a><br /></li>
         <li><b>Artefacts of Android device power off due to depleted battery</b><br /><a href="https://instatronic.com/artefacts-of-android-device-power-off-due-to-depleted-battery">https://instatronic.com/artefacts-of-android-device-power-off-due-to-depleted-battery</a></li>
      </ul>
      <li><b>/log/recovery</b></li>
      <li><b>/log/sdp_log</b></li>
      <li><b>/log/thermal_log</b></li>
      <li><b>/log/power_off_reset_reason.txt</b></li>
      <ul>
         <li><b>Cellebrite CTF 2021 - Heisenberg's Android<br /></b><a href="https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-heisenbergs-android.html">https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-heisenbergs-android.html</a></li>
         <li><b>Artefacts of Android device power off due to depleted battery<br /></b><a href="https://instatronic.com/artefacts-of-android-device-power-off-due-to-depleted-battery">https://instatronic.com/artefacts-of-android-device-power-off-due-to-depleted-battery</a></li>
         <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/powerOffReset.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/powerOffReset.py</a></li>
      </ul>
   </ul>
</div>
<p>
<h2 style="text-align: left;"><b><span style="font-size: medium;">"/misc" and "/misc_de" folder</span></b></h2>
</p>
<div>
   <ul>
      <li><b>/misc/adb/adb_keys</b></li>
      <ul>
         <li><b>aLEAPP plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/adb_hosts.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/adb_hosts.py</a></li>
      </ul>
      <li><b>/misc/bluedroiddump/mainBuffer.log</b></li>
      <li><b>/misc/bluedroiddump/subBuffer.log</b></li>
      <li><b>/misc/bluedroid/bt_config.conf</b></li>
      <ul>
         <li><b>How Android Bluetooth Connections Can Determine If The Hands of a Driver Were On The Wheel During An Accident</b><br /><a href="https://cellebrite.com/en/how-android-bluetooth-connections-can-determine-if-the-hands-of-a-driver-were-on-the-wheel-during-an-accident/">https://cellebrite.com/en/how-android-bluetooth-connections-can-determine-if-the-hands-of-a-driver-were-on-the-wheel-during-an-accident/</a><br /><a href="https://dfir.pubpub.org/pub/6ysxvhvc/release/1">https://dfir.pubpub.org/pub/6ysxvhvc/release/1</a></li>
         <li><b>Android Bluetooth Connection Configuration</b><br /><a href="https://www.stark4n6.com/2021/06/android-bluetooth-connection.html">https://www.stark4n6.com/2021/06/android-bluetooth-connection.html</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2015</b><br /><a href="https://cts-forensics.com/reports/35550_Web.pdf">https://cts-forensics.com/reports/35550_Web.pdf</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2016</b><br /><a href="https://cts-forensics.com/reports/36550_Web.pdf">https://cts-forensics.com/reports/36550_Web.pdf</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2017</b><br /><a href="https://cts-forensics.com/reports/37550_Web.pdf">https://cts-forensics.com/reports/37550_Web.pdf</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2019</b><br /><a href="https://cts-forensics.com/reports/19-5550_Web.pdf">https://cts-forensics.com/reports/19-5550_Web.pdf</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2020</b><br /><a href="https://cts-forensics.com/reports/20-5550_Web.pdf">https://cts-forensics.com/reports/20-5550_Web.pdf</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2021<br /></b><a href="https://cts-forensics.com/reports/21-5550_Web.pdf">https://cts-forensics.com/reports/21-5550_Web.pdf</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2022<br /></b><a href="https://cts-forensics.com/reports/22-5550_Web.pdf">https://cts-forensics.com/reports/22-5550_Web.pdf</a></li>
         <li><b>Cellebrite CTF 2021 Writeup</b><br /><a href="https://medium.com/@williamskosasi/cellebrite-ctf-2021-writeup-b73d821a708">https://medium.com/@williamskosasi/cellebrite-ctf-2021-writeup-b73d821a708</a><br /></li>
         <li><b>Cellebrite CTF 2021 - Heisenberg's Android</b><br /><a href="https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-heisenbergs-android.html">https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-heisenbergs-android.html</a></li>
         <li><b>Cellebrite CTF 2022 - Heisenberg's Android</b><br /><a href="https://www.stark4n6.com/2022/06/cellebrite-ctf-2022-heisenbergs-android.html">https://www.stark4n6.com/2022/06/cellebrite-ctf-2022-heisenbergs-android.html</a></li>
         <li><b>aLEAPP plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/bluetoothConnections.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/bluetoothConnections.py</a></li>
      </ul>
      <li><b>/misc/bootstat/</b></li>
      <ul>
         <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/last_boot_time.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/last_boot_time.py</a><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/factory_reset.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/factory_reset.py</a></li>
      </ul>
      <li><b>/misc/wifi/qtables.json</b></li>
      <li><b><b>/misc/wifi/wpa_supplicant.conf</b><br /></b><b>/misc/wifi/</b><b>WifiConfigStore.xml<br /></b><b>/misc/apexdata/com.android.wifi/WifiConfigStore.xml</b></li>
      <ul>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2015</b><br /><a href="https://cts-forensics.com/reports/35550_Web.pdf">https://cts-forensics.com/reports/35550_Web.pdf</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2016</b><br /><a href="https://cts-forensics.com/reports/36550_Web.pdf">https://cts-forensics.com/reports/36550_Web.pdf</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2017</b><br /><a href="https://cts-forensics.com/reports/37550_Web.pdf">https://cts-forensics.com/reports/37550_Web.pdf</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2019</b><br /><a href="https://cts-forensics.com/reports/19-5550_Web.pdf">https://cts-forensics.com/reports/19-5550_Web.pdf</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2020</b><br /><a href="https://cts-forensics.com/reports/20-5550_Web.pdf">https://cts-forensics.com/reports/20-5550_Web.pdf</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2021<br /></b><a href="https://cts-forensics.com/reports/21-5550_Web.pdf">https://cts-forensics.com/reports/21-5550_Web.pdf</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2022<br /></b><a href="https://cts-forensics.com/reports/22-5550_Web.pdf">https://cts-forensics.com/reports/22-5550_Web.pdf</a></li>
         <li><b>Cellebrite Fall 2020 CTF - Part 1 - Tony Mederos</b><br /><a href="https://starwarsfan2099.github.io/2020/11/02/cellebirte-ctf-tony.html">https://starwarsfan2099.github.io/2020/11/02/cellebirte-ctf-tony.html</a></li>
         <li><b>Clockin’ In with Google’s Wear OS</b><br /><a href="https://thebinaryhick.blog/2021/01/13/clockin-in-with-googles-wear-os/">https://thebinaryhick.blog/2021/01/13/clockin-in-with-googles-wear-os/</a><br /></li>
         <li><b>Learning Android Forensics - Second Edition</b><br /><a href="https://www.packtpub.com/product/learning-android-forensics-second-edition/9781789131017">https://www.packtpub.com/product/learning-android-forensics-second-edition/9781789131017</a></li>
         <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
         <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/wifiConfigstore.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/wifiConfigstore.py</a><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/wifiProfiles.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/wifiProfiles.py</a></li>
      </ul>
      <li><b>/misc/wifi/softap.conf<br /></b><b>/misc/apexdata/com.android.wifi/WifiConfigStoreSoftAp.xml</b></li>
      <ul>
         <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/wifiHotspot.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/wifiHotspot.py</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2018</b><br /><a href="https://cts-forensics.com/reports/38550_Web.pdf">https://cts-forensics.com/reports/38550_Web.pdf</a></li>
         <li><b>Let's solve challenges - Cellebrite 2022 CTF Writeup</b><br /><a href="https://www.dfirblog.com/cellebrite-2022-ctf-writeup/">https://www.dfirblog.com/cellebrite-2022-ctf-writeup/</a></li>
         <li><b>Cellebrite CTF 2022 - Heisenberg's Android</b><br /><a href="https://www.stark4n6.com/2022/06/cellebrite-ctf-2022-heisenbergs-android.html">https://www.stark4n6.com/2022/06/cellebrite-ctf-2022-heisenbergs-android.html</a></li>
         https://www.dfirblog.com/cellebrite-2022-ctf-writeup/
         <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
      </ul>
      <li><b>/misc_de/0/apexdata/com.android.permission/runtime-permissions.xml</b></li>
      <ul>
         <li><b>Android’s “Dangerous” Permissions</b><br /><a href="https://thebinaryhick.blog/2021/01/26/androids-dangerous-permissions/">https://thebinaryhick.blog/2021/01/26/androids-dangerous-permissions/</a></li>
         <li><b>Examining A Malware-Infected Android Phone. This Android Is Not Alright.</b><br /><a href="https://thebinaryhick.blog/2022/04/09/examining-a-malware-infected-android-phone-this-android-is-not-alright/">https://thebinaryhick.blog/2022/04/09/examining-a-malware-infected-android-phone-this-android-is-not-alright/</a></li>
         <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/runtimePerms.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/runtimePerms.py</a></li>
      </ul>
      <li><b>/misc_de/0/apexdata/com.android.permission/roles.xml</b></li>
      <ul>
         <li><b>Android - Roles and Permissions (Android 10/11)</b><br /><a href="https://blog.d204n6.com/2021/01/android-roles-and-permissions-android.html">https://blog.d204n6.com/2021/01/android-roles-and-permissions-android.html</a></li>
         <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/roles.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/roles.py</a></li>
      </ul>
   </ul>
   <div>
      <p>
      <h2 style="text-align: left;"><b>"/property" folder</b></h2>
      </p>
      <div>
         <ul>
            <li><b>/property/persistent_properties</b></li>
            <ul>
               <li><b>aLEAPP plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/persistentProp.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/persistentProp.py</a></li>
            </ul>
         </ul>
      </div>
   </div>
   <div>
      <h2 style="text-align: left;"><b>"/system", "/system_ce" and "/system_de" folders</b></h2>
   </div>
   <div>
      <ul style="text-align: left;">
         <li><b>/system/appops/<br /></b></li>
         <ul>
            <li><b>Snooping on Android 12’s Privacy Dashboard</b><br /><a href="https://thebinaryhick.blog/2022/01/22/snooping-on-android-12s-privacy-dashboard/">https://thebinaryhick.blog/2022/01/22/snooping-on-android-12s-privacy-dashboard/</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/discreteNative.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/discreteNative.py</a></li>
         </ul>
         <li><b>/system/batteryusagestats/</b></li>
         <li><b>/system/job/jobs.xml</b></li>
         <li><b>/system/netstats/</b></li>
         <ul>
            <li><b>Burn After Reading: Expunging Execution Footprints of Android Apps</b><br /><a href="https://lijuanru.com/publications/nss18.pdf">https://lijuanru.com/publications/nss18.pdf</a></li>
            <li><b>Android Internals</b><br /><a href="http://newandroidbook.com/Book/2-Excerpt-Data.pdf">http://newandroidbook.com/Book/2-Excerpt-Data.pdf</a></li>
         </ul>
         <li><b>/system/procstats/</b></li>
         <ul>
            <li><b>Android Internals</b><br /><a href="http://newandroidbook.com/Book/2-Excerpt-Data.pdf">http://newandroidbook.com/Book/2-Excerpt-Data.pdf</a></li>
         </ul>
         <li><b>/system/sync/accounts.xml</b></li>
         <ul>
            <li><b>Who is the owner of the mobile device?</b><br /><a href="https://www.digitalforensics.com/blog/articles/who-is-the-owner-of-the-mobile-device/">https://www.digitalforensics.com/blog/articles/who-is-the-owner-of-the-mobile-device/</a><br /></li>
            <li><b>Clockin’ In with Google’s Wear OS</b><br /><a href="https://thebinaryhick.blog/2021/01/13/clockin-in-with-googles-wear-os/">https://thebinaryhick.blog/2021/01/13/clockin-in-with-googles-wear-os/</a></li>
            <li><b>Super Sunday Funday Forensic Challenge - Update 4</b><br /><a href="https://www.hecfblog.com/2014/09/super-sunday-funday-forensic-challenge_15.html">https://www.hecfblog.com/2014/09/super-sunday-funday-forensic-challenge_15.html</a></li>
            <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
         </ul>
         <li><b>/system/shutdown-checkpoints/</b></li>
         <ul>
            <li><b>Shutdown Checkpoints in Android 12</b><br /><a href="https://www.stark4n6.com/2022/01/shutdown-checkpoints-in-android-12.html">https://www.stark4n6.com/2022/01/shutdown-checkpoints-in-android-12.html</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/shutdown_checkpoints.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/shutdown_checkpoints.py</a></li>
         </ul>
         <li><b>/system/users/0.xml</b></li>
         <ul>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2021<br /></b><a href="https://cts-forensics.com/reports/21-5550_Web.pdf">https://cts-forensics.com/reports/21-5550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2022<br /></b><a href="https://cts-forensics.com/reports/22-5550_Web.pdf">https://cts-forensics.com/reports/22-5550_Web.pdf</a></li>
            <li><b>Forensic analysis of IoT ecosystem</b><br /><a href="https://hal.archives-ouvertes.fr/hal-03369836/document">https://hal.archives-ouvertes.fr/hal-03369836/document</a></li>
         </ul>
         <li><b>/system/users/0/app_idle_stats.xml</b></li>
         <li><b>/system/users/0/settings_global.xml<br /></b></li>
         <li><b><b>/system/users/0/</b>settings_secure.xml</b></li>
         <ul>
            <li><b>Cellebrite CTF 2021 - Heisenberg's Android</b><br /><a href="https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-heisenbergs-android.html">https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-heisenbergs-android.html</a></li>
            <li><b>Part 1: Walk-Through of Answers to the 2021 CTF – Investigating Heisenberg’s Android Device</b><br /><a href="https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/">https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/</a></li>
            <li><b>Examining A Malware-Infected Android Phone. This Android Is Not Alright.</b><br /><a href="https://thebinaryhick.blog/2022/04/09/examining-a-malware-infected-android-phone-this-android-is-not-alright/">https://thebinaryhick.blog/2022/04/09/examining-a-malware-infected-android-phone-this-android-is-not-alright/</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/settingsSecure.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/settingsSecure.py</a></li>
         </ul>
         <li><b><b>/system/users/0/</b>settings_ssaid.xml</b></li>
         <ul>
            <li><b>Forensic analysis of instant messengers: Decrypt Signal, Wickr, and Threema</b><br /><a href="https://www.sciencedirect.com/science/article/pii/S2666281722000166">https://www.sciencedirect.com/science/article/pii/S2666281722000166</a></li>
         </ul>
         <li><b><b>/system/users/0/</b>settings_system.xml</b></li>
         <ul>
            <li><b>Android - Roles and Permissions (Android 10/11)</b><br /><a href="https://blog.d204n6.com/2021/01/android-roles-and-permissions-android.html">https://blog.d204n6.com/2021/01/android-roles-and-permissions-android.html</a></li>
         </ul>
         <li><b>/system/appops.xml</b></li>
         <ul>
            <li><b>Snooping on Android 12’s Privacy Dashboard</b><br /><a href="https://thebinaryhick.blog/2022/01/22/snooping-on-android-12s-privacy-dashboard/">https://thebinaryhick.blog/2022/01/22/snooping-on-android-12s-privacy-dashboard/</a></li>
            <li><b>Wipeout! Detecting Android Factory Resets</b><br /><a href="https://thebinaryhick.blog/2021/08/19/wipeout-detecting-android-factory-resets/">https://thebinaryhick.blog/2021/08/19/wipeout-detecting-android-factory-resets/</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/appopSetupWiz.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/appopSetupWiz.py</a><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/appops.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/appops.py</a></li>
            <li><b>Digital Forensic Practices and Methodologies for AI Speaker Ecosystems</b><br /><a href="https://www.sciencedirect.com/science/article/pii/S1742287619301628">https://www.sciencedirect.com/science/article/pii/S1742287619301628</a></li>
            <li><b>Android Internals</b><br /><a href="http://newandroidbook.com/Book/2-Excerpt-Data.pdf">http://newandroidbook.com/Book/2-Excerpt-Data.pdf</a></li>
         </ul>
         <li><b>/system/batterystats.bin</b></li>
         <ul>
            <li><b>Video Aficionado: We Know What You Are Watching<br /></b><a href="https://par.nsf.gov/servlets/purl/10215810">https://par.nsf.gov/servlets/purl/10215810</a></li>
            <li><b>Android Internals</b><br /><a href="http://newandroidbook.com/Book/2-Excerpt-Data.pdf">http://newandroidbook.com/Book/2-Excerpt-Data.pdf</a></li>
         </ul>
         <li><b>/system/batterystats-checkin.bin</b></li>
         <li><b>/system/batterystats-daily.xml</b></li>
         <ul>
            <li><b>Every Step You Take: Application and Network Usage in Android</b><br /><a href="https://docplayer.net/90183420-Every-step-you-take-application-and-network-usage-in-android.html">https://docplayer.net/90183420-Every-step-you-take-application-and-network-usage-in-android.html</a></li>
         </ul>
         <li><b>/system/deviceidle.xml</b></li>
         <li><b>/system/locksettings.db</b></li>
         <li><b>/system/netpolicy.xml</b></li>
         <ul>
            <li><b>Cellebrite CTF 2021 - Heisenberg's Android</b><br /><a href="https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-heisenbergs-android.html">https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-heisenbergs-android.html</a></li>
            <li><b>Part 1: Walk-Through of Answers to the 2021 CTF – Investigating Heisenberg’s Android Device</b><br /><a href="https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/">https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/</a></li>
            <li><b>Cellebrite CTF 2021 Writeup</b><br /><a href="https://medium.com/@williamskosasi/cellebrite-ctf-2021-writeup-b73d821a708">https://medium.com/@williamskosasi/cellebrite-ctf-2021-writeup-b73d821a708</a></li>
            <li><b>Android Internals</b><br /><a href="http://newandroidbook.com/Book/2-Excerpt-Data.pdf">http://newandroidbook.com/Book/2-Excerpt-Data.pdf</a></li>
         </ul>
         <li><b>/system/notification_policy.xml</b></li>
         <ul>
            <li><b>Part 1: Walk-Through of Answers to the 2021 CTF – Investigating Heisenberg’s Android Device</b><br /><a href="https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/">https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/</a></li>
         </ul>
         <li><b>/system/PkgPredictions.db</b></li>
         <li><b>/system/SemWifiApContentProvider</b></li>
         <ul>
            <li><b>Part 2: CTF 2022 Write Up – Heisenberg’s Android</b><br /><a href="https://cellebrite.com/en/part-2-ctf-2022-write-up-heisenbergs-android/">https://cellebrite.com/en/part-2-ctf-2022-write-up-heisenbergs-android/</a></li>
         </ul>
         <li><b>/system/SimCard.dat</b></li>
         <ul>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2018</b><br /><a href="https://cts-forensics.com/reports/38550_Web.pdf">https://cts-forensics.com/reports/38550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2019</b><br /><a href="https://cts-forensics.com/reports/19-5550_Web.pdf">https://cts-forensics.com/reports/19-5550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2020</b><br /><a href="https://cts-forensics.com/reports/20-5550_Web.pdf">https://cts-forensics.com/reports/20-5550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2021<br /></b><a href="https://cts-forensics.com/reports/21-5550_Web.pdf">https://cts-forensics.com/reports/21-5550_Web.pdf</a></li>
            <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
         </ul>
         <li><b>/system/WifiConfigStore.db</b></li>
         <li><b>/system/WifiHistory.db</b></li>
         <li><b>/system/wifigeofence.db</b></li>
         <ul>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2020</b><br /><a href="https://cts-forensics.com/reports/20-5550_Web.pdf">https://cts-forensics.com/reports/20-5550_Web.pdf</a></li>
         </ul>
         <li><b>/system/packages.xml</b></li>
         <ul>
            <li><b>Android - Roles and Permissions (Android 10/11)</b><br /><a href="https://blog.d204n6.com/2021/01/android-roles-and-permissions-android.html">https://blog.d204n6.com/2021/01/android-roles-and-permissions-android.html</a></li>
            <li><b>Mobile Forensics: Discovering the Undiscovered</b><br /><a href="https://www.magnetforensics.com/blog/mobile-forensics-discovering-the-undiscovered/">https://www.magnetforensics.com/blog/mobile-forensics-discovering-the-undiscovered/</a></li>
            <li><b>Some artifacts in the /data/system/ directory</b><br /><a href="http://freeandroidforensics.blogspot.com/2014/11/some-artifacts-in-datasystem-directory.html">http://freeandroidforensics.blogspot.com/2014/11/some-artifacts-in-datasystem-directory.html</a></li>
            <li><b>Android Internals</b><br /><a href="http://newandroidbook.com/Book/2-Excerpt-Data.pdf">http://newandroidbook.com/Book/2-Excerpt-Data.pdf</a></li>
            <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/packageInfo.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/packageInfo.py</a><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/permissions.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/permissions.py</a></li>
         </ul>
         <li><b>/system/packages.list</b></li>
         <ul>
            <li><b>Android - Roles and Permissions (Android 10/11)</b><br /><a href="https://blog.d204n6.com/2021/01/android-roles-and-permissions-android.html">https://blog.d204n6.com/2021/01/android-roles-and-permissions-android.html</a></li>
            <li><b>Android Internals</b><br /><a href="http://newandroidbook.com/Book/2-Excerpt-Data.pdf">http://newandroidbook.com/Book/2-Excerpt-Data.pdf</a></li>
            <li><b>Learning Android Forensics - Second Edition</b><br /><a href="https://www.packtpub.com/product/learning-android-forensics-second-edition/9781789131017">https://www.packtpub.com/product/learning-android-forensics-second-edition/9781789131017</a></li>
            <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a><br /></li>
            <li><b>Learning Android Forensics - Second Edition</b><br /><a href="https://www.packtpub.com/product/learning-android-forensics-second-edition/9781789131017">https://www.packtpub.com/product/learning-android-forensics-second-edition/9781789131017</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/packageGplinks.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/packageGplinks.py</a></li>
         </ul>
         <li><b>/system_ce/0/accounts_ce.db<br /></b></li>
         <ul>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2020</b><br /><a href="https://cts-forensics.com/reports/20-5550_Web.pdf">https://cts-forensics.com/reports/20-5550_Web.pdf</a></li>
            <li><b>Part 1: Walk-Through of Answers to the 2021 CTF – Investigating Heisenberg’s Android Device</b><br /><a href="https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/">https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/</a></li>
            <div>
               <li><b>Android - Tracking Device Migration</b><br /><a href="https://blog.d204n6.com/2021/06/android-tracking-device-migration.html">https://blog.d204n6.com/2021/06/android-tracking-device-migration.html</a></li>
               <li><b>aLEAPP Plugin<br /></b><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/accounts_ce.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/accounts_ce.py</a></li>
            </div>
         </ul>
         <li><b>/system_ce/recent_images/<br /></b></li>
         <ul>
            <li><b>Mobile Forensics: Discovering the Undiscovered<br /></b><a href="https://www.magnetforensics.com/blog/mobile-forensics-discovering-the-undiscovered/">https://www.magnetforensics.com/blog/mobile-forensics-discovering-the-undiscovered/</a></li>
            <li><b>Android Recent Tasks XML Parser</b><br /><a href="https://abrignoni.blogspot.com/2019/02/android-recent-tasks-xml-parser.html">https://abrignoni.blogspot.com/2019/02/android-recent-tasks-xml-parser.html</a></li>
            <li><b>Every Step You Take: Application and Network Usage in Android</b><br /><a href="https://docplayer.net/90183420-Every-step-you-take-application-and-network-usage-in-android.html">https://docplayer.net/90183420-Every-step-you-take-application-and-network-usage-in-android.html</a></li>
            <li><b>Digital Forensic Practices and Methodologies for AI Speaker Ecosystems</b><br /><a href="https://www.sciencedirect.com/science/article/pii/S1742287619301628">https://www.sciencedirect.com/science/article/pii/S1742287619301628</a></li>
            <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/recentactivity.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/recentactivity.py</a></li>
         </ul>
         <li><b>/system_ce/recent_tasks/</b></li>
         <ul>
            <li><b>Mobile Forensics: Discovering the Undiscovered</b><br /><a href="https://www.magnetforensics.com/blog/mobile-forensics-discovering-the-undiscovered/">https://www.magnetforensics.com/blog/mobile-forensics-discovering-the-undiscovered/</a></li>
            <li><b>Android Recent Tasks XML Parser</b><br /><a href="https://abrignoni.blogspot.com/2019/02/android-recent-tasks-xml-parser.html">https://abrignoni.blogspot.com/2019/02/android-recent-tasks-xml-parser.html</a></li>
            <li><b>Digital Forensic Practices and Methodologies for AI Speaker Ecosystems<br /></b><a href="https://www.sciencedirect.com/science/article/pii/S1742287619301628">https://www.sciencedirect.com/science/article/pii/S1742287619301628</a></li>
            <li><b>Corroboration. That Is All.</b><br /><a href="https://thebinaryhick.blog/2021/06/17/corroboration-that-is-all/">https://thebinaryhick.blog/2021/06/17/corroboration-that-is-all/</a></li>
            <li><b>Every Step You Take: Application and Network Usage in Android</b><br /><a href="https://docplayer.net/90183420-Every-step-you-take-application-and-network-usage-in-android.html">https://docplayer.net/90183420-Every-step-you-take-application-and-network-usage-in-android.html</a></li>
            <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/recentactivity.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/recentactivity.py</a></li>
            <li><b>Write-up Magnet Weekly CTF</b><br /><a href="https://www.cloud-response.com/2020/10/write-up-magnet-weekly-ctf.html">https://www.cloud-response.com/2020/10/write-up-magnet-weekly-ctf.html</a></li>
         </ul>
         <li><b>/system_ce/shortcuts/</b></li>
         <li><b>/system_ce/snapshots/</b></li>
         <ul>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/recentactivity.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/recentactivity.py</a></li>
         </ul>
         <li><b>/system_ce/usagestats/</b></li>
         <ul>
            <li><b>Android Usagestats XML Parser</b><br /><a href="https://abrignoni.blogspot.com/2019/02/android-usagestats-xml-parser.html">https://abrignoni.blogspot.com/2019/02/android-usagestats-xml-parser.html</a></li>
            <li><b>Identifying the Android Operating System Version thru UsageStats</b><br /><a href="https://www.sans.org/white-papers/40265/">https://www.sans.org/white-papers/40265/</a></li>
            <li><b>Usagestats on Android 10 (Q)</b><br /><a href="http://www.swiftforensics.com/2020/01/usagestats-on-android-10-q.html">http://www.swiftforensics.com/2020/01/usagestats-on-android-10-q.html</a></li>
            <li><b>Mobile Forensics: Discovering the Undiscovered</b><br /><a href="https://www.magnetforensics.com/blog/mobile-forensics-discovering-the-undiscovered/">https://www.magnetforensics.com/blog/mobile-forensics-discovering-the-undiscovered/</a></li>
            <li><b>Some artifacts in the /data/system/ directory</b><br /><a href="http://freeandroidforensics.blogspot.com/2014/11/some-artifacts-in-datasystem-directory.html">http://freeandroidforensics.blogspot.com/2014/11/some-artifacts-in-datasystem-directory.html</a></li>
            <li><b>Android Dumpsys Analysis to Indicate Driver Distraction</b><br /><a href="https://ccdcoe.org/uploads/2021/03/Android-Dumpsys-Analysis-to-Indicate-Driver-Distraction.pdf">https://ccdcoe.org/uploads/2021/03/Android-Dumpsys-Analysis-to-Indicate-Driver-Distraction.pdf</a></li>
            <li><b>Every Step You Take: Application and Network Usage in Android</b><br /><a href="https://docplayer.net/90183420-Every-step-you-take-application-and-network-usage-in-android.html">https://docplayer.net/90183420-Every-step-you-take-application-and-network-usage-in-android.html</a></li>
            <li><b>Tracking traces of deleted applications</b><br /><a href="https://www.youtube.com/watch?v=4LcQm4ErXpA">https://www.youtube.com/watch?v=4LcQm4ErXpA</a><br /><a href="https://docplayer.net/148670626-Tracking-traces-of-deleted-applications-christopher-vance-alexis-brignoni.html">https://docplayer.net/148670626-Tracking-traces-of-deleted-applications-christopher-vance-alexis-brignoni.html</a></li>
            <li><b>Android version without the build.props file</b><br /><a href="https://abrignoni.blogspot.com/2021/04/android-version-without-buildprops-file.html">https://abrignoni.blogspot.com/2021/04/android-version-without-buildprops-file.html</a></li>
            <li><b>Android Internals</b><br /><a href="http://newandroidbook.com/Book/2-Excerpt-Data.pdf">http://newandroidbook.com/Book/2-Excerpt-Data.pdf</a></li>
            <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
            <li><b>aLEAPP Plugin<br /></b><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/usagestats.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/usagestats.py</a><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/usagestatsVersion.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/usagestatsVersion.py</a></li>
         </ul>
         <li><b>/system_de/0/accounts_de.db</b></li>
         <ul>
            <li><b>Android - Tracking Device Migration<br /></b><a href="https://blog.d204n6.com/2021/06/android-tracking-device-migration.html">https://blog.d204n6.com/2021/06/android-tracking-device-migration.html</a></li>
            <li><b>Clockin’ In with Google’s Wear OS</b><br /><a href="https://thebinaryhick.blog/2021/01/13/clockin-in-with-googles-wear-os/">https://thebinaryhick.blog/2021/01/13/clockin-in-with-googles-wear-os/</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/accounts_de.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/accounts_de.py</a></li>
         </ul>
      </ul>
   </div>
</div>
<div>
   <div>
      <h2 style="text-align: left;"><b>"/user_de" folder</b></h2>
   </div>
   <ul>
      <li><b><b><b>/user_de/0/</b>com.android.bluetooth/</b>bonddevice.db</b></li>
      <ul>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2020</b><br /><a href="https://cts-forensics.com/reports/20-5550_Web.pdf">https://cts-forensics.com/reports/20-5550_Web.pdf</a></li>
      </ul>
      <li><b>/user_de/0/com.android.providers.telephony/databases/telephony.db</b></li>
      <ul>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2021</b><br /><a href="https://cts-forensics.com/reports/21-5550_Web.pdf">https://cts-forensics.com/reports/21-5550_Web.pdf</a></li>
         <li><b>Cellebrite CTF 2021 - Heisenberg's Android</b><br /><a href="https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-heisenbergs-android.html">https://www.stark4n6.com/2021/10/cellebrite-ctf-2021-heisenbergs-android.html</a></li>
         <li><b>Part 1: Walk-Through of Answers to the 2021 CTF – Investigating Heisenberg’s Android Device</b><br /><a href="https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/">https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/</a></li>
         <li><b>Cellebrite CTF 2021 Writeup</b><br /><a href="https://medium.com/@williamskosasi/cellebrite-ctf-2021-writeup-b73d821a708">https://medium.com/@williamskosasi/cellebrite-ctf-2021-writeup-b73d821a708</a></li>
         <li><b>Hex Diving — The Easy Way to Uncover Hidden Forensic Artifacts</b><br /><a href="https://cellebrite.com/en/hex-diving-the-easy-way-to-uncover-hidden-forensic-artifacts/">https://cellebrite.com/en/hex-diving-the-easy-way-to-uncover-hidden-forensic-artifacts/</a></li>
         <li><b>Android Mobile Artifacts: A Treasure Trove of Digital Evidence in Crime Investigation&nbsp;</b><br /><a href="https://www.irjet.net/archives/V8/i8/IRJET-V8I885.pdf">https://www.irjet.net/archives/V8/i8/IRJET-V8I885.pdf</a></li>
         <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
      </ul>
      <li><b><b>/user_de/0/</b>com.android.settings/databases/applist.db</b></li>
      <li><b>/user_de/0/com.samsung.accessibility/shared_prefs/accessibility_prefs.xml</b></li>
      <li><b><b>/user_de/0/</b>com.sec.imsservice/shared_prefs/capdiscovery_0.xml</b></li>
   </ul>
   <div>
      <h2 style="text-align: left;"><b>"/data" folder</b></h2>
   </div>
</div>
<div>
   <h3 style="text-align: left;"><b>Digital Wellbeing (</b><b>com.google.android.apps.wellbeing)</b></h3>
</div>
<div>
   <ul>
      <li><b>/data/com.google.android.apps.wellbeing/databases/app_usage<br /></b></li>
      <ul>
         <li><b>Walking the Android (time)line. Using Android’s Digital Wellbeing to timeline Android activity.</b><br /><a href="https://thebinaryhick.blog/2020/02/22/walking-the-android-timeline-using-androids-digital-wellbeing-to-timeline-android-activity/">https://thebinaryhick.blog/2020/02/22/walking-the-android-timeline-using-androids-digital-wellbeing-to-timeline-android-activity/</a></li>
      </ul>
   </ul>
   <div>
      <h3 style="text-align: left;"><b>Google Docs (com.google.android.apps.docs)</b></h3>
   </div>
   <ul>
      <li><b>/data/com.google.android.apps.docs/databases/DocList.db</b></li>
      <ul>
         <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/DocList.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/DocList.py</a></li>
         <li><b>Google Docs - Cello &amp; DocList DBs</b><br /><a href="https://www.stark4n6.com/2020/12/google-docs-cello-doclist-dbs.html">https://www.stark4n6.com/2020/12/google-docs-cello-doclist-dbs.html</a></li>
         <li><b>Digital Forensic Investigation of Cloud Storage Services</b><br /><a href="https://arxiv.org/ftp/arxiv/papers/1709/1709.10395.pdf">https://arxiv.org/ftp/arxiv/papers/1709/1709.10395.pdf</a></li>
         <li><b>Android Cloud Forensics - Final Findings</b><br /><a href="http://obrienforensics.blogspot.com/2014/04/final-findings.html">http://obrienforensics.blogspot.com/2014/04/final-findings.html</a><br /></li>
         <li><b>Digital Evidence Identification on Google Drive in Android Device Using NIST Mobile Forensic Method</b><br /><a href="https://pdfs.semanticscholar.org/b699/e47687819041e2cbf69fa6d6afbd0c6a3fc2.pdf">https://pdfs.semanticscholar.org/b699/e47687819041e2cbf69fa6d6afbd0c6a3fc2.pdf</a></li>
         <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2017</b><br /><a href="https://cts-forensics.com/reports/37550_Web.pdf">https://cts-forensics.com/reports/37550_Web.pdf</a></li>
         <li><b>Proposed Method for Mobile Forensics Investigation Analysis of Remnant Data on Google Drive Client<br /></b><a href="https://jit.ndhu.edu.tw/article/download/1795/1801">https://jit.ndhu.edu.tw/article/download/1795/1801</a></li>
         <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
      </ul>
   </ul>
   <div>
      <h3 style="text-align: left;">
         <b>Files by Google (com.google.android.apps.nbu.files)</b>
   </div>
   <ul><li><b>/data/com.google.android.apps.nbu.files/databases/files_master_database</b></li><ul><li><b>Files By Google: More Mobile Explorer Artifacts</b></h3><br /><a href="https://www.stark4n6.com/2021/01/files-by-google-more-mobile-explorer.html">https://www.stark4n6.com/2021/01/files-by-google-more-mobile-explorer.html</a></li><li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/FilesByGoogle_FilesMaster.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/FilesByGoogle_FilesMaster.py</a></li></ul><li><b>/data/com.google.android.apps.nbu.files/databases/search_history_database</b></li><ul><li><b>Files By Google: More Mobile Explorer Artifacts</b><br /><a href="https://www.stark4n6.com/2021/01/files-by-google-more-mobile-explorer.html">https://www.stark4n6.com/2021/01/files-by-google-more-mobile-explorer.html</a></li><li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/FilesByGoogle_SearchHistory.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/FilesByGoogle_SearchHistory.py</a></li></ul></ul>
   <div>
      <h3 style="text-align: left;"><b>Device Health Services (com.google.android.apps.turbo)</b></h3>
   </div>
   <ul>
      <li><b>/data/com.google.android.apps.turbo/databases/turbo.db</b></li>
      <ul>
         <li><b>Charging Battery with Turbo DB</b><br /><a href="https://www.stark4n6.com/2020/12/charging-battery-with-turbo-db.html">https://www.stark4n6.com/2020/12/charging-battery-with-turbo-db.html</a></li>
         <li><b>Part 2: CTF 2022 Write Up – Heisenberg’s Android</b><br /><a href="https://cellebrite.com/en/part-2-ctf-2022-write-up-heisenbergs-android/">https://cellebrite.com/en/part-2-ctf-2022-write-up-heisenbergs-android/</a></li>
         <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/Turbo_Battery.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/Turbo_Battery.py</a></li>
      </ul>
      <li><b>/data/com.google.android.apps.turbo/databases/bluetooth.db</b></li>
      <ul>
         <li><b>Turbo Strikes Again - Tracking Bluetooth Device Battery</b><br /><a href="https://www.stark4n6.com/2021/06/turbo-strikes-again-tracking-bluetooth.html">https://www.stark4n6.com/2021/06/turbo-strikes-again-tracking-bluetooth.html</a></li>
         <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/Turbo_Battery.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/Turbo_Battery.py</a></li>
      </ul>
      <li><b>/data/com.google.android.apps.turbo/shared_prefs/app_usage_stats.xml</b></li>
      <ul>
         <li><b>Turbo Pt. 3 - Device Health Services Application Usage</b><br /><a href="https://www.stark4n6.com/2021/06/turbo-application-usage.html">https://www.stark4n6.com/2021/06/turbo-application-usage.html</a></li>
         <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/Turbo_AppUsage.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/Turbo_AppUsage.py</a></li>
      </ul>
   </ul>
   <div>
      <h3 style="text-align: left;"><b>Settings Services (com.google.android.settings.intelligence)</b></h3>
   </div>
   <ul>
      <li><b>/data/com.google.android.settings.intelligence/databases/battery-usage-db-v4</b></li>
      <ul>
         <li><b>Application Battery Usage via Settings Services</b><br /><a href="https://www.stark4n6.com/2021/12/application-battery-usage-via-settings.html">https://www.stark4n6.com/2021/12/application-battery-usage-via-settings.html</a></li>
         <li><b>Examining A Malware-Infected Android Phone. This Android Is Not Alright.</b><br /><a href="https://thebinaryhick.blog/2022/04/09/examining-a-malware-infected-android-phone-this-android-is-not-alright/">https://thebinaryhick.blog/2022/04/09/examining-a-malware-infected-android-phone-this-android-is-not-alright/</a></li>
         <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/battery_usage_v4.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/battery_usage_v4.py</a></li>
      </ul>
   </ul>
   <div>
      <h3 style="text-align: left;"><b>Google Play Service (com.google.android.gms)</b></h3>
   </div>
   <div>
      <ul style="text-align: left;">
         <li><b>/data/com.google.android.gms/databases/cast.db</b></li>
         <ul>
            <li><b>An Android Casting (Device) Story: "cast.db"</b><br /><a href="https://deagler4n6blog.blogspot.com/2021/01/a-casting-story-castdb.html">https://deagler4n6blog.blogspot.com/2021/01/a-casting-story-castdb.html</a></li>
         </ul>
         <li><b>/data/com.google.android.gms/databases/constellation.db</b></li>
         <ul>
            <li><b>Hex Diving — The Easy Way to Uncover Hidden Forensic Artifacts</b><br /><a href="https://cellebrite.com/en/hex-diving-the-easy-way-to-uncover-hidden-forensic-artifacts/">https://cellebrite.com/en/hex-diving-the-easy-way-to-uncover-hidden-forensic-artifacts/</a></li>
         </ul>
         <li><b>/data/com.google.android.gms/databases/gass.db</b></li>
         <ul>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2021</b><br /><a href="https://cts-forensics.com/reports/21-5550_Web.pdf">https://cts-forensics.com/reports/21-5550_Web.pdf</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/installedappsGass.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/installedappsGass.py</a></li>
         </ul>
         <li><b>/data/com.google.android.gms/databases/gms.notifications.db</b></li>
         <li><b><b>/data/com.google.android.gms/databases/</b>google_account_history.db</b></li>
         <li><b>/data/com.google.android.gms/databases/google_app_measurement.db</b></li>
         <ul>
            <li><b>Forensics on Android Applications<br /></b><a href="https://dione.lib.unipi.gr/xmlui/bitstream/handle/unipi/11306/Kitsaki_mte1618.pdf?isAllowed=y&amp;sequence=1">https://dione.lib.unipi.gr/xmlui/bitstream/handle/unipi/11306/Kitsaki_mte1618.pdf?isAllowed=y&amp;sequence=1</a></li>
            <li><b>Forensic Analysis of the Bumble Dating App for Android</b><br /><a href="https://www.mdpi.com/2673-6756/2/1/16/htm">https://www.mdpi.com/2673-6756/2/1/16/htm</a></li>
         </ul>
         <li><b>/data/com.google.android.gms/databases/herrevad</b></li>
         <ul>
            <li><b>HERREVAD Databases Geo Location Artefacts</b><br /><a href="http://trewmte.blogspot.com/2017/02/herrevad-databases-geo-location.html">http://trewmte.blogspot.com/2017/02/herrevad-databases-geo-location.html</a></li>
            <li><b>Update - HERREVAD Databases Geo Location Artefacts</b><br /><a href="http://trewmte.blogspot.com/2018/07/update-herrevad-databases-geo-location.html">http://trewmte.blogspot.com/2018/07/update-herrevad-databases-geo-location.html</a><br /></li>
            <li><b>Update2 - HERREVAD Databases Geo Location Artefacts</b><br /><a href="http://trewmte.blogspot.com/2019/05/update2-herrevad-databases-geo-location.html">http://trewmte.blogspot.com/2019/05/update2-herrevad-databases-geo-location.html</a></li>
            <li><b>Update3 - HERREVAD Databases Geo Location Artefacts</b><br /><a href="http://trewmte.blogspot.com/2019/12/update3-herrevad-databases-geo-location.html">http://trewmte.blogspot.com/2019/12/update3-herrevad-databases-geo-location.html</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2019</b><br /><a href="https://cts-forensics.com/reports/19-5550_Web.pdf">https://cts-forensics.com/reports/19-5550_Web.pdf</a></li>
         </ul>
         <li><b>/data/com.google.android.gms/databases/icing_contacts.db</b></li>
         <ul>
            <li><b>Recovering data from broken screen Android phone - alternative</b><br /><a href="https://hackcorrelation.blogspot.com/2016/10/recovering-data-from-broken-screen.html">https://hackcorrelation.blogspot.com/2016/10/recovering-data-from-broken-screen.html</a></li>
         </ul>
         <li><b>/data/com.google.android.gms/databases/icing_mmssms.db</b></li>
         <ul>
            <li><b>Cellebrite-icing_mmssms.db-Parser</b><br /><a href="https://github.com/python-for-mobile-forensics/Cellebrite-icing_mmssms.db-Parser/blob/master/README.md">https://github.com/python-for-mobile-forensics/Cellebrite-icing_mmssms.db-Parser/blob/master/README.md</a></li>
            <li><b>Android Messaging Forensics – SMS/MMS and Beyond</b><br /><a href="https://www.magnetforensics.com/blog/android-messaging-forensics-sms-mms-and-beyond/">https://www.magnetforensics.com/blog/android-messaging-forensics-sms-mms-and-beyond/</a></li>
         </ul>
         <li><b>/data/data/com.google.android.gms/databases/MdpSimBasedDatabase</b></li>
         <ul>
            <li><b>Hex Diving — The Easy Way to Uncover Hidden Forensic Artifacts</b><br /><a href="https://cellebrite.com/en/hex-diving-the-easy-way-to-uncover-hidden-forensic-artifacts/">https://cellebrite.com/en/hex-diving-the-easy-way-to-uncover-hidden-forensic-artifacts/</a></li>
         </ul>
         <li><b>/data/com.google.android.gms/databases/NetworkUsage.db</b></li>
         <ul>
            <li><b>Providing Context to the Clues: Recovery and Reliability of Location Data from Android Devices</b><br /><a href="https://stars.library.ucf.edu/cgi/viewcontent.cgi?referer=&amp;httpsredir=1&amp;article=2353&amp;context=etd">https://stars.library.ucf.edu/cgi/viewcontent.cgi?referer=&amp;httpsredir=1&amp;article=2353&amp;context=etd</a></li>
         </ul>
         <li><b>/data/com.google.android.gms/databases/ns.db</b></li>
         <li><b>/data/com.google.android.gms/databases/reminders.db</b></li>
         <ul>
            <li><b>Smart Speakers Forensics</b><br /><a href="https://core.ac.uk/download/pdf/230544843.pdf">https://core.ac.uk/download/pdf/230544843.pdf</a></li>
         </ul>
         <li><b>/data/com.google.android.gms/shared_prefs/batterystats.xml<br /></b></li>
         <ul>
            <li><b>Every Step You Take: Application and Network Usage in Android</b><br /><a href="https://docplayer.net/90183420-Every-step-you-take-application-and-network-usage-in-android.html">https://docplayer.net/90183420-Every-step-you-take-application-and-network-usage-in-android.html</a></li>
         </ul>
         <li><b>/data/com.google.android.gms/shared_prefs/adid_settings.xml</b></li>
         <li><b>/data/com.google.android.gms/shared_prefs/BackupAccount.xml</b></li>
         <ul>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2021<br /></b><a href="https://cts-forensics.com/reports/21-5550_Web.pdf">https://cts-forensics.com/reports/21-5550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2022<br /></b><a href="https://cts-forensics.com/reports/22-5550_Web.pdf">https://cts-forensics.com/reports/22-5550_Web.pdf</a></li>
         </ul>
         <li><b>/data/com.google.android.gms/shared_prefs/Checkin.xml</b></li>
         <ul>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2018</b><br /><a href="https://cts-forensics.com/reports/38550_Web.pdf">https://cts-forensics.com/reports/38550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2019</b><br /><a href="https://cts-forensics.com/reports/19-5550_Web.pdf">https://cts-forensics.com/reports/19-5550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2020</b><br /><a href="https://cts-forensics.com/reports/20-5550_Web.pdf">https://cts-forensics.com/reports/20-5550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2021</b><br /><a href="https://cts-forensics.com/reports/21-5550_Web.pdf">https://cts-forensics.com/reports/21-5550_Web.pdf</a></li>
            <li><b>Hex Diving — The Easy Way to Uncover Hidden Forensic Artifacts</b><br /><a href="https://cellebrite.com/en/hex-diving-the-easy-way-to-uncover-hidden-forensic-artifacts/">https://cellebrite.com/en/hex-diving-the-easy-way-to-uncover-hidden-forensic-artifacts/</a></li>
            <li><b>Cellebrite CTF 2021 Writeup</b><br /><a href="https://medium.com/@williamskosasi/cellebrite-ctf-2021-writeup-b73d821a708">https://medium.com/@williamskosasi/cellebrite-ctf-2021-writeup-b73d821a708</a></li>
            <li><b>Cellebrite CTF 2022 - Heisenberg's Android</b><br /><a href="https://www.stark4n6.com/2022/06/cellebrite-ctf-2022-heisenbergs-android.html">https://www.stark4n6.com/2022/06/cellebrite-ctf-2022-heisenbergs-android.html</a></li>
         </ul>
         <li><b>/data/com.google.android.gms/shared_prefs/nearbysharing:service:state.xml</b></li>
         <ul>
            <li><b>Nearby Share – AirDrop for Android (Return of the Unsolicited Richard Photograph)</b><br /><a href="https://thebinaryhick.blog/2020/08/22/nearby-share-airdrop-for-android-return-of-the-unsolicited-richard-photograph/">https://thebinaryhick.blog/2020/08/22/nearby-share-airdrop-for-android-return-of-the-unsolicited-richard-photograph/</a></li>
         </ul>
      </ul>
      <p>
      <h3 style="text-align: left;"><b>Google Play Store (com.android.vending)</b></h3>
      </p>
      <ul>
         <li><b>/data/com.android.vending/databases/data_usage.db</b></li>
         <ul>
            <li><b>Forensic investigation of Cisco WebEx desktop client, web, and Android smartphone applications</b><br /><a href="https://link.springer.com/article/10.1007/s12243-022-00919-6">https://link.springer.com/article/10.1007/s12243-022-00919-6</a></li>
         </ul>
         <li><b>/data/com.android.vending/databases/frosting.db</b></li>
         <ul>
            <li><b>Analysis of application installation logs on Android systems</b><br /><a href="https://dl.acm.org/doi/10.1145/3297280.3297489">https://dl.acm.org/doi/10.1145/3297280.3297489</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/frosting.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/frosting.py</a></li>
         </ul>
         <li><b>/data/com.android.vending/databases/install_queue.db</b></li>
         <ul>
            <li><b>Forensic investigation of Cisco WebEx desktop client, web, and Android smartphone applications</b><br /><a href="https://link.springer.com/article/10.1007/s12243-022-00919-6">https://link.springer.com/article/10.1007/s12243-022-00919-6</a></li>
         </ul>
         <li><b>/data/com.android.vending/databases/library.db</b></li>
         <ul>
            <li><b>Mobile Forensics: Discovering the Undiscovered</b><br /><a href="https://www.magnetforensics.com/blog/mobile-forensics-discovering-the-undiscovered/">https://www.magnetforensics.com/blog/mobile-forensics-discovering-the-undiscovered/</a></li>
            <li><b>Analysis of application installation logs on Android systems</b><br /><a href="https://dl.acm.org/doi/10.1145/3297280.3297489">https://dl.acm.org/doi/10.1145/3297280.3297489</a></li>
            <li><b>CTF Cellebrite CTF 2020: Rene Gade</b><br /><a href="https://ciofecaforensics.com/2020/10/31/cellebrite-ctf-rene/">https://ciofecaforensics.com/2020/10/31/cellebrite-ctf-rene/</a></li>
            <li><b>Tracking traces of deleted applications</b><br /><a href="https://www.youtube.com/watch?v=4LcQm4ErXpA">https://www.youtube.com/watch?v=4LcQm4ErXpA</a><br /><a href="https://docplayer.net/148670626-Tracking-traces-of-deleted-applications-christopher-vance-alexis-brignoni.html">https://docplayer.net/148670626-Tracking-traces-of-deleted-applications-christopher-vance-alexis-brignoni.html</a></li>
            <li><b>Every Step You Take: Application and Network Usage in Android</b><br /><a href="https://docplayer.net/90183420-Every-step-you-take-application-and-network-usage-in-android.html">https://docplayer.net/90183420-Every-step-you-take-application-and-network-usage-in-android.html</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/installedappsLibrary.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/installedappsLibrary.py</a></li>
         </ul>
         <li><b>/data/com.android.vending/databases/localappstate.db</b></li>
         <ul>
            <li><b>Analysis of application installation logs on Android systems</b><br /><a href="https://dl.acm.org/doi/10.1145/3297280.3297489">https://dl.acm.org/doi/10.1145/3297280.3297489</a></li>
            <li><b>Tracking traces of deleted applications</b><br /><a href="https://www.youtube.com/watch?v=4LcQm4ErXpA">https://www.youtube.com/watch?v=4LcQm4ErXpA</a><br /><a href="https://docplayer.net/148670626-Tracking-traces-of-deleted-applications-christopher-vance-alexis-brignoni.html">https://docplayer.net/148670626-Tracking-traces-of-deleted-applications-christopher-vance-alexis-brignoni.html</a></li>
            <li><b>Part 2: CTF 2022 Write Up – Heisenberg’s Android</b><br /><a href="https://cellebrite.com/en/part-2-ctf-2022-write-up-heisenbergs-android/">https://cellebrite.com/en/part-2-ctf-2022-write-up-heisenbergs-android/</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2015</b><br /><a href="https://cts-forensics.com/reports/35550_Web.pdf">https://cts-forensics.com/reports/35550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2016</b><br /><a href="https://cts-forensics.com/reports/36550_Web.pdf">https://cts-forensics.com/reports/36550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2017</b><br /><a href="https://cts-forensics.com/reports/37550_Web.pdf">https://cts-forensics.com/reports/37550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2018</b><br /><a href="https://cts-forensics.com/reports/38550_Web.pdf">https://cts-forensics.com/reports/38550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2019</b><br /><a href="https://cts-forensics.com/reports/19-5550_Web.pdf">https://cts-forensics.com/reports/19-5550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2020</b><br /><a href="https://cts-forensics.com/reports/20-5550_Web.pdf">https://cts-forensics.com/reports/20-5550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2021<br /></b><a href="https://cts-forensics.com/reports/21-5550_Web.pdf">https://cts-forensics.com/reports/21-5550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2022<br /></b><a href="https://cts-forensics.com/reports/22-5550_Web.pdf">https://cts-forensics.com/reports/22-5550_Web.pdf</a></li>
            <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/installedappsVending.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/installedappsVending.py</a></li>
         </ul>
         <li><b>/data/com.android.vending/databases/package_verification.db</b></li>
         <ul>
            <li><b>Tracking traces of deleted applications</b><br /><a href="https://www.youtube.com/watch?v=4LcQm4ErXpA">https://www.youtube.com/watch?v=4LcQm4ErXpA</a><br /><a href="https://docplayer.net/148670626-Tracking-traces-of-deleted-applications-christopher-vance-alexis-brignoni.html">https://docplayer.net/148670626-Tracking-traces-of-deleted-applications-christopher-vance-alexis-brignoni.html</a></li>
         </ul>
         <li><b>/data/com.android.vending/databases/suggestions.db</b></li>
         <ul>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2015</b><br /><a href="https://cts-forensics.com/reports/35550_Web.pdf">https://cts-forensics.com/reports/35550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2016</b><br /><a href="https://cts-forensics.com/reports/36550_Web.pdf">https://cts-forensics.com/reports/36550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2017</b><br /><a href="https://cts-forensics.com/reports/37550_Web.pdf">https://cts-forensics.com/reports/37550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2018</b><br /><a href="https://cts-forensics.com/reports/38550_Web.pdf">https://cts-forensics.com/reports/38550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2019</b><br /><a href="https://cts-forensics.com/reports/19-5550_Web.pdf">https://cts-forensics.com/reports/19-5550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2020</b><br /><a href="https://cts-forensics.com/reports/20-5550_Web.pdf">https://cts-forensics.com/reports/20-5550_Web.pdf</a></li>
            <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
         </ul>
         <li><b>/data/com.android.vending/databases/verify_apps.db</b></li>
         <ul>
            <li><b>Forensic investigation of Cisco WebEx desktop client, web, and Android smartphone applications</b><br /><a href="https://link.springer.com/article/10.1007/s12243-022-00919-6">https://link.springer.com/article/10.1007/s12243-022-00919-6</a></li>
         </ul>
      </ul>
      <div>
         <p>
         <h3 style="text-align: left;">
            <b>Google Quick Search (com.google.android.googlequicksearchbox)</b>
         </h3>
         </p>
         <p></p>
         <ul>
            <li><b>Google Search &amp; Personal Assistant data on android</b><br /><a href="http://www.swiftforensics.com/2020/03/google-search-personal-assistant-data.html">http://www.swiftforensics.com/2020/03/google-search-personal-assistant-data.html</a></li>
            <li><b>Google Search Bar &amp; Search Term History – Are You Finding Everything?</b><br /><a href="https://thebinaryhick.blog/2019/03/20/google-search-bar-search-term-history-are-you-finding-everything/">https://thebinaryhick.blog/2019/03/20/google-search-bar-search-term-history-are-you-finding-everything/</a></li>
            <li><b>Forensic Investigation of Google Assistant</b><br /><a href="https://link.springer.com/article/10.1007/s42979-020-00285-x">https://link.springer.com/article/10.1007/s42979-020-00285-x</a></li>
            <li><b>How Android Bluetooth Connections Can Determine if a Driver had Their Hands on the Wheel During an Accident</b><br /><a href="https://dfir.pubpub.org/pub/6ysxvhvc/release/1">https://dfir.pubpub.org/pub/6ysxvhvc/release/1</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2016</b><br /><a href="https://cts-forensics.com/reports/36550_Web.pdf">https://cts-forensics.com/reports/36550_Web.pdf</a></li>
            <li><b>DroidForensics: Accurate Reconstruction of Android Attacks via Multi-layer Forensic Logging</b><br /><a href="https://kyuhlee.github.io/publications/asiaccs17.pdf">https://kyuhlee.github.io/publications/asiaccs17.pdf</a></li>
            <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/googleQuickSearchbox.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/googleQuickSearchbox.py</a><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/googleQuickSearchboxRecent.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/googleQuickSearchboxRecent.py</a></li>
         </ul>
      </div>
      <div>
         <h3 style="text-align: left;">
            <b>Google Services Framework (com.google.android.gsf)</b>
         </h3>
      </div>
      <div>
         <ul>
            <li><b>/data/com.google.android.gsf/databases/gservices.db</b></li>
            <ul>
               <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2022</b><br /><a href="https://cts-forensics.com/reports/22-5550_Web.pdf">https://cts-forensics.com/reports/22-5550_Web.pdf</a></li>
            </ul>
            <li><b>/data/com.google.android.gsf/databases/googlesettings.db</b></li>
            <ul>
               <li><b>Forensic Analysis of Wireless Networking Evidence of Android Smartphones</b><br /><a href="https://www.fortoo.eu/m/page-media/4/Andriotis-2012-1-wifs.pdf">https://www.fortoo.eu/m/page-media/4/Andriotis-2012-1-wifs.pdf</a></li>
               <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2018</b><br /><a href="https://cts-forensics.com/reports/38550_Web.pdf">https://cts-forensics.com/reports/38550_Web.pdf</a></li>
               <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/pSettings.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/pSettings.py</a></li>
            </ul>
         </ul>
         <div>
            <h3 style="text-align: left;">
               <b>Messages (com.google.android.apps.messaging)</b>
            </h3>
         </div>
         <div>
            <ul>
               <li><b>/data/com.google.android.apps.messaging/databases/bugle_db</b></li>
               <ul>
                  <li><b>Hex Diving — The Easy Way to Uncover Hidden Forensic Artifacts</b><br /><a href="https://cellebrite.com/en/hex-diving-the-easy-way-to-uncover-hidden-forensic-artifacts/">https://cellebrite.com/en/hex-diving-the-easy-way-to-uncover-hidden-forensic-artifacts/</a></li>
                  <li><b>Android Messaging Forensics – SMS/MMS and Beyond</b><br /><a href="https://www.magnetforensics.com/blog/android-messaging-forensics-sms-mms-and-beyond/">https://www.magnetforensics.com/blog/android-messaging-forensics-sms-mms-and-beyond/</a></li>
                  <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
               </ul>
               <li><b>/data/com.google.android.apps.messaging/shared_prefs/sim_state_tracker.xml</b></li>
            </ul>
         </div>
      </div>
   </div>
</div>
<div>
   <div>
      <h3 style="text-align: left;">
         <b>Samsung One UI Home (com.sec.android.app.launcher)</b>
      </h3>
   </div>
   <div>
      <ul>
         <li><b>Recreate Android apps, folders, and widget screen positions from a forensic extraction</b><br /><a href="https://abrignoni.blogspot.com/2019/10/recreate-android-apps-folders-and.html">https://abrignoni.blogspot.com/2019/10/recreate-android-apps-folders-and.html</a></li>
      </ul>
      <div>
         <h3 style="text-align: left;">
            <b>Android Contacts Storage (</b><b>com.android.providers.contacts)</b>
         </h3>
      </div>
      <div>
         <ul style="text-align: left;">
            <li><b>/data/com.android.providers.contacts/databases/calllog.db</b></li>
            <ul>
               <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2020</b><br /><a href="https://cts-forensics.com/reports/20-5550_Web.pdf">https://cts-forensics.com/reports/20-5550_Web.pdf</a></li>
               <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2021<br /></b><a href="https://cts-forensics.com/reports/21-5550_Web.pdf">https://cts-forensics.com/reports/21-5550_Web.pdf</a></li>
               <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2022<br /></b><a href="https://cts-forensics.com/reports/22-5550_Web.pdf">https://cts-forensics.com/reports/22-5550_Web.pdf</a></li>
               <li><b>Hex Diving — The Easy Way to Uncover Hidden Forensic Artifacts</b><br /><a href="https://cellebrite.com/en/hex-diving-the-easy-way-to-uncover-hidden-forensic-artifacts/">https://cellebrite.com/en/hex-diving-the-easy-way-to-uncover-hidden-forensic-artifacts/</a></li>
               <li><b>Calllog.db and SMS data on Android 7.0 Nougat</b><br /><a href="https://forensenellanebbia.blogspot.com/2018/10/calllogdb-and-sms-data-on-android-70.html">https://forensenellanebbia.blogspot.com/2018/10/calllogdb-and-sms-data-on-android-70.html</a><br /></li>
               <li><b>Android Mobile Artifacts: A Treasure Trove of Digital Evidence in Crime Investigation&nbsp;</b><br /><a href="https://www.irjet.net/archives/V8/i8/IRJET-V8I885.pdf">https://www.irjet.net/archives/V8/i8/IRJET-V8I885.pdf</a></li>
               <li><b>Call Log query</b><br /><a href="https://github.com/kacos2000/Queries/blob/master/calllog_db.sql">https://github.com/kacos2000/Queries/blob/master/calllog_db.sql</a></li>
               <li><b>Learning Android Forensics - Second Edition</b><br /><a href="https://www.packtpub.com/product/learning-android-forensics-second-edition/9781789131017">https://www.packtpub.com/product/learning-android-forensics-second-edition/9781789131017</a></li>
               <li><b>Practical Mobile Forensics - Fourth Edition</b><br /><a href="https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520">https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520</a></li>
               <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/calllog.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/calllog.py</a></li>
            </ul>
            <li><b>/data/com.android.providers.contacts/databases/contacts2.db</b></li>
            <ul>
               <li><b>Open Source Mobile Device Forensics</b><br /><a href="https://smarterforensics.com/wp-content/uploads/2014/06/OpenSourceMobileForensics.pdf">https://smarterforensics.com/wp-content/uploads/2014/06/OpenSourceMobileForensics.pdf</a></li>
               <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2016</b><br /><a href="https://cts-forensics.com/reports/36550_Web.pdf">https://cts-forensics.com/reports/36550_Web.pdf</a></li>
               <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2017</b><br /><a href="https://cts-forensics.com/reports/37550_Web.pdf">https://cts-forensics.com/reports/37550_Web.pdf</a></li>
               <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2018</b><br /><a href="https://cts-forensics.com/reports/38550_Web.pdf">https://cts-forensics.com/reports/38550_Web.pdf</a></li>
               <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2019</b><br /><a href="https://cts-forensics.com/reports/19-5550_Web.pdf">https://cts-forensics.com/reports/19-5550_Web.pdf</a></li>
               <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2020</b><br /><a href="https://cts-forensics.com/reports/20-5550_Web.pdf">https://cts-forensics.com/reports/20-5550_Web.pdf</a></li>
               <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2021</b><br /><a href="https://cts-forensics.com/reports/21-5550_Web.pdf">https://cts-forensics.com/reports/21-5550_Web.pdf</a></li>
               <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2022<br /></b><a href="https://cts-forensics.com/reports/22-5550_Web.pdf">https://cts-forensics.com/reports/22-5550_Web.pdf</a></li>
               <li><b>Android Mobile Artifacts: A Treasure Trove of Digital Evidence in Crime Investigation&nbsp;</b><br /><a href="https://www.irjet.net/archives/V8/i8/IRJET-V8I885.pdf">https://www.irjet.net/archives/V8/i8/IRJET-V8I885.pdf</a></li>
               <li><b>Contacts query</b><br /><a href="https://github.com/kacos2000/Queries/blob/master/contacts2.sql">https://github.com/kacos2000/Queries/blob/master/contacts2.sql</a></li>
               <li><b>Contacts calls query</b><br /><a href="https://github.com/kacos2000/Queries/blob/master/contacts2calls.sql">https://github.com/kacos2000/Queries/blob/master/contacts2calls.sql</a></li>
               <li><b>Learning Android Forensics - Second Edition</b><br /><a href="https://www.packtpub.com/product/learning-android-forensics-second-edition/9781789131017">https://www.packtpub.com/product/learning-android-forensics-second-edition/9781789131017</a></li>
               <li><b>Practical Mobile Forensics - Fourth Edition</b><br /><a href="https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520">https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520</a></li>
               <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
               <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/contacts.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/contacts.py</a></li>
            </ul>
            <li><b>/data/com.android.providers.contacts/files/photos/</b></li>
            <ul>
               <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2021</b><br /><a href="https://cts-forensics.com/reports/21-5550_Web.pdf">https://cts-forensics.com/reports/21-5550_Web.pdf</a></li>
            </ul>
         </ul>
      </div>
      <div>
         <h3 style="text-align: left;">
            <b>Android Messaging Storage (com.android.providers.telephony)</b>
         </h3>
      </div>
      <ul style="text-align: left;">
         <li><b>/data/user_de/0/com.android.providers.telephony/databases/mmssms.db</b><br /><b>/data/com.android.providers.telephony/databases/mmssms.db</b></li>
         <ul>
            <li><b>Android Messaging Forensics – SMS/MMS and Beyond</b><br /><a href="https://www.magnetforensics.com/blog/android-messaging-forensics-sms-mms-and-beyond/">https://www.magnetforensics.com/blog/android-messaging-forensics-sms-mms-and-beyond/</a></li>
            <li><b>Android mmssms.db each table introduction</b><br /><a href="https://blog.katastros.com/a?ID=00250-640c0b9b-4c94-4928-9250-7406735e59a2">https://blog.katastros.com/a?ID=00250-640c0b9b-4c94-4928-9250-7406735e59a2</a></li>
            <li><b>Part 1: Walk-Through of Answers to the 2021 CTF – Investigating Heisenberg’s Android Device</b><br /><a href="https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/">https://cellebrite.com/en/part-1-walk-through-of-answers-to-the-2021-ctf-investigating-heisenbergs-android-device/</a></li>
            <li><b>Cellebrite CTF 2022 - Heisenberg's Android</b><br /><a href="https://www.stark4n6.com/2022/06/cellebrite-ctf-2022-heisenbergs-android.html">https://www.stark4n6.com/2022/06/cellebrite-ctf-2022-heisenbergs-android.html</a></li>
            <li><b>Learning Android Forensics - Second Edition</b><br /><a href="https://www.packtpub.com/product/learning-android-forensics-second-edition/9781789131017">https://www.packtpub.com/product/learning-android-forensics-second-edition/9781789131017</a></li>
            <li><b>Practical Mobile Forensics - Fourth Edition</b><br /><a href="https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520">https://www.packtpub.com/product/practical-mobile-forensics-fourth-edition/9781838647520</a></li>
            <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
            <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/smsmms.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/smsmms.py</a></li>
         </ul>
         <li><b>/data/com.android.providers.telephony/databases/app_parts/</b></li>
         <ul>
            <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
         </ul>
      </ul>
      <div>
         <h3 style="text-align: left;">
            <b>Android Calendar Storage (</b><b>com.android.providers.calendar)</b>
         </h3>
      </div>
      <ul style="text-align: left;">
         <li><b>/data/com.android.providers.calendar/databases/calendar.db</b></li>
         <ul>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2016</b><br /><a href="https://cts-forensics.com/reports/36550_Web.pdf">https://cts-forensics.com/reports/36550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2017</b><br /><a href="https://cts-forensics.com/reports/37550_Web.pdf">https://cts-forensics.com/reports/37550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2018</b><br /><a href="https://cts-forensics.com/reports/38550_Web.pdf">https://cts-forensics.com/reports/38550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2019</b><br /><a href="https://cts-forensics.com/reports/19-5550_Web.pdf">https://cts-forensics.com/reports/19-5550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2020</b><br /><a href="https://cts-forensics.com/reports/20-5550_Web.pdf">https://cts-forensics.com/reports/20-5550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2021</b><br /><a href="https://cts-forensics.com/reports/21-5550_Web.pdf">https://cts-forensics.com/reports/21-5550_Web.pdf</a></li>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2022<br /></b><a href="https://cts-forensics.com/reports/22-5550_Web.pdf">https://cts-forensics.com/reports/22-5550_Web.pdf</a></li>
         </ul>
         <li><b>/data/data/com.google.android.calendar/databases/cal_v2a</b></li>
         <ul>
            <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2022<br /></b><a href="https://cts-forensics.com/reports/22-5550_Web.pdf">https://cts-forensics.com/reports/22-5550_Web.pdf</a></li>
         </ul>
      </ul>
      <div>
         <div>
            <h3 style="text-align: left;">
               <b>Android Media Storage</b>
            </h3>
         </div>
         <div>
            <ul>
               <li><b>/data/com.google.android.providers.media.module/databases/external.db</b></li>
               <ul>
                  <li><b>Android’s external.db – Everything Old Is New Again<br /></b><a href="https://thebinaryhick.blog/2020/10/19/androids-external-db-everything-old-is-new-again/">https://thebinaryhick.blog/2020/10/19/androids-external-db-everything-old-is-new-again/</a></li>
                  <li><b>Mobile Forensic Investigations A Guide to Evidence Collection, Analysis, and Presentation - Second Edition</b><br /><a href="https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/">https://www.oreilly.com/library/view/mobile-forensic-investigations/9781260135107/</a></li>
                  <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/emulatedSmeta.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/emulatedSmeta.py</a></li>
               </ul>
            </ul>
            <div>
               <h3 style="text-align: left;">
                  <b>Android Logs Provider (com.sec.android.provider.logsprovider)</b>
               </h3>
            </div>
            <div>
               <ul>
                  <li><b>/data/com.sec.android.provider.logsprovider/databases/logs.db</b></li>
                  <ul>
                     <li><b>Android Messaging Forensics – SMS/MMS and Beyond</b><br /><a href="https://www.magnetforensics.com/blog/android-messaging-forensics-sms-mms-and-beyond/">https://www.magnetforensics.com/blog/android-messaging-forensics-sms-mms-and-beyond/</a></li>
                     <li><b>Logs provider query</b><br /><a href="https://github.com/kacos2000/Queries/blob/master/logs_db.sql">https://github.com/kacos2000/Queries/blob/master/logs_db.sql</a></li>
                     <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2015</b><br /><a href="https://cts-forensics.com/reports/35550_Web.pdf">https://cts-forensics.com/reports/35550_Web.pdf</a></li>
                     <li><b>Collaborative Testing Services - Mobile Digital Evidence - 2018</b><br /><a href="https://cts-forensics.com/reports/38550_Web.pdf">https://cts-forensics.com/reports/38550_Web.pdf</a></li>
                     <li><b>aLEAPP Plugin</b><br /><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/calllogs.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/calllogs.py</a></li>
                  </ul>
               </ul>
            </div>
            <div>
               <h3 style="text-align: left;">
                  <b>Android Location (</b><b>com.google.android.location)</b>
               </h3>
            </div>
            <div>
               <ul>
                  <li><b>/data/</b><b>com.google.android.location</b><b>/files/cache.cell/cache.wifi<br /></b><b>/data/com.google.android.location/files/cache.cell/cache.cell</b></li>
                  <ul>
                     <li><b>Decoding cache.cell and cache.wifi files<br /></b><a href="https://forensics.spreitzenbarth.de/2011/10/28/decoding-cache-cell-and-cache-wifi-files/">https://forensics.spreitzenbarth.de/2011/10/28/decoding-cache-cell-and-cache-wifi-files/</a></li>
                     <li><b>aLEAPP Plugin<br /></b><a href="https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/cachelocation.py">https://github.com/abrignoni/ALEAPP/blob/master/scripts/artifacts/cachelocation.py</a></li>
                  </ul>
               </ul>
            </div>
         </div>
      </div>
   </div>
</div>
<p></p>
