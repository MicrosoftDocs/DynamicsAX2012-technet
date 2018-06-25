---
title: 'How to: Import Application Objects by Using the AOT'
TOCTitle: 'How to: Import Application Objects by Using the AOT'
ms:assetid: aca27fe1-7e3a-43b7-b0a3-7db2c9bf71d4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa854197(v=AX.60)
ms:contentKeyID: 35249712
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# How to: Import Application Objects by Using the AOT [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2012, you can import X++ application objects that are contained in .xpo files previously created with the **Export** menu command. For more information, see [How to: Export Application Objects by Using the AOT](how-to-export-application-objects-by-using-the-aot.md). Only users who have developer rights can import code. This topic describes how to import one or more application objects, without business data, into the application.

For more information about how to import and export business data, see [Use DAT and DEF files to export and import data](use-dat-and-def-files-to-export-and-import-data.md) and [Export options (class form)](https://technet.microsoft.com/en-us/library/aa571790\(v=ax.60\)).

### To import application objects

1.  On the **Command** menu, click **Import**. The **Import** window opens.

2.  Click **Browse** to find the location and name for the import file.

3.  Set options as needed in the **Import** and **Options** field groups. For more information, see [Import Form](https://technet.microsoft.com/en-us/library/aa575673\(v=ax.60\)).

4.  If you do not want to import all application objects in the .xpo file, click **Show Details**, and then clear the check box for application objects that should not be imported.
    

    > [!NOTE]
    > <P>Application objects can only be imported into the same layer opened by the client. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa673975(v=ax.60)">How to: Set the Layer</A>.</P>



5.  Click **OK** to import the selected application objects.

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

