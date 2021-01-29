# KMSAuto-Net-2015-v1.3.8-Portable

                        KMSAuto Net 2015 Portable от Ratiborus,
                                       MSFree Inc.

       		                    System requirements: 
                          —————————————————————————————————
VL editions: Windows Vista, 7, Windows 8, 8.1, 10, Server 2008, 2008 R2, 2012,
2012 R2, Office 2010/2013/2016.

       		                         Description:
                          —————————————————————————————————
KMSAuto Net - automatic KMS-activator for operating systems 
Windows VL editions: Vista, 7, 8, 8.1, 10, Server 2008, 2008 R2, 2012,
2012 R2 also Office 2010, 2013, 2016.

Additionally, the program activates:
	Windows 8.1 Single Language;
	Windows 8.1 Core;
	Windows 8.1 Core N;
	Windows 8.1 Pro WMC;
	Windows Embedded 8.1 Industry Pro;
	Windows Server 2012 R2 Standard;
	Windows Server 2012 R2 Datacenter.
It is based on KMS Server Service from mikmik38 (MDL).

  
       		                   Using the program:
                          —————————————————————————————————
Run KMSAuto Net.exe as administrator and use the interface. If you need additional 
program features, enter into Professional Mode. The On/Off Professional Mode button
is placed in the "About" Tab.
The easiest way to use the program is to pick the automatic mode. All you need to do is
click on the button if you want to activate and agree to create a scheduled task for
reactivation by pressing the button.

Tip: First you need to activate Windows and Office in manual mode, and only then, 
when you are sure that the activation takes place, you can create a scheduled task for 
reactivation products every 25 days.
If the system does not want to be activated in Professional Mode go to "Utilites" and 
manually set GVLK key for the proper Windows Edition, and then try to activate again.

			                    Additional Information:
                          —————————————————————————————————

To activate Windows 8.1 the TAP network adapter must be installed directly
and use the IP address 10.3.0.2-254 or use a special driver. All these features
are built into the program.
To activate via LAN, the TAP interface can't be used to install and
activate through an address of a computer in the network.
If you reconfigure the program and it stops operating correctly - check the checkbox 
"Reset the program." All settings will be set by default.


		            Additional parameters of the program (switches):
                          —————————————————————————————————
/win=act	- Run this program in quiet mode, activate Windows
		  and exit the program.
/off=act	- Run this program in quiet mode, activate Office
		  and exit the program.
/log=yes	- Run this program in quiet mode, create a file ActStatus.log
		  and exit the program.
/kmsset=yes	- Run this program in quiet mode, install KMS-Service and exit the program.
 	          It's only for KMS-Service, without TAP, WinDivert, Hook.
/kmsdel=yes	- Run this program in quiet mode, remove KMS-Service and exit the program.
/key=yes	- Run this program in quiet mode, install the Windows key and exit
  	          the program.
/task=yes	- Run this program in quiet mode, create a scheduled task for Windows and
   	          Office Activation every 25 days and quit.
/taskrun=yes	- Run this program in quiet mode, run the task scheduler for Windows and 
   	          Office Activation and exit the program.
/convert=	- Run this program in quiet mode, preparation to perform the conversion 
   	          of Windows version and exit the program.
			  Possible key values: win81pro, win81ent, win81, win81sl, win81wmc
			  After using this function, you need to restart your computer.
/sound=yes	- Enable sounds.
/sound=no	- Disable sounds.
		  
                          —————————————————————————————————
The activation will be done with the settings defined in the tab KMS-Service.


                          —————————————————————————————————
When you transfer the program to another computer, you need to reset the Auto Mode.
Activation would still be in automatic, but the mode may not be optimal
for your new computer.
To reset the auto mode to the initial state you need to switch to any other mode,
and then again select auto. Everything is now reset to the initial state.

	              About how to activate the built-in program				
                          —————————————————————————————————
The program can perform the activation with built-in KMS server Emulator in several
different ways. Why are there several of them?: the standard way to connect to the activation 
server through the local host (127.0.0.2-254) was blocked in Windows 8.1. 
All methods are intended for activation of something to cheat the system, do so
that it "thinks" that the KMS server is not on your computer, but somewhere far away in the 
network.
				  
						  
	           Overview about the operating modes of the program:
                          —————————————————————————————————
