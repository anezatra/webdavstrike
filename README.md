# WebdavStrike Exploitation Toolkit 🎲
![banner image](https://github.com/anezatra/webdavstrike/blob/main/banner.jpg)
## What is a WebdavStrike?
**WebdavStrike is a tool that allows you to index or reverse shell sites using WebDAV vulnerabilities. WebDAV protocol is a standard for file management over HTTP. WebdavStrike is used to infect sites located on WebDAV, specifically through the Interrupt Request (PUT) Method. This method is used to perform operations such as uploading files or modifying existing files on vulnerable sites. WebdavStrike is available to users to detect sites with such vulnerabilities and perform various actions on these sites.**
## What is a webdav?
**WebDAV, short for Web Distributed Authoring and Versioning, is a communication protocol used for file management. Built on top of HTTP (Hypertext Transfer Protocol), it is commonly utilized for file sharing, collaboration, and management. WebDAV extends standard HTTP methods with additional methods and features for file system operations, facilitating the management and updating of files on remote servers. It finds frequent use, particularly in document management systems and cloud storage services.**
## Use dorks to detect Webdav vulnerable sites 🕵🏽
```
------------------
inurl:.co.id/*.asp
inurl:.ah.cn/*.asp
inurl:.bj.cn/*.asp
------------------
inurl:"g2_view=webdav.WebDavMount"
inurl:"remote.php/webdav" -site:owncloud.org
intitle:"Directory Listing For /" + inurl:webdav tomcat
------------------
```
## How to download 💡
**You can download Webdavstrike directly by saying** <br/><br/>
` pip install -r requirements.txt `
## or <br/>
` python -m pip install -r requirements.txt ` <br/>
## Required python version 📌
` python 3.x `
## About 🚀
**My gmail adress: anezatra@gmail.com**




