1. Generate password for user you can use any website for that or use linux command "mkpasswd -m sha-512 -s"
2. Unpack iso image to some temp folder
3. Auto boot config located in your unpacked iso ./isolinux/txt.cfg
4. Create folders structure in root directory of the iso ./auto/inst
5. Create empty file ./auto/inst/meta-data (this file should be without extension)
6. Create empty file ./auto/inst/user-data (this file should be without extension)
7. Copy user-data file from this repo or copy content to your local file
8. Edit ./isolinux/txt.cfg to get autinstall
9. Create new iso usind special software, for windows it can be UltraISO or WinISO