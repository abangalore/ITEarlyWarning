# ITEarlyWarning
Download and Install Active Perl 5.24.3 from https://www.activestate.com/activeperl/downloads     
  - Choose Typical Install option
  
Download ITEarlyWarning.zip from https://github.com/abangalore/ITEarlyWarning and save it on local computer

Unzip and Extract ITEarlyWarning.zip under C:\

Make sure all of the files are under C:\ITEarlyWarning dirctory

Open notepad as Administrator
   -- To open any program as Administrator in windows right click on the application and choose the option to "Run as Administrator"

Open windows.conf unser C:\ITEarlyWarning in notepad

Add directories to be monitored at the end of the file
    e.g C:\Desigo all - This will scan all directories and sub directories associated with the Desigo server
    
Save file

Open a command prompt window as Administrator
   - Goto start menu, type Cmd, Right click on cmd application and choose "Run as Administrator"
   
In the Cmd prompt window type cd C:\ITEarlyWarning

Once in C:\ITEarlyWarning  type ITEarlyEarning  (This is a .bat file)

This kicks of a batch file that will initialize and cotinously monitor the directories specified in the windows.conf directory. Every  5 minutes a file be stored with any possible changes in the C:\ITEarlyWarning\archive directory. 

Open the archive files using notepad.

The retnetion policy in terms on number of days that the archive files will be stored is configurable in the windows.conf directory
