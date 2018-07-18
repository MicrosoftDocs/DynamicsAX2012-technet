---
title: (IND) Set up a payment fee type for TCS authority payments
TOCTitle: (IND) Set up a payment fee type for TCS authority payments
ms:assetid: 9d4f4bf9-391b-42ba-83ec-d85af4e54a0f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664707(v=AX.60)
ms:contentKeyID: 49386038
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up a payment fee type for TCS authority payments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Payment fee**.

2.  Create a payment fee. Enter the required details.

3.  Select the payment fee type in the **Fee type** field from the following options:
    
      - **None**
    
      - **Interest** – Charge interest on late payments made to the Tax Collected at Source (TCS) authority vendor.
        

        > [!NOTE]
        > <P>In <STRONG>Form 27EQ</STRONG>, the total payment fee amount posted with a payment fee ID of the <STRONG>Interest</STRONG> fee type, with all the related transactions for the authority type of TCS, is displayed. If there is no <STRONG>Interest</STRONG> or <STRONG>Others</STRONG> amount for a particular period and relevant TCS transaction, in the generated <STRONG>Form 27EQ</STRONG>, the <STRONG>TCS</STRONG>, <STRONG>Surcharge</STRONG>, <STRONG>Education cess</STRONG>, <STRONG>Interest</STRONG>, <STRONG>Others</STRONG>, and <STRONG>Total tax deposit</STRONG> fields are filled in with 0.00.</P>

    
      - **Others** – Include other charges on late payments made to the TCS authority vendor.
        

        > [!NOTE]
        > <P>The total payment fee amount posted with a payment fee ID of the <STRONG>Others</STRONG> fee type, with all the related transactions for the authority type of TCS, is displayed.</P>

    
    The **Ledger** option is displayed automatically in the **Charge** field when you select **Interest** or **Others** in the **Fee type** field.

4.  Select the ledger account to post the interest or the other charges to in the **Ledger account** field. Enter the other required details.

## See also

[(IND) Vendor payment fee (modified form)](https://technet.microsoft.com/en-us/library/jj710970\(v=ax.60\))

  


