# RprimeSuite
An R package to design 4C primers and oligo FiSH probes and primers

#########################################################
Installing dependencies
This README will guide you through how to install necessary (Blast and Primer3) and optional (ApE) dependencies of Rprime


#########################################################
Install primer3 on a MAC and Linux
#########################################################

1) Extract the zipped distribution (either by command line or right click, extract (Ubuntu) or double click (MAC)
2) Go to terminal and move to the current directory

$ cd /your/path/to/Rprime/dependencies/primer3-2.3.7/src

3) type

$make all
$make test

This will take a while. Check whether there are no "failed" messages.

********
This manual was taken from: http://primer3.sourceforge.net/primer3_manual.htm#installLinux

#########################################################
Install Blast on a MAC
#########################################################

1) Double click on the disk image ncbi-blast-2.6.0+.dmg
The OSX will guide you through the installation process


#########################################################
Install ApE on a MAC
#########################################################

1) Double click on the disk image ApE_OSX_modern_current.dmg
The OSX will guide you through the installation process


#########################################################
Install ApE on Linux
#########################################################

1) Go to http://equi4.com/tclkit/download.html and download the most recent version of Tclkit for Linux that corresponds to your CPU architecture (if you have an Intel, it will probably be "x86 (32b)").

2) Open the downloaded archive and drag-and-drop the file inside onto your desktop. Rename the file to "tclkit".

3) Open a terminal window (for Ubuntu, this is under the menu "Applications" --> "Accessories" --> "Terminal".

4) By default, a new terminal window should open to your user directory. Confirm by typing "ls" and hit ENTER. You should see a list of your folders such as Documents, Downloads, Desktop, etc.

5) Once you have confirmed you are in your user directory, type "cd Desktop" (this is caps-sensitive) and hit ENTER.

6) Type "ls" and hit ENTER to list the files on your Desktop. You should see "tclkit" among them. Type "sudo mv tclkit /usr/bin/" to move the tclkit file to where it needs to go. You will be prompted for your root password, which you should have established when you first installed Ubuntu.

7) Now go to where you've moved tclkit by typing "cd /usr/bin/" and hit ENTER. Type "sudo chmod +x tclkit" and hit ENTER, which will allow tclkit to be run as an executable command. You will again be prompted for your password.

8) Now, go to the ApE website and download the ApE Linux archive. The archive contains both the ApE Linux folder and the Mac OSX folder which you can ignore. Drag and drop the "ApE Linux" folder into a location of your choice. I recommend something easy to find, like on your Desktop or Documents folder. Notice that inside the ApE Linux folder is a file called "AppMain.tcl"; however, you cannot just double click this. Normally you would open it via terminal command. However, you can create a menu shortcut that will make things easier.

9) To create the shortcut, right click the top menu bar and click "Edit Menus". Under the "Science" category (or another if you choose), click "New Item". A new window will come up. Under "Type", select "Application in Terminal". Under "Name", write whatever name you wish. Under "Command", click browse and find where you put AppMain.tcl. Once you select that file, it should display the location of AppMain.tcl, for example "/home/user/Desktop/ApE%Linux/AppMain.tcl" Now, in FRONT of that location type "tclkit ", so that the entire location becomes "tclkit /home/user/Desktop/ApE/AppMain.tcl". Note that there is a single space between "tclkit" and "/home".

10) Click "OK" and that should be it! Go to the new menu item you created under "Applications" and click it. A terminal window should pop up, then ApE should appear! Leave the terminal window open until you are done with ApE; if you close the terminal window it will also close ApE.

********
This manual was taken from: https://ape-a-plasmid-editor.wikispaces.com/share/view/32935290
