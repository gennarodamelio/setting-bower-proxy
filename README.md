# setting-bower-proxy
setting-bower-proxy

{

    "proxy":"http://<user>:<password>@<host>:<port>",
    "https-proxy":"http://<user>:<password>@<host>:<port>"

}


Adding Git to Windows 7/8/8.1 Path

Note: You must have msysgit installed on your machine. Also, the path to my Git installation is "C:\Program Files (x86)\Git". Yours might be different. Please check where yours is before continuing.

Open the Windows Environment Variables/Path Window.

Right-click on My Computer -> Properties
Click Advanced System Settings link from the left side column
Click Environment Variables in the bottom of the window
Then under System Variables look for the path variable and click edit
Add the pwd to Git's binary and cmd at the end of the string like this:
;%PROGRAMFILES(x86)%\Git\bin;%PROGRAMFILES(x86)%\Git\cmd
Now test it out in PowerShell. Type git and see if it recognizes the command.

This is image showing you how to do so!
