---
title: Upgrade reason codes
TOCTitle: Upgrade reason codes
ms:assetid: ffb6c577-5e92-4e2c-8a41-03e0c15ad088
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh454988(v=AX.60)
ms:contentKeyID: 36993127
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Upgrade reason codes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Reason codes are used to explain why transactions were entered, such as why a request for quotation (RFQ) was rejected. In previous releases of Microsoft Dynamics AX, you could create an RFQ reason code of up to 20 characters. In Microsoft Dynamics AX 2012, reason codes have a limit of 10 characters.

## Modules affected

Accounts payable and Procurement and sourcing

## Versions affected

Microsoft Dynamics AX 4.0 and Microsoft Dynamics AX 2009

## Data model changes

The **PurchRFQReasonCode** table was merged into the **ReasonTable** table.

## Upgrade notes

In previous releases of Microsoft Dynamics AX, you could create reason codes in a separate RFQ reason code form. In Microsoft Dynamics AX 2012, you create all reason codes in the financial reason codes form.

During upgrade from an earlier version of Microsoft Dynamics AX to Microsoft Dynamics AX 2012, the table for RFQ reason codes is merged into the table for financial reason codes. An upgraded RFQ reason code identification number (ID) might be longer than the current limit of 10 characters for reason code IDs. If an RFQ reason code ID is longer than 10 characters, the RFQ reason code ID is truncated during upgrade and numeric digits are added so that the IDs remain unique.

You can modify the upgraded RFQ reason code IDs to remove the numeric digits. The new ID must remain unique. Use the following procedure to modify a reason code.

1.  Click **Organization administration** \> **Setup** \> **Financial reasons**.

2.  In the **Financial reasons** form, select the reason code that you want to modify.
    

    > [!WARNING]
    > <P>When you modify a reason code, the transactions and documents that reference the reason code are not automatically updated with the modified reason code information. You can manually change the reason code in a document.</P>



3.  Right-click the reason code, and then select **Record info**.

4.  In the **Record information** form, click **Rename**.

5.  In the **Reason code** field, enter a new ID for the reason code.

6.  Scroll down the form, and then click **OK**.

## See also

[Reasons (form)](https://technet.microsoft.com/en-us/library/hh209362\(v=ax.60\))

[About financial reason codes](about-financial-reason-codes.md)

  


