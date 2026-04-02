<h1>This is a full guide on booting from a usb drive or a external ssd (windows laptop). read till the end</h1>
<h2>Uses of usb booting</h2>
<p>USB booting is extremely useful. It refers to the process of running everything from the external storage, instead of the computer's native SSD.  Some of it's uses are:</p>
<ul>
  <li>Recovering computer if native ssd is corrupted/unable to boot.</li>
  <li>Bypassing restrictions set on the native SSD</li>
</ul>
<p>This process is completely separate from the computer's native SSD and will not touch data stored on the native SSD whatsoever. It is not detectable by any monitoring applications installed on the main SSD either, making it useful for bypassing set restrictions.</p>
<p><b><u>Before you decide to do this, I am not reponsible for any damage or consequences whatsoever caused by this. Use at your own risk.</u></b></p>
<hr>
<h2>Prepping computer for USB booting</h2>
<p>Open up BIOS settings. Can be done by pressing a specific key during your computer's startup process. Alternatively, a surefire way if you're struggling with opening up bios is by pressing the windows button at the middle of the taskbar and clicking the power icon at the botton right. <b>Hold shift</b> and click restart. After restarting, click "troubleshoot" and "UEFI Firmware settings", then click "restart". After restarting, it should bring you to your computer's BIOS settings. If your BIOS are locked, pray and go straight to the next step. </p>
<p>In your computer's BIOS settings, make sure "usb boot" is turned on. This will allow you to boot from your usb.</p>
<h2>Obtaining your usb drive/external SSD</h2>
<p>If you are trying to only use your external drive as a backup for your PC, feel free to choose any large sized drive. <b>However</b>, if you are trying to run a OS and even game on your external drive, make sure to pay much attention to which drive you decide to purchase. If you are new to storage systems, the most important thing to look out for is your SSD's <u>read speed</u>. This will determine how smooth your OS runs and how smooth your gameplay will be. Make sure to get at least a 128 gb drive if you want to use it long term. To get a good drive, look for those with read speeds over 400 mb/s, and additionally a high write speed. Some reccomendations are listed below, buy based off avalability and price.</p>
<ul>
  <li>PNY elite pro v3 (usb drive)</li>
  <li>Kingston Datatraveler Max (usb drive)</li>
  <li>Transcend ESC310 (external SSD)</li>
  <li>Sandisk exterme PRO (usb drive)</li>
</ul>
<p>If interested, check https://ssd-tester.sg/ for detailed information on SSDs and USB drives.</p>
<p><u><b>DO NOT SLACK ON YOUR DRIVE IF YOU WANT TO GAME ON IT</b></u></p>

<h2>Preparing your USB drive</h2>
<p>On a windows device, download Ubuntu or any OS from the official website. Will take a while as most operating systems are quite big. At the same time, download and launch rufus from the official website https://rufus.ie/en/. Once both downloads have been completed and rufus has been launched, plug in your drive to the PC. In Rufus, select the ISO (file) and select the drive you want to copy it to. If you wish to store your information about your live sessions on your drive, enable persistance storage. It is suggested to keep persistence storage lower (around 70-80% of drive storage space). Partition scheme: GPT Target system, UEFI (nonCSM) File system: FAT32 
After all this is done, start the transfer and wait a while until the "ready" button turns green, then safely eject your drive.</p>
<p>For those of you who are looking to create a backup drive, your journey ends here. You have successfully created a bootable drive.</p>

<h2>Setting up your drive OS</h2>
<p>Now its time to see if your drive boots up. Plug your drive into your target device and restart your devie. Find your computer's boot menu key online. Boot menu keys vary depending on your device but they usually are: F12, F11, Esc and Del. Once your device is restarting, spam your boot menu key. You should see a boot menu pop up and 2 options, your native SSD and your USB. Click on your usb. If you have installed a linux system on the usb (preferably) navigate to the option that says try [OS] <b> WHATEVER YOU DO, DO NOT INSTALL THE OS, ONLY TRY.</b> Installing the os would mean wiping your device's entire drive and installing another OS, which is REALLY REALLY bad. If you see anything telling you to "wipe disk and install OS", click out of it <b>IMMEDIATELY</b>. </p>
<p>If you had done all these steps correctly, you should now have your own bootable external disk! All you have to do now is maybe connect to wifi and enjoy unrestricted, unmonitorable access on any device. </p>
<h2> SAFETY PRECAUTIONS, PRACTICE EVERYTIME</h2>
<ul>
  <li>eject drive properly. if you pull out your drive while OS is still on, it will crash. If this happens to you, hold your power button for 10 seconds to force shutdown and reboot normally. Check drive for any signs of corrupted data.</li>
  <li>If you are trying to use this to bypass set restrictions on your device, it is probably against your school's rules. It is STRONGLY suggested not to bring the drive to school or work and use at home for personal use.</li>
</ul>
