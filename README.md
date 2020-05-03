# electronExeFile
first electron application. Tip how create exe file of electron
# create first app reference
https://www.electronjs.org/docs/tutorial/first-app
----------------------------------------------------------------------------------------------------------

# creating exe file
1. (a.) for use in npm scripts
    npm install electron-packager --save-dev

   (b.) for use from cli
    npm install electron-packager -g
    
2. npm install --save-dev electron

3. electron-packager .  --platform=win32

creating exe file link -- https://www.christianengvall.se/electron-packager-tutorial/

Error: 
------
Q. rcedit.exe failed with exit code 1. Fatal error: Unable to commit changes

Ans. turn off antivirus
