# FORKED FROM OTK.ahk  https://github.com/clangremlini/OTA.ahk

Download github repo from ahk. No knowledge needed. 

## How to use

I changed the script to run out of the box for dummies like me that need their hand held. 

- Specify the name of the github repository in the OTA.ahk file (`line #3`)
- Specify the name of the file to be loaded from the latest release (`line #4`)
- Specify the name of the file to be saved (`line #5`)
- Including file OTA.ahk (`#Include OTA.ahk`)
- In the main project file, specify the version of the script (`global version = "v1.26.1"`)
- To check for updates, call OTA.checkupd() in your code

## [example project via using this class](https://github.com/clangremlini/aye-ahk-loader)
