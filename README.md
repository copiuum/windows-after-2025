
# Guide on how to stay on windows 10/11 after windows 10 goes End Of Life in 2025!

**Step 1**

- Go to https://massgrave.dev/genuine-installation-media
- Find "Windows 10 / 11 Iot Enterprise LTSC"
- You can go with Windows 10 21H2 Iot Enterprise LTSC or Windows 11 24H2 Iot Enterprise LTSC, desktop experience is equally the same as on Home or Pro editions of Windows, only change is licensing and update channels!
- Download

**Step 2**
- Go to https://www.ventoy.net/en/download.html
- Download "ventoy...windows.zip" file, locate the downloaded file and then extract it.
- Prepare USB thumb drive or SATA SSD, any drive works for this method!
- Open **Ventoy2Disk.exe**, click on **Option** -> **Show All Devices**, then select **Device** (your prepared drive).
- Press **Install**
- _(please keep in mind which brand and how many GB your drive has!!!)_

**Step 3**
- Go to File Explorer and verify that Ventoy has been installed to your prepared drive.
- Go to the place where you downloaded your Windows ISO and copy paste it (or you can drag and drop) the downloaded into the Ventoy partition.
- _(keep in mind you can use Ventoy to store all your needed files for backup purposes, it can be anything)_

**Step 4**
- Reboot to the Boot Menu and select the drive with Ventoy label, proceed to boot into it.
- You will see text with Ventoy and ISO files, select your Windows ISO and proceed, it will boot into Windows Installation.
- Do the regular Windows installation procedure like in usual.
- _(if you are not sure which drive to install on, press **Shift + F10** and write **diskpart**, then **list disk** then **sel disk number** then **detail disk**, you wll see information about your selected drive)_
- Proceed and select which drive you want to install Windows on.

**Additional things to mention**
Now, you will have unbothered Windows experience for long time, you will receive cumulative & security updates for long time!
> If you want to get Microsoft Store, open powershell or press win + r and then type **wsreset -i**, it will reinstall Microsoft Store.
> To activate Windows, open powershell and type `irm https://get.activated.win | iex`, select HWID, it will activate Windows.
> If you don't want drivers installed directly from Windows Update, open powershell and type `irm christitus.com/win | iex` navigate to "Updates" and select "Security Settings", you can still install Windows Updates manually by using [Windows Update Catalog](https://www.catalog.update.microsoft.com/Home.aspx) and following up Windows Update History!

## Thanks for following up this guide! Help others by contributing to FOSS and repair! https://endof10.org/
