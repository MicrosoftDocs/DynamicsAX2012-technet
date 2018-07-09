---
title: (NOR) Set up the file types and parameters to archive files
TOCTitle: (NOR) Set up the file types and parameters to archive files
ms:assetid: c3467400-be6b-480a-8076-904b2c9cc300
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213638(v=AX.60)
ms:contentKeyID: 36059287
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (NOR) Set up the file types and parameters to archive files [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can archive a copy of the bank files that are received during the electronic banking process to a database. When you have to run the electronic banking process another time, you can use the archived files that are stored in the database.

The analyzing process decodes the format, and the information in the file is displayed with leading titles and positions. The bank files that are archived in the database are in a readable format so that you can analyze and review them before they are sent to the bank. You can analyze how the file is structured, the sequence of various fields, and count positions.

1.  Click **System administration** \> **Setup** \> **File archiving** \> **File types**.

2.  Create a new file type.

3.  Enter the extension of the file type to archive to the database in the **File type** field. The extension must be followed by a period.
    

    > [!NOTE]
    > <P>Do not leave any space between the period and the file-name extension.</P>



4.  In the **Name** field, enter a description for the file type.

5.  Enter an alternative file type with which to open the current file type in the **Open file type** field.

6.  Close the form to save your changes.

7.  Click **System administration** \> **Setup** \> **File archiving** \> **File archiving parameters**.

8.  Enter the number of the file to be archived next in the **Next file archive number** field.

9.  Select the **Automatic file type** check box to use a default file type to open an archived file when a file type is not defined.

10. Select the default file type to use to open an archived file in the **Automatic open file type** field.

11. Close the form to save your changes.

## See also

[(NOR) View and analyze archived files](nor-view-and-analyze-archived-files.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

