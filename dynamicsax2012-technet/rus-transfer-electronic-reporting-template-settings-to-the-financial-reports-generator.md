---
title: (RUS) Transfer electronic reporting template settings to the Financial reports generator
TOCTitle: (RUS) Transfer electronic reporting template settings to the Financial reports generator
ms:assetid: eb3d1c15-8a47-4e76-8c71-0f352260cded
ms:mtpsurl: https://technet.microsoft.com/library/JJ923610(v=AX.60)
ms:contentKeyID: 52075449
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- FRG
- electronic report
- transfer template
audience: Application User
ms.search.region: Russia
---

# (RUS) Transfer electronic reporting template settings to the Financial reports generator 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you specify an electronic reporting document template for a report, lines are created automatically in the Financial reports generator (FRG). For each field on the report, the name of the appropriate requisite is taken from the template.

Data from the electronic reporting document template is transferred to the **Field setup** form as follows:

  - The **Cell** field in the **Field setup** form is updated by using the values from the **Worksheet** and **Cell** fields in the **Fixed requisites** form. The values in the **Worksheet** and **Cell** fields are replaced so that they are in the format Worksheet name\!Cell range. The **Cell** field in the **Field setup** form is then updated with the resulting value.

  - The **Line type** and **Requisite** fields in the **Field setup** form are updated based on the settings for **Constant** requisite types that are specified in the **Requisites setup** form. For **Cell** requisite types, the **By default** field in the **Field setup** form is updated with the value that is specified in the **Default** field in the **Requisites setup** form.

  - For a **Constant** requisite type, a line that has a line type of **Fixed requisite** is created in the lower pane of the **Field setup** form. The **Fixed requisite** field displays the value from the settings for the document template.

  - For the **Value** requisite type, a line that has a line type of **Constant** is created in the lower pane of the **Field setup** form. The value in the **Data** field is updated with the data from the **Value** field in the **Requisites setup** form.

Use the following procedure to transfer the settings for the electronic report template to the FRG.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Financial reports generator**. Select a report line, and then click **Setup**.
    
    –or–
    
    Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Document templates**. Click **Report**. Select a report line, and then click **Setup**.

2.  Click **New**, and then in the **Report code** and **Description** fields, enter an identification number and a short description for the report.

3.  In the **Template** field, select the document template to use for the report.

4.  On the **General** tab, in the **File name** field, select the file name and path where the document template is saved.

5.  Press CTRL+S to save the report. Then click **Yes** to update the report by using cell information from the document template.

## See also

[(EEUR) Set up the financial reports generator](eeur-set-up-the-financial-reports-generator.md)

[(RUS) Document templates (form)](https://technet.microsoft.com/library/jj923585\(v=ax.60\))

[(RUS) Report (form)](https://technet.microsoft.com/library/jj853247\(v=ax.60\))

  


