---
title: (RUS) Perform a single translation
TOCTitle: (RUS) Perform a single translation
ms:assetid: fbd7b8f5-8fb3-4c02-b9f6-004953b2c58f
ms:mtpsurl: https://technet.microsoft.com/library/JJ923615(v=AX.60)
ms:contentKeyID: 52075457
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Perform a single translation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can initiate a translation session to save the information for a translation. The translation session determines the way that ledger account transactions and data conversion from the source company to the target company are translated. Click **General ledger** \> **Setup** \> **General ledger parameters**. If this check box is cleared, transactions are translated without correspondence.

1.  Click **General ledger** \> **Periodic** \> **Translation** \> **Translation sessions**.

2.  In the **Rule group** field, select a translation group.

3.  Click **Translation wizard** to open the **Translation wizard** form, and then click **Next**.

4.  Click **Consistency check** to check the conversion parameters.
    

    > [!NOTE]
    > <P>If the <STRONG>Stop on the first error</STRONG> check box on the <STRONG>Translation</STRONG> area is selected in the <STRONG>General ledger parameters</STRONG> form, the translation wizard will not let you proceed to the next step until the conversion parameters are checked for additional errors.</P>



5.  Click **Next \>**, and then select the start and end dates in the **From date** and **To date** fields for the period that the translation is to be performed for.

6.  Click **Inquiry** to specify additional transaction selection criteria.

7.  Click **Next \>**, and then in the transaction processing window, click **Next** to run the data conversion.

8.  Click **Preview** to view the conversion results.

9.  Click **Next \>** \> **Next \>** to import the translation data to the target company.

10. Click **Finish** after the translation is completed.
    

    > [!NOTE]
    > <P>The <STRONG>Translation sessions</STRONG> form automatically creates a line for the translation session status when the translation session for the source company is finished. The <STRONG>Export status</STRONG> and <STRONG>Import status</STRONG> fields are automatically updated to <STRONG>Completed</STRONG>.</P>



## See also

[(RUS) Translation sessions (form)](https://technet.microsoft.com/library/jj852138\(v=ax.60\))

[(RUS) Translation wizard (form)](https://technet.microsoft.com/library/jj733514\(v=ax.60\))

  