Auto	 - the program tries to automatically find the way that best suits your activation
           system. Attempts are being made to activate the system or Office for all admissible
           ways your system has, and the one picked by the program it will be held to remember.
           To reset to the initial mode, you can switch to any other mode and then select Auto. 
	       This mode is selected by default.	
Hook     - method based on the substitution of the original file system changed on a special way.
           The new version of the method works without physically replacing the file.
WinDivert- in the system a driver is installed at the time of activation and it keeps running 
           to emulate a remote connection to the KMS server.	  
NoAuto   - In this mode, there is no automation, there is need to set the way it will work.
           Is intended for people who know better than me what, how and when to do and whether 
           you want to do it or not. :)	
TAP      - the system is a virtual device. TAP activation is done through this virtual device.
           The program includes two drivers for the TAP adapter. If you already installed one of
           the drivers, the program will used the other driver to activate, resulting in your 
           current adapter left intact.		   
* Mode names on the System tab - clicking these links on which you can change some settings.

				KMSSS.exe Options
                          —————————————————————————————————
Command Line Parameters:
  -Port <Port Value> - KMS Port. Range from 1 to 65535
         -PWin <PID> - Windows PID
         -PO14 <PID> - Office 2010 PID
         -PO15 <PID> - Office 2013 PID
      -AI <Interval> - Activation Interval. Range from 15 to 43200 minutes
      -RI <Interval> - Renewal Interval. Range from 15 to 43200 minutes
   KillProcessOnPort - Force to open the KMS Port if this is present.
                -Log - Log file Enabled.
		 -IP - Show IP address Clients Computers.         
        -Hwid <HWID> - Machine Hardware Hash.
		   
                          —————————————————————————————————
The program requires .NET Framework 4.5
To run properly, it is necessary to add the file KMSSS.exe in the exclusion of your Anti-Virus!.
Or disable Anti-Virus at the time of activation.

Sometimes KMS-Service is not installed properly, it may be for different reasons.
You need to perform 2-3 times "Removing KMS-Service" and restart your computer.
When working with the program it makes sense to check on the option "Save 
settings in the program folder". In this case, the configuration file will be stored 
in the program folder, and not in the C:\Users\username\AppData\Local\MSfree Inc.

                          —————————————————————————————————
KMS Log Analyzer.xlsm previous versions are incompatible with KMS Server Service v1.1.7
In order to save their old records should be transferred to the new
KMS Log Analyzer using copy-paste function.

			  "I wasn't able to activate!!!"
                          —————————————————————————————————
Perhaps you have a non VL product, not intended for activation of KMS-Service, for instance 
Windows 7 Ultimate can't support KMS activation, or your antivirus blocks the activation.
If an antivirus is the culprit you can do the following: in the "System" tab click on the 
blue label "KMS-Service" and in the window that appears remove the check mark. Then add the 
folder to exceptions in your antivirus program.
                                                                                                                                                                                                          


                          —————————————————————————————————
I want to say thank you mikmik38, without his work this program would be just impossible. 
To Hotbird64, for his KMS Client, Evgeny972 and guys from forum.ru-board.com for making
possible assistance and testing of multiple versions of the program.
                                                                 
										Ratiborus

																 
Changelog:
v1.3.8
 -Fixed: mapping display buttons when the font is enlarged to 125%.
 -Added: Display the license expiration date (180 days 0 hours 0 minutes).
 -Added in "Other utilities" restore system files from the disk with your 
  version/edition of Windows.


v1.3.7
 -Fixed: Encoding readme_ru.txt.
 -Added readme.txt in the Bulgarian language.
 -Utility to save activation MSActBackUp v1.0.8.


v1.3.6
 -Updated program ProduKey v1.70 to v1.80.
 -Fixed: Setting keys for Office 2016.
 -Fixed: The task in the scheduler runs every 10 days.


v1.3.5
 -Updated ProduKey v1.66 to v1.70.
 -New TAP driver to support Windows 10. A random IP address is used and when the activation fails check box is cleared.
 -Re-compiled KMS Service. So antivirus software will not detect it as threat/false positive.
 -Included utility MSActBackUp.
 -Added Keys for Windows 10 and Office 2016.
 -Conversion from Office 2016 RETAIL to VL.
 -If Office is not installed, the button "Activate Office" is disabled.
 -In the "About" tab you can find a link to a page with my programs.
 -Added program for Windows 10 "Show or hide updates"

