---
title: (IND) Set up a payment fee type for TDS authority payments
TOCTitle: (IND) Set up a payment fee type for TDS authority payments
ms:assetid: ffc59657-0992-41db-b4bf-8b6466f725c6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710992(v=AX.60)
ms:contentKeyID: 49386404
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up a payment fee type for TDS authority payments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Payment fee**.

2.  Press CTRL+N to create a payment fee.

3.  Enter the required details.

4.  Select the payment fee type in the **Fee type** field from the following options:
    
      - **None**
    
      - **Interest** – Select this option to charge interest on late payments made to the TDS authority vendor.
        

        > [!NOTE]
        > <P>In <STRONG>TDS statement Form 26Q</STRONG> or <STRONG>TDS statement Form 27Q,</STRONG> the total payment fee amount posted with a payment fee ID of the <STRONG>Interest</STRONG> fee type, with all the related transactions for the authority type of TDS, is displayed. If there is no relevant TDS transaction for a particular period, <STRONG>TDS statement Form 26Q</STRONG> is generated, and the <STRONG>TDS</STRONG>, <STRONG>Surcharge</STRONG>, <STRONG>Education cess</STRONG>, <STRONG>Interest</STRONG>, <STRONG>Others</STRONG>, and <STRONG>Total tax deposit</STRONG> fields are filled in with 0.00.</P>

    
      - **Others** – Select this option to include other charges on late payments made to the TDS authority vendor.
        

        > [!NOTE]
        > <P>The total payment fee amount posted with a payment fee ID of the <STRONG>Others</STRONG> fee type, with all the related transactions for the authority type of TDS, is displayed.</P>



5.  Select the main account to post the interest or the other charges to in the **Main account** field. Enter the other required details.

## See also

[(IND) TCS or TDS inquiry (form)](https://technet.microsoft.com/en-us/library/jj678019\(v=ax.60\))

  


