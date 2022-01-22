# FunWithBash
Different useful tools I use in the terminal environment

## sed
 ```sed 's/;/\n /g'  Place_Holder.txt > Fixed_Place_Holder.txt```
 
 This code:
 1. replaces for all string 's' 
 2. ';' with a new line '\n'
 3. using a global flag '\g' 
 4. from a file called Place_Holder.txt 
 5. pipe it to Fixed_Place_Holder.txt

Good resources on sed
https://likegeeks.com/sed-linux/


## install ubuntu bash on windows without using MS store
https://stackoverflow.com/a/64872285/4656963

from power shell

```
# go into some folder into which you want the file to be downloaded
cd <somefolder>

# download Ubuntu 20.04
Invoke-WebRequest -Uri https://aka.ms/wslubuntu2004 -OutFile Ubuntu.appx -UseBasicParsing

# install downloaded *.appx file
Add-AppxPackage .\Ubuntu.appx

```
