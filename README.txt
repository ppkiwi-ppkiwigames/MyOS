MYOS — OS TEMPLATE

MyOS is a customizable, browser-based desktop template.

HOW APPS WORK
Each app is a folder inside /home/user/Apps. The folder name is the app name, and that folder's index.html is the app's actual entry page.

Example:
Apps/
  Weather/
    index.html
    styles/main.css
    scripts/app.js
    images/logo.png

IMPORT AN APP FOLDER FROM YOUR COMPUTER
1. Open MyOS and launch Files.
2. Click Import app folder.
3. Select the app's folder (the folder that contains index.html).
4. MyOS copies the folder's contents into its virtual Apps folder.
5. The app is registered under the selected folder's name. Launch it from the app launcher.
6. Relative CSS, JavaScript, image, and other asset paths are kept with the app.

IMPORTANT BROWSER LIMITATION
A browser page cannot silently scan folders sitting beside index.html on your computer or inside the extracted ZIP. Use Import app folder to grant access and copy the selected folder into MyOS. Apps created inside MyOS's virtual Files app are also discovered automatically.

CUSTOM CURSORS
Open Settings > Appearance > Custom cursor to choose a cursor style. The selection is saved in browser storage.

NOTE
MyOS is a browser-based desktop simulation/template, not a bootable operating-system installer.
