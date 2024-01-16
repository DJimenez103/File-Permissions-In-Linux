# File-Permissions-In-Linux
Examine existing permissions on a file system.
<br />
<h2>Description</h2>
The task was to examine existing permissions on the file system. I needed to determine if the permissions match the authorization that should be given. If they did not match, I had to modify the permissions to authorize the appropriate users and remove any unauthorized access. The OS is Linux. In order to to complete our task we must:

<br />
- Check file and directory details
<br />
- Describe the permissions string
<br />
- Change file permissions
<br />
- Change file permissions on a hidden file
<br />
- Change directory permissions
<br />
- Conclusion
<br />
<br />
<br />


<h2>Languages and Utilities Used</h2>

- <b>Linux</b> 


<p align="center">

<br/>
In order to open the file that contains the allow list, the allow list needs to be assigned  to the variable import_file. We now want to read the file contents while storing it in the variable "ip_addresses". Since we opened the import file as "file" we apply this to our ".read" function we then assign this output to the variable ip_address to further build out algorithm.

<br />
<img src="https://imgur.com/ySx9Lnd.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The string then needs to be in a list format in order to view the list and to be able to remove IP addresses that are on the "remove list". After using the read method to read our file, we then print the ip_addresses using the ".split" method to convert the string into a list.

<br/>
<img src="https://imgur.com/6orRGku.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
In order to iterate through the remove list, the remove list must be defined just as the allow list also needed to be defined. We then use a for loop. To start the for loop, we used the loop variable "element" first followed by in remove_list to show which list we are iterating through.

<br />
<img src="https://imgur.com/yTzExzT.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
