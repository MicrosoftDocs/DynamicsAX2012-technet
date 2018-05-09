---
title: (RUS) Set up the periods of formats application directory
TOCTitle: (RUS) Set up the periods of formats application directory
ms:assetid: 5deb01fd-4c55-4c13-b555-332bb5da037e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677542(v=AX.60)
ms:contentKeyID: 49384846
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up the periods of formats application directory 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The tax authority creates a document that defines all versions of tax report formats. You can download and use this document to create the tax reports in the versions that you want. The periods of formats application directory contains the format settings that describe this document, and additional settings for the correct configuration and loading of the reports. The directory also contains the report structure that is loaded automatically from the XML schema definition (XSD) for the file.

You can add versions to the format directory manually or automatically.

## Add a format version manually

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Periods of formats application**.

2.  Click **New**, and then in the **Format version** and **KND code** fields, enter an identification number and Klassificator nalogovoy documentacii (KND) code for the format.

3.  In the **Form name**, **Format part number**, and **Number of version** fields, enter the Nalogovaya Buhgalterskaya Otchetnost (NBO) form name, the NBO format part number, and the version number.

4.  In the **Application start date** field, select the starting date of the period for which to use the NBO format.

5.  In the **First application period** field, enter the first tax reporting period for which to use the NBO format.

6.  In the **Application end date** field, select the ending date of the period for which to use the NBO format.

7.  In the **Number in formats register** field, enter the format version number in the Federal registry for the submission of legislation reporting.

8.  On the **General** tab, in the **File name prefix** field, enter the prefix for the file name.
    

    > [!NOTE]
    > <P>The prefix O is used for all text format versions. The value from the <STRONG>File name prefix</STRONG> field is used to name output files that are created by using a configured template that the format version is specified for.</P>



9.  In the **File name** and **Format** fields, select a fixed requisite and the format code for the fixed requisite.

10. In the **Resolution number and approval date** field, enter the NBO form resolution number and approval date.

11. In the **Note** field, enter a description that is displayed on the report.

12. Click **Load XSD schema**, and then in the **File name** field, specify the name and path of the schema file.

13. Click **OK**. The versions format is displayed in the **XSD schema** field on the **XSD text** tab. The template structure is created based on the loaded schemas.

## Add a format version automatically

Use the **Selection of KND** form to import Spavochnik periodov primeneniya formatov documentov (SPPFD).

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Periods of formats application**.

2.  Click **Import of SPPFD**.

3.  Select the **Select** check box for each version to import for the selected report.

4.  Click **Check** \> **Check selected** to open the **Load Microsoft Word file with formats list** form, where you can check for new versions for the selected KND code.
    
    –or–
    
    Click **Check** \> **Check all** to open the **Load Microsoft Word file with formats list** form, where you can check for new versions for all KND codes.

5.  In the **Application start date** field, select the date when the format version is applicable.

6.  Click **OK**. All new versions after the specified date that have a matching KND code are displayed on the **List of updates** tab.

7.  On the **List of updates** tab, select the **Select** check box for the versions to add to the directory.

8.  Click **Add** \> **Add selected** to add the selected versions only.
    
    –or–
    
    Click **Add** \> **Add all** to add all versions.

## See also

[(RUS) Periods of formats application (form)](https://technet.microsoft.com/en-us/library/jj710684\(v=ax.60\))

[(RUS) Fixed requisites (form)](https://technet.microsoft.com/en-us/library/jj710680\(v=ax.60\))

[(RUS) Format of requisites (form)](https://technet.microsoft.com/en-us/library/jj710737\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

