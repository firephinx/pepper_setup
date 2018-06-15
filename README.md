# pepper_setup

## Instructions
1. Take Pepper carefully out of the box.
2. Remove the pins from the robot and put them next to the emergency button.
3. Unpress the emergency button.
4. Turn on the robot and follow the setup instructions with wifi and stuff.
5. Copy all of the files in the copy_to_pepper.tar.gz file from: https://drive.google.com/open?id=1l_PrzPfWjI9-6MabdLz7TjgUNyQ5Yocc to the new pepper using `scp -r <folder> nao@ipaddress:~/`
6. Make sure to copy the .bash_profile to pepper and modify the ros master ip address parameter there depending on pepper's ip address.
7. Also make sure to modify the ip addresses in the startros file.
8. Set up the Tablet's wifi by sshing onto Pepper and typing `qicli call ALTabletService._openSettings` which will open the Tablet's wifi settings menu.