v1.3.4
 -Changes in program for compatibility with antivirus software.

v1.3.3
 -The program, when attempting activation of Office 2013 RETAIL converts the license channel 
  of OfficeProPlus, VisioPro, ProjectPro on Windows 7, 8, 8.1, 10 to KMS client.

v1.3.2
 -Small changes to the interface, added compatibility with Windows Technical Preview.
 -Now the program has French interface, thanks to coleo.
 
v1.3.1.b4
 -Added function that runs the script from heos(ru-board.com).
  This script searches for installed but outdated update Office 2010/2013 
  and makes it possible to remove them.

v1.3.1.b3
 -Added function for switching language interface.
 
v1.3.1.b2
 -Fixed bug when working with command line parameters creating a scheduled task.

v1.3.1.b1
 -Added support to activate Windows Technical Preview, Windows 10.

v1.3.0
 -Added support to activate OEM editions: "Windows 8.1 Single Language with Bing",
  "Windows 8.1 with Bing" and   "Windows 8.1 Pro for Education"
 
v1.2.8
 -ProduKey program updated from v1.65 to v1.66.
 -Replaced SppPatcher in the Hook SECO Injector method.
 -Eliminated an error that displays "Activation interval" in ES, VI, UA transfers.
 
v1.2.7
 -To view the log in the activation program now KMS Log Analizer.xlsm is integrated.
 -The computer should have an application installed to view .xlms files (MS Excel).
 -Work on adapting the program to the new format of the log file performed by Bort_Nick,
  forum.ru-board.com.
 -New KMS Server Service (KMSSS.exe) v1.1.7.
 -Expanded list of systems for converting edition.
 
v1.2.6.1
 -Changed the way "Program Information" button works on the "About" tab.
 -Fixed the nonworking "Get ePID and Hwid KMS-Service" button.
 
v1.2.6
 -Fixed a problem with key installation after executing the command "slmgr.vbs /upk".
 -To avoid detection from antivirus modules, driver files are password protected. 
  Moreover, is imperative to add to exclusions the following folders:
  %SYSTEMDRIVE%\ProgramData\KMSAuto\*.* 
  %SYSTEMDRIVE%\ProgramData\KMSAutoS\*.* 
  %TEMP%\KMSAuto\*.*
  %TEMP%\PDK\*.*
  
v1.2.5
 -When activation fails a message is displayed and an attempt is made to set 
  a GVLK forcibly.
 -Added option to disable Task Scheduler which monitor user actions.
 
v1.2.4.1
 -Fixed bug when working with command line parameters creating a scheduled task.

v1.2.4
 -Activating in Auto mode starts using Windivert method.
 -In the TAP method the TAP adapter is not re-installed.
 
v1.2.3
 -Activation functions are optimized for Windows and Office.
 -Fixed minor bugs.
 -Changed the "Utilities" tab. Added "KMS Client by Hotbird64"
 -New KMSSS.exe supporting installation Hwid KMS-Server.

v1.2.2
 -Fixed date and time displayed in hexadecimal format in the log file. 
 
v1.2.1
 -Added the utility from ShowHideControls miXOnIN. To convert Systems Editions. 
 -In Professional Mode, Advanced tab, the button "Convert Office RETAIL to VL". 
  Runs on Windows 8-8.1, doesn't work on Windows 7!.
 -New KMSSS.exe supporting installation Hwid KMS-Server.
  
v1.2.0
 -Changed the "Settings" tab.
 
v1.1.9.b1
 -Updated program for ProduKey v1.62 v1.65
 -Added the choice of Activation intervals of 10 and 20 days.
 -Installing GVLK Key at "Utilities" tab, works through slmgr.vbs.
 -Changed setting keys function for "Unsupported Product" (so reports WMI OS).
 -Added the program KMS Log Analyzer, for easy viewing and conservation of
  information of the log file from KMS-Service. The computer must have installed 
  an application for working with files .xlsm (MS Excel). Not ready yet!

