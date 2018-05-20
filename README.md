# ITEarlyWarning Instructons
1. Download and Install Active Perl 5.24.3 from https://www.activestate.com/activeperl/downloads   
   - Choose Typical Install option
  
2. Download ITEarlyWarning.zip from https://github.com/abangalore/ITEarlyWarning and save it on local computer</LI>

3. Unzip and Extract ITEarlyWarning.zip under C:\

4. Make sure all of the files are under C:\ITEarlyWarning dirctory

5. Open notepad as Administrator
   - To open any program as Administrator in windows right click on the application and choose the option to "Run as Administrator"

6. Open windows.conf unser C:\ITEarlyWarning in notepad

7. Add directories to be monitored at the end of the file
    e.g C:\Desigo all - This will scan all directories and sub directories associated with the Desigo server
    
8. Save file

9. Open a command prompt window as Administrator
   - Goto start menu, type Cmd, Right click on cmd application and choose "Run as Administrator"
   
10. In the Cmd prompt window type cd C:\ITEarlyWarning

11. Once in C:\ITEarlyWarning  type ITEarlyEarning  (This is a .bat file)

12. This kicks of a batch file that will initialize and cotinously monitor the directories specified in the windows.conf directory. Every  5 minutes a file be stored with any possible changes in the C:\ITEarlyWarning\archive directory. 

13. Open the archive files using notepad.

14. The retention policy in terms on number of days that the archive files will be stored is configurable in the windows.conf directory

15. To kill ITEarlyyWarning, close the command prompt window running ITEarlyWarning.bat


