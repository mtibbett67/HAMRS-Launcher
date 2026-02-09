This is how to install the files to create an icon and run HAMRS

Install git if it is not already instaled

`sudo apt install git`

Rename and move the AppImage file:

`cp hamrs*.AppImage hamrs.AppImage`

`mv hamrs.AppImage /usr/local/bin/hamrs.AppImage`

Copy .desktop file to create app launcher:

`mv hamrs.desktop ~/.local/share/applications/`

`chmod +x ~/.local/share/applications/hamrs.desktop`

Copy Icon file to the proper place

`sudo cp hamrs.jpeg /usr/share/icons/`

`gtk-update-icon-cache /usr/share/icons/`

