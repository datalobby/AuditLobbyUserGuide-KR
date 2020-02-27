---
description: When you try to upload a file and the web browser is forcibly terminated
---

# \(ENG\)"Web browser is abruptly closed when uploading the file."

## "I want to upload a file, but when I click the Upload button, the Internet window suddenly goes out."

> * This is for Windows computer users
> * This is what happens throughout the Chrome browser

## The web browser is forcibly terminated while uploading a HWP \(2010~2014 version\) file from the Chrome browser.

Please take the following guidance. 

1. Run Window Explorer
2. Enter drive C
3. Enter the Program Files \(x86\) folder
4. Enter the Hnc folder
5. Enter Hwp80 \(or HOffice9\) folder
6. When searching for the window, search for HncShellExt64.dll file in the upper right search box and find it
7. Rename the file to HncShellExt64.dll.old \(Append the old name followed by the word .old.\) 
8. Quit all Chrome Web browsers and reopen them to see if the file upload \(attach\) feature works

> If the problem persists, please contact support@datalobby.co.kr.

