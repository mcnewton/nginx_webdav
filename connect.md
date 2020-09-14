Connection instructions for different WebDav clients
====================================================

Windows
-------

1.  Open a File Explorer window (as in \"my computer\", not
    the web browser)
2.  In the list on the left side, right click \"Network\"
3.  Click \"Map network drive\...\"
4.  Window pops up, in the \"folder\" box type:

        https://www.example.org/

5.  Un-tick \"reconnect at sign-in\" (unless you want it to connect
    every time\...)
6.  Click \"Finish\"
7.  Enter username/password
8.  Click \"OK\"


Linux - GNOME
-------------

1.  Open a new \"files\" window to see your home folder
2.  In left tool bar click \"Other Locations\"
3.  At the bottom it says \"Connect to Server\" - enter:

        davs://www.example.org/

4.  Click \"Connect\"
5.  Enter username/password
6.  Click \"OK\"


MacOS
-----

Instructions from
[Apple](https://support.apple.com/en-gb/guide/mac-help/mchlp1546/mac)

1.  In Finder, choose Go \> Connect to Server
2.  Enter the server address:

        https://www.example.org/

3.  Click \"Connect\"
4.  Enter username/password
5.  Click \"OK\"


Android phones
--------------

There doesn\'t seem to be built-in support, but the free version of
\"Smart File Manager\" ([link
here](https://play.google.com/store/apps/details?id=com.cvinfo.filemanager&hl=en_GB))
has a WebDAV client.

1.  Click the hamburger symbol (three lines) to get the menu
2.  Choose \"Add Cloud Storage\"
3.  Choose \"WebDAV\", then \"Next\"
4.  Transport Protocol, choose \"HTTPS\", then Next
5.  Connection information:
    -   Host Name: www.example.org
    -   Path: /
    -   Port: 443
    -   Name: (anything you like to call this connection)

    then \"Next\".
6.  Log in: username and password, then \"Next\"
7.  \"Connect\" - hit \"Log in\", then \"You are logged in as ...\"
    hit \"Done\", then \"Done\" again.

To reconnect, choose the name you set above on the hamburger menu.

iPhones
-------

There doesn\'t seem to be full built-in support, but this app [WebDAV
Navigator](https://apps.apple.com/gb/app/webdav-navigator/id382551345)
works well.

1.  Open app and click the \"+\" in the top right corner.
2.  Enter the connection information:
    -   Name: (anything you like to call this connection)
    -   Server URL: https://www.example.org/
    -   Username and password.
3.  Tap \"save\" in the top right corner.

### iPhone example: uploading a video

1.  Tap on the connection that you just created
2.  Navigate to the correct location, if applicable
3.  Tap on the photo icon (mountains) at the bottom of the screen, find
    the video to upload
4.  Tap the video, then \"choose\". A blue bar will appear with
    \"compressing video\"
5.  When it has finished it will ask for the filename to save as
6.  Tap \"upload\" and wait, it should appear in the folder you
    selected.
