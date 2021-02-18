Just a quick note on how to access Cisco UCS server's KVM running old version of firmware.
In older UCS servers HTML5.0 KVM is not an option and the only way to access the KVM is via a GUI login using Adobe Flash, but this is an issue since most browsers (like Chrome) have now disabled Adobe Flash. There are ways around it, but if all you need is to quicky access KVM you can do the following.

1. Make sure you have JAVA Runtime installed.
2. Download the generic JNLP file from the repository.
3. Open the file and replace all instances of IP address 2.2.2.2 with whatever is your CIMC IP Address.
4. Replace the username (I use the default "admin" and I bet most of you are doing the same) and the password in the file (you can use the plain, unencrypted password).
5. You can replace the "description" with whatever you need the KVM console to display during connection.
6. Save the file.
7. Run the file (in Windows just a dobule click will do).
8. Enjoy the KVM connection :)
