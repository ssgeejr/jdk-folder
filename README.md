# jdk-folder
For some genius reason, the almighty Oracle team has decided to no longer provide a compressed (portable) version of  the JDK.  **So dumb!**

This was so very painful for me to write as my batch skills are awful! Luckily, I was able to knock it out with a lot of googling and some good examples.

This script will move the JDK file you provide to c:\tmp
Unzip it, unzip it again, create the jars from the pack files
rename the folder
if \-m was provided move the folder %PROGRAMFILES%
if \-m \<dest\> was provided, move the folder to the new location 
