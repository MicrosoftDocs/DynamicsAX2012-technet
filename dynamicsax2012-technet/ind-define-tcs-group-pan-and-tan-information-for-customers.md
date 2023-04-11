---
title: (IND) Define TCS group, PAN, and TAN information for customers
TOCTitle: (IND) Define TCS group, PAN, and TAN information for customers
ms:assetid: f6f047cf-9b72-4ccb-adfe-712fb99831d9
ms:mtpsurl: https://technet.microsoft.com/library/JJ710943(v=AX.60)
ms:contentKeyID: 49386355
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Define TCS group, PAN, and TAN information for customers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. On the **Action Pane**, on the **Customer account** tab, in the **Customer account** group, click **Customer account**.

2.  Select the default TCS group to calculate TCS for the customer in the **TCS group** field.
    

    > [!NOTE]
    > <P>The <STRONG>TDS group</STRONG> field is not available if you select a TCS group in the <STRONG>TCS group</STRONG> field.</P>



3.  Click the **Tax information** tab, and select the status for the Permanent Account Number (PAN) for the customer in the **Status** field from the following options:
    
      - **Not available** – Customer does not have a PAN.
    
      - **Received** – Customer has a PAN.
    
      - **Applied** – Customer has applied for a PAN.
    
      - **Invalid** – The customer’s PAN number is not valid.

4.  If the PAN status is **Received**, enter the PAN information in the **Number** field.
    

    > [!NOTE]
    > <P>The PAN number must consist of five alphabetic characters, four numeric characters, and one alphabetic character; for example, ABCDE1260A.</P>



5.  If the PAN status is **Applied**, enter the reference number in the **Reference number** field.

6.  In the **Nature of assessee** field, select the nature of the assessee category for the customer from the following options:
    
      - **Company**
    
      - **HUF**
    
      - **Firm**
    
      - **Individual**
    
      - **AOP**
    
      - **BOI**
    
      - **Local authority**
    
      - **Others**

7.  Enter the Tax Account Number (TAN) for the address of the customer in the **Number** field.
    

    > [!NOTE]
    > <P>The withholding tax registration numbers that are created for the customers registration number type in the <STRONG>Withholding tax registration numbers</STRONG> form (<STRONG>General ledger</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Withholding tax</STRONG> &gt; <STRONG>India</STRONG> &gt; <STRONG>Withholding tax registration numbers</STRONG>) are available in this field.</P>



8.  Press CTRL+S or close the form.

## See also

[(IND) Customers (modified form)](https://technet.microsoft.com/library/jj678004\(v=ax.60\))

  