v1.1.7 ÷ v1.1.8
 -Small changes in the program interface. Added a link to a video.
 -In "Auto" mode the program starts searching for a solution with the correct IP address.
 -Fixed a rarely occurring bug related to the inability to delete files "Injector by deagles".
  Program could hang with the message "Installation Hook, Injector by deagles"
 -Activation functions are optimized for Windows and Office.
 -On the Utilities tab a button was added "Resetting the system is not valid."
  Carefully read the message that appears when you click on this button!

v1.1.6
 -Added the ability to reset the program to default values.
 -New containers for modules. Unpacking modules and drivers is faster.
 -Task scheduler creates tasks on behalf of the Administrator.
 -Deleting addresses from KMS Server is working correctly.
 -Fixed some minor bugs.
  *** Happy New Year 2014 ! ***

v1.1.4
 -Program settings can be saved in a folder containing the program.
 -All modules of the program can work from ProgramData or the folder containing the program.
 -Fixed minor bugs.

v1.1.2.b8
 -ProduKey program is integrated into the executable file.

v1.1.2.b7
 -Fixed bug accessing the folder.

v1.1.2.b6
 -Fixed a bug in the Scheduler.

v1.1.2.b4
 -In Auto mode, you can disable any method of activation.
 
v1.1.2.b3 
 -Hook method uses a modified SECO Injector. Works at Activation and Renewal intervals 
  and set own ePID.

 v1.1.2b2
 -Option to connect to the KMS server where Hook mode works without replacing files.
 -Added option in the task scheduler to create the task in the ProgramData\KMSAutoS path.

v1.1.1
 -Added activation method with temporary substitution of 8.1 files.

v1.0.9.1
 -Eliminating annoying bug with non-removed service TunMirror.

v1.0.9
 -Program requires .NET Framework 4.5 again, as per users request.
 -Dialog to change the product key appears only once per session with the program.
 -When the scheduled task executes, the KMS-Service is no longer removed from the system,
  if it was installed the first time.
 -New added NoAuto option to disable automatic loading KMS-Service during activation.
  Hence, if NoAuto then full NoAuto.
 -In Auto mode when the configuration switch is added, the analysis of the
  system will always begin from the start position, and not from the previously stored.
  This is convenient if the program is run on different computers.
 -Before activating the system editon is defined and if it is 8.1 then the classic way
  of local host activation is excluded.
 -Added a second type of TAP adapter to resolve the conflict with the already established TAP VPN.
 -WinDivert v1.1 has been applied, so not "incidents" result in BSOD on x86 systems.
 -Eliminate errors when in the file path a sign "&" (ampersand) is present.
 
v1.0.8
 -Added a setting to remove the WinDivert driver. To avoid a possible crashing of your
  system in a BSOD, the unconditional removal can be turned on.
  By default, the removal is made after reboot.
 -Added the ability to run the program with switches at the command line.
 
v1.0.8.b5
 -The program combines three ways to connect to the KMS server, first try automatic mode
  setting.

v1.0.7
 -New KMS Server Service (KMSSS.exe). Added function to display the IP 
  address of the client in the log file. More in KMSSS.txt
  
v1.0.6
 -New KMS Server Service (KMSSS.exe). More in KMSSS.txt
 -Cosmetic changes to the interface
 
v1.0.5
 -Log file that includes information about de client OS version.
 -Fixes the problem with the definition of a folder Sysnative.
 
v1.0.4
 -New KMSSS.exe, KMS Server Service.
 -KMS Service Log output in the specified folder.
 -Fixed some minor bugs :)
 
v1.0.3
 -Applied a modified KMS-Service. Allows for the use of each product your own ePID. 
  Including CSVLK from actual key.
 -Changed the installation and removal of TunMirror.
 -Changed the installation and removal of TAP interface.
 -Added support for activation of Core, Embedded Industry, Single Language, etc.

v1.0.2
 -Change the setting of TAP interface.
 -New feature for activation Backup / Restore.
 -Cosmetic changes to the interface.
 -Added the ability to create a task scheduler to activate.

v1.0.1
 -Added GVLK keys to Server R2.
 -Cosmetic changes to the interface.

v1.0.0
 -First release.




