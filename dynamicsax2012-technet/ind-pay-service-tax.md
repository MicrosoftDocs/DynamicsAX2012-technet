---
title: (IND) Pay service tax
TOCTitle: (IND) Pay service tax
ms:assetid: 133df2c5-cda8-4d1f-8774-ebc17b2ff8a6
ms:mtpsurl: https://technet.microsoft.com/library/JJ664501(v=AX.60)
ms:contentKeyID: 49385579
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Pay service tax 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use a payment journal to pay service tax to the service tax authority.

After service tax has been paid, you can use the **Challan information** form to update the challan information. Challan is a document that is used to make tax payments to tax authorities. It is not mandatory to update the challan information; however, you can update the challan information, if required. For more information, see [(IND) Setting up service tax](ind-setting-up-service-tax.md).


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. Click **Lines**.
    
    –or–

2.  Click **General ledger** \> **Journals** \> **General journal**. Click **Lines**.

3.  Click **Functions** \> **Challan information** to open the **Challan information** form to update the challan information.
    

    > [!NOTE]
    > <P>The <STRONG>Challan information</STRONG> form is activated for only posted journal transactions.</P>

    
    The **Challan information** option is activated for the following account combinations.
    
    <table>
    <colgroup>
    <col style="width: 25%" />
    <col style="width: 25%" />
    <col style="width: 25%" />
    <col style="width: 25%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Account type field</p></th>
    <th><p>Debit field</p></th>
    <th><p>Credit field</p></th>
    <th><p>Offset account type field</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Vendor account</p></td>
    <td><p>Positive amount</p></td>
    <td><p></p></td>
    <td><p>Bank</p></td>
    </tr>
    <tr class="even">
    <td><p>Bank</p></td>
    <td><p>Negative amount</p></td>
    <td><p></p></td>
    <td><p>Vendor account</p></td>
    </tr>
    <tr class="odd">
    <td><p>Vendor account</p></td>
    <td><p></p></td>
    <td><p>Negative amount</p></td>
    <td><p>Bank</p></td>
    </tr>
    <tr class="even">
    <td><p>Bank</p></td>
    <td><p></p></td>
    <td><p>Positive amount</p></td>
    <td><p>Vendor account</p></td>
    </tr>
    </tbody>
    </table>


4.  Select the **Service tax** option in the **Tax type** field.

5.  Enter the challan number in the **Challan number** field.

6.  Enter the date of the challan in the **Date** field.

7.  Enter the description of the challan in the **Text** field.

## See also

[(IND) Challan information (form)](https://technet.microsoft.com/library/jj677847\(v=ax.60\))

[(IND) Journal voucher - Vendor payment journal (modified form)](https://technet.microsoft.com/library/jj664794\(v=ax.60\))

  


