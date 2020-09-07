# Introduction #

A PowerShell based tool to make VMWare Reports in Excel.
## Changes in V2 ##
V2 has much more increased speed therefore i would recommend using this one.
![VMWareReport-WPF](https://github.com/seyo-IV/VMWareReport/blob/master/images/WPF-VMWareReport.PNG)

# Setup #

## Requiments ##
The ImportExcel module is needed for this script. You can get it here https://www.powershellgallery.com/packages/ImportExcel, or install it directly for the current user with the following command `Install-Module -Name ImportExcel -Scope CurrentUser`. Alternatively the script will ask you if you wish to install it, if you declide the script will stop.

# Usage #
![VMWareReport](https://github.com/seyo-IV/VMWareReport/blob/master/images/VMWareReport.PNG)

The connection area is there for a VIServer connection, you can connect to multiple severs but you have to restart the connect dialog. You can see if you are connected when [Wait...] switches to [Not connected] or [VIServer connected](one server), or [VIServers connected](multiple servers).

The folder is empty at start and is only filed with information as soon as you connect to a VIServer.

The file button determines a File in which the report will be saved.

All you now need to do is press Go and wait for your report to complete.
# Tip #
Open the desired script, then choose raw and follow the steps.
To download only one script and not the whole repo use [wget -O somefile.ps1 -uri https://raw.githubusercontent.com/seyo-IV/VMWareReport/master/WPF-VMWareReport.ps1]

You might also need to cahnge the Script encoding to UTF-8-BOM.
