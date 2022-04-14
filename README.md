#  AutoColor-Minimal-Proton

This repository contains some settings that together with the vivaldifox add-on create a minimalist theme whose color is the color of the website you are visiting. 

# Screenshots

![screenshot1](https://github.com/Neikon/Minimal-VivaldiFox-Theme/blob/master/screenshots/Captura%20de%20pantalla%202022-04-14%20155152.png)
![screenshot2](https://github.com/Neikon/Minimal-VivaldiFox-Theme/blob/master/screenshots/Captura%20de%20pantalla%202022-04-14%20155405.png)
![screenshot3](https://github.com/Neikon/Minimal-VivaldiFox-Theme/blob/master/screenshots/Captura%20de%20pantalla%202022-04-14%20155248.png)
![screenshot4](https://github.com/Neikon/Minimal-VivaldiFox-Theme/blob/master/screenshots/Captura%20de%20pantalla%202022-04-14%20155227.png)
![screenshot5](https://github.com/Neikon/Minimal-VivaldiFox-Theme/blob/master/screenshots/Captura%20de%20pantalla%202022-04-14%20155447.png)


# How to download and install
1. [Click here to download](https://github.com/Neikon/Almost-Dark-Grey-Colorfull-Proton---FirefoxCSS-Themes/releases) or Click in `Releases` on the right side of this page. Or download this repository clicking in green button "Code" and download ZIP. [Direct link to Download Zip](https://github.com/Neikon/AutoColor-Minimal-Proton/archive/refs/heads/master.zip)
2. Open a new tab in firefox and write in url bar `about:support` you should see a list with your firefox data, You only need **"Profile folder"** , you can now click in "Open folder" button o copy the address to your profile folder.
    the address should be similar to following example depend of your system:
    + Linux - `$HOME/.mozilla/firefox/XXXXXXX.default-XXXXXX/`
	+ Windows 10 - `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXX.default-XXX`
	+ macOS - `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX`
3. Go to that folder.
4. if there is no folder called `chrome`. Create it.
5. Extract the contents of the zip file you downloaded in the first step into the folder `chrome`
    + it should look something like this: 
    ```
    chrome/
          |- useschrome.css
          |- useContent.css
          |- image/
    ```
6. Now go to firefox open a new tab and write `about:config` in the url bar
7. A dialog will warn you, but ignore it, just do it press the `I accept the risk!` button.
8. Search this `toolkit.legacyUserProfileCustomizations.stylesheets` and set to **true**.
9. Restart Firefox
10. That's all, after restarting you should be seeing your new topic

# Color line in pinned tab
+ Those tabs are simply in a container and I have adjusted the colors of those containers to match.

# Download Vivaldifox
[VivaldiFox from Mozilla add-ons](https://addons.mozilla.org/es/firefox/addon/vivaldifox/)

Configure Vivaldifox as the images you can find in this repository folder in [Minimal-VivaldiFox-Theme/VivaldiFox config screenshots/](https://github.com/Neikon/Minimal-VivaldiFox-Theme/tree/master/VivaldiFox%20config%20screenshots)
