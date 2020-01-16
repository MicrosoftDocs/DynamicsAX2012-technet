---
title: (RUS) Calculate transport tax and generate a transport tax declaration
TOCTitle: (RUS) Calculate transport tax and generate a transport tax declaration
ms:assetid: 47080df1-cf5b-4c04-9673-e27cecb415d9
ms:mtpsurl: https://technet.microsoft.com/library/JJ665340(v=AX.60)
ms:contentKeyID: 49387428
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate transport tax and generate a transport tax declaration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Print transport tax declaration** form to generate a declaration of transport tax. After you generate and export the transport tax declaration by using Microsoft Excel, you can submit it electronically to the tax authority. You can also print and mail the declaration to the tax authority.

1.  Click **Fixed assets (Russia)** \> **Journals** \> **Tax register journal**.

2.  Create a journal, and then calculate the assessed tax. For more information, see [(RUS) Calculate assessed tax registers](rus-calculate-assessed-tax-registers.md).

3.  If the tax is calculated for a year, click **Print** \> **Transport tax** to open the **Print transport tax declaration** form, and then enter the required details.
    

    > [!NOTE]
    > <P>If the tax is calculated for another period, such as a month, quarter, or half-year, click <STRONG>Print</STRONG> &gt; <STRONG>Advance payment</STRONG>.</P>



4.  In the **By place** field, select the company location that you are submitting the declaration from:
    
      - **of Russian organization being** – A declaration is created that includes information for all fixed assets that are registered at the head office and separate divisions. The head office information is printed on the title page.
    
      - **of detached department being** – A separate declaration is created for each separate division for which the **Independent** check box is selected in the **Separate divisions** form. An individual fixed asset declaration is also created for the head office, and the information that pertains to the head office is printed on the title page.

5.  Click **OK** to generate and export the transport tax declaration, and to close the form.

## See also

[(RUS) Print transport tax declaration (form)](https://technet.microsoft.com/library/jj711516\(v=ax.60\))

[(RUS) Tax register journal (form)](https://technet.microsoft.com/library/jj856114\(v=ax.60\))

[(RUS) Create a transport tax declaration](rus-create-a-transport-tax-declaration.md)

  


