this script creates a the start menu directory in the default user, then copies a start menu configuration to that directory. this will set the default start menu for all new users to that config, including domain users.

you also don't have to wait until apps are installed to run the script. for example, you can run the script then install chrome, and it will pop up in the start menu after the install is finished.

will set the default start menu to the following:

<img width="200" alt="image" src="https://user-images.githubusercontent.com/121190800/208971876-8371be47-1aaf-40da-bed8-9087ff76b7f4.png">

if you would like to change the items, modify your own start menu to be what you want, then copy %localappdata%\Packages\Microsoft.Windows.StartMenuExperienceHost_cw5n1h2txyewy\LocalState\start.bin to the location of the .bat file
