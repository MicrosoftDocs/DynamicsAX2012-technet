---
title: (RUS) Calculate assessed tax and generate an assessed tax declaration
TOCTitle: (RUS) Calculate assessed tax and generate an assessed tax declaration
ms:assetid: eee43154-913e-4e38-8a4c-6061baf6b778
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678599(v=AX.60)
ms:contentKeyID: 49388081
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Calculate assessed tax and generate an assessed tax declaration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Print assessed tax declaration** form to generate a declaration of assessed tax. After you generate and export the assessed tax declaration by using Microsoft Excel, you can submit it electronically to the tax authority. You can also print and mail the declaration to the tax authority.

1.  Click **Fixed assets (Russia)** \> **Journals** \> **Tax register journal**.

2.  Create a journal, and then calculate the assessed tax.

3.  If the tax is calculated for a year, click **Print** \> **Assessed tax**.
    

    > [!NOTE]
    > <P>If the tax is calculated for other periods, such as a month, quarter, or half year, click <STRONG>Print</STRONG> &gt; <STRONG>Advance payment</STRONG>.</P>



4.  In the **By place** field, select the company location from which you are submitting the declaration:
    
      - **of accounting of the first-rate taxpayer** – The declaration is created for all fixed assets that are registered at the head office and separate divisions. The information that pertains to the head office is printed on the title page.
    
      - **of detached department being** – A separate declaration is created for each separate division for which the **Independent** check box is selected in the **Separate divisions** form. Individual fixed asset declarations are created for the head office and each separate division, and the information that pertains to the head office is printed on the title page.
    
      - **of accounting of foreign organization** – A separate declaration is created for the tax authority that is associated with foreign transactions.
    
      - **of immovable property object being** – A separate declaration is created for the tax authority that is associated with transactions that pertain to immovable properties.

5.  Click **OK** to generate and export the assessed tax declaration.

## See also

[(RUS) Print assessed tax declaration (form)](https://technet.microsoft.com/en-us/library/jj711475\(v=ax.60\))

[(RUS) Tax register journal (form)](https://technet.microsoft.com/en-us/library/jj856114\(v=ax.60\))

[(RUS) Calculate assessed tax registers](rus-calculate-assessed-tax-registers.md)

[(RUS) Create an assessed tax declaration](rus-create-an-assessed-tax-declaration.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

