# goodUSB-4-Flipper
## Documentation
### Important! These scripts are made for Windows 10 & 11 OS. Will not run on MacOS.
Download and unpack the zip folder or clone to local machine. 
Open up the goodUSB folder inside you will see the following.
**recoverWifiPassword-windo.txt**
**cleanUpDisk-windo.txt**
these files need to be tailored to your circumstances.

**recoverWifiPassword-windo.txt**  You need to add the name of the Wi-Fi you are going to recover from.
Important to note this is not hacking it is just telling the computer to recall information from the last time it was connected to the network. 

**cleanUpDisk-windo.txt** You need to double check to see that the pathing to your Temp folder is correct. to check this, go to your windows run and type in "Temp" hit enter and it will navigate to your temp folder. Copy path and add to the text file says.
" STRING del /s C:\Users\compo\AppData\Local\Temp\*".
Important to note this is not going to delete the Temp folder just the content within. This is temporary data stored from your browsing and automatic downloads from the internet.
Over time this can take up space on your disk.
running this script will also open the Disk Clean Up app on your Windows machine.

## Installation 
To install this onto your Flipper first **plug in your flipper to the computer and open the qFlipper app**.
 
Next navigate to the folder inside the Flipper named "badusb" this is what stores and launches Rubber Ducky scripts.

Now take the goodUSB folder and **add it to your desktop**.

Then drag it from desktop to the badusb folder on your Flipper it will take a second to load onto your Flipper once finished **close qFlipper to run scripts**.

To run scripts, open the bad USB app on your Flipper and you should see a folder called goodUSB inside are your new scripts ready to use.