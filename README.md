Generate password for user you can use any website for that or use linux command "mkpasswd -m sha-512 -s"
Unpack iso image to some temp folder
Auto boot config located in your unpacked iso ./isolinux/txt.cfg
Create folders structure in root directory of the iso ./auto/inst
Create empty file ./auto/inst/meta-data (this file should be without extension)
Create empty file ./auto/inst/user-data (this file should be without extension)
Copy user-data file from this repo or copy content to your local file (default password is "test")
Edit ./isolinux/txt.cfg to get autinstall
Create new iso using special software, for windows it can be UltraISO or WinISO