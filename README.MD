Just a quick note on how to access the Cisco UCS server's KVM running the old version of the firmware.
In older UCS servers HTML5.0 KVM is not an option and the only way to access the KVM is via a GUI login using Adobe Flash, but this is an issue since most browsers (like Chrome) have now disabled Adobe Flash. There are ways around it, but if all you need is to quickly access KVM you can do the following.

IMPORTANT! Just in case you are not familiar wiht GitHub: do NOT right click and download just the jnlp file, the way GitHub work you will end up with html formatted file. You want to select "Code" -> "Download ZIP" and upack the file after downloading.

1. Make sure you have JAVA Runtime installed.
2. Download the git repository and unpack the JNLP file from the repository.
3. Open the file and replace all instances of IP address 2.2.2.2 with whatever is your CIMC IP Address.
4. Replace the username (I use the default "admin" and I bet most of you are doing the same) in line 14
5. Replace the password (you can use the plain, unencrypted password) in line 15.
6. You can replace the "description" with whatever you need the KVM console to display during connection (line 10)
7. Save the file.
8. Run the file (in Windows just a double click will do).
9. Enjoy the KVM connection :)

Here is a video of how to do it.
https://youtu.be/BF9MgFV6JAQ

If you found this helpful and you like the work I do, why not buy me a coffe, thanks ! :)

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R52KGCD)

