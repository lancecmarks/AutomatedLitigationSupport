---
sectionid: secure-zip-compress
sectionclass: h2
title: SecureZip Custom Compression and Split
parent-id: secure-zip
number: 4100
---

Reasons for using this process can include but not limited to easily dividing large files that do not have apparent divisions, e.g. Phone Extractions, or archiving large case files onto the minimum number of DVDs.

1. Find SecureZIP either by using the Windows 10 Search Box or alphabetically under All Apps in the Windows Start Menu

    ![windows-start_menu](https://i.imgur.com/IzVlACK.png)

2. In the SecureZIP application, open the File menu and click on Options.

    ![securezip-options](https://i.imgur.com/oafjcqC.png)

3. Expand the Compression entry in the left side navigation area and select Advanced.

    ![securezip-advanced](https://i.imgur.com/kYLAgYY.png)

4. In the field labeled "Split size:" type in the number 3891200.  We have to use this custom number because the McAfee Endpoint Security will add extra data during the burning process.

    ![securezip-bytes](https://i.imgur.com/s2UStmH.png)

5. Click on the Add Files icon on the left side of the "Home" toolbar ribbon.

    ![securezip-add](https://i.imgur.com/Bk2k9j3.png)

6. In the popup window, navigate to files or folders you want to add, highlight and click "OK" button.  Repeat this step for multiple files in different locations.

    ![securezip-select](https://i.imgur.com/oXIvzqq.png)

7. Choose the location to save the ZIP files. Optionally you can change the name if desired. Click on "Save" button.

    ![securezip-file](https://i.imgur.com/YKT28PR.png)

8. An encryption popup window will appear, the passphrase is optional.  If you do not want to enter a passphrase click on the "Skip" button.

    ![securezip-password](https://i.imgur.com/xuLiTIT.png)

9. The program will begin the compression process; depending on the total size of the files and the computer, this step can take an hour or more.  In my testing a 10 GB folder will take about 10 minutes on one of the faster office machines.

10. Upon completion if the original was over 4GB there will be at least two files.  For the 10 GB folder, there are three files. Each piece's filename ends with the .z##, where ## is the two digit number for the piece starting at 01.  The last file will contain the remaining data and have file name ending with .zip.

    ![securezip-end](https://i.imgur.com/PMiXpfN.png)
