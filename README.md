# pepper_setup

## Instructions
1. Take Pepper carefully out of the box.
2. Remove the pins from the robot and put them next to the emergency button.
3. Unpress the emergency button.
4. Turn on the robot and follow the setup instructions with wifi and stuff.
5. Copy all of the files in the pepper_binaries.zip file from: https://drive.google.com/open?id=1BF4ewnXfKsD6ldcINYbssuVzEouqdJYJ to the new pepper using `scp -r * nao@<PEPPER_IP>:~/`
6. Make sure to copy the .bash_profile to Pepper using the command `scp -r .bash_profile nao@<PEPPER_IP>:~/`.
7. Set up the Tablet's wifi by sshing onto Pepper and typing `qicli call ALTabletService._openSettings` which will open the Tablet's wifi settings menu.