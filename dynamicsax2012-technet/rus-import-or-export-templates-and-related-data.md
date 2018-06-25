---
title: (RUS) Import or export templates and related data
TOCTitle: (RUS) Import or export templates and related data
ms:assetid: 98326465-0e8d-4f7d-9774-9b0df9913ee6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677621(v=AX.60)
ms:contentKeyID: 49384923
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- import
- template
- export
- export template
- import template
---

# (RUS) Import or export templates and related data [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Import templates settings** and **Export templates settings** forms to import and export template settings from one template to another.

## Import template settings

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Create a document template, and then click **Functions** \> **Import**. For more information, see [(RUS) Set up templates for electronic reporting](rus-set-up-templates-for-electronic-reporting.md).
    
    –or–
    
    Select a template, and then click **Functions** \> **Import**.

3.  In the **File name** field, specify the name and path of the file that is imported.

4.  Select the **Show details** check box to view the imported data.
    

    > [!NOTE]
    > <P>All templates and their parameters are displayed on the <STRONG>Financial reports generator</STRONG> tab. This tab is available only if you select the <STRONG>Show details</STRONG> check box.</P>



5.  Click **Select new** to select items to import.

6.  Select a parameter, and then click **Compare** \> **Compare** to compare the value of the imported parameter and the one that already exists. The differences are displayed in the lower pane of the form.
    

    > [!NOTE]
    > <P>The <STRONG>Compare</STRONG> button is available for templates and parameters that already exist.</P>



7.  Click **OK** to import the template settings. The new templates and parameters are added, and the existing templates and parameters are updated.

## Export template settings

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**.

2.  Create a document template, and then click **Functions** \> **Export**. For more information, see [(RUS) Set up templates for electronic reporting](rus-set-up-templates-for-electronic-reporting.md).
    
    –or–
    
    Select a template, and then click **Functions** \> **Export**.

3.  In the **File name** field, specify the name and path of the file that the template is exported to.

4.  Select the **Export** check box for the template that is exported. Click **Select all** to select all the templates for export, or click **Clear all** to clear all the check boxes for the templates.

5.  Click the **Settings** tab. All available template parameters for the selected template are displayed on this tab.

6.  For each parameter, in the **Export** field, select whether to export all values of the parameter or only the values that are used.
    

    > [!NOTE]
    > <P>By default, only the parameter values that are used in the settings of the exported template are exported.</P>



7.  Click **OK** to export the template settings to the XML file that is specified in the **File name** field on the **General** tab.

## See also

[(RUS) Document templates (form)](https://technet.microsoft.com/en-us/library/jj923585\(v=ax.60\))

[(RUS) Export templates settings (form)](https://technet.microsoft.com/en-us/library/jj710788\(v=ax.60\))

[(RUS) Import templates settings (form)](https://technet.microsoft.com/en-us/library/jj710704\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

