---
title: (IND) Post invoice transactions for excisable goods using a Purchase subscription
TOCTitle: (IND) Post invoice transactions for excisable goods using a Purchase subscription
ms:assetid: 33eccebc-cefd-4fbb-b4bb-290203a2294a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664600(v=AX.60)
ms:contentKeyID: 49385677
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Post invoice transactions for excisable goods using a Purchase subscription 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The invoice for excisable goods transaction is posted using **Subscription** as the purchase type.

For example, a subscription order is created for 100 quantities for an item. The unit price is INR 90 and the Maximum Retail Price (MRP) is INR 100. The line amount is INR 9,000. The excise record that is selected on the **Tax information** tab is RG23A. The claim percentage for RG23A is set as 50 percent in the **Claim percentage** form. An abatement of 40 percent is defined in the **Item sales tax group** form. The MRP is INR 6,000 after availing the abatement.

An invoice journal is created in the invoice register. The credit amount in the journal line is 9000, and the maximum retail price of the item is 6000. The excise record type that is selected is RG23C. The claim percentage for CENVAT is set as 50% in the **Claim percentage** form.

The formula for the calculation of excise is defined in the **Formula designer** form as shown in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tax code</p></th>
<th><p>Taxable basis</p></th>
<th><p>Calculation expression</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>BED</p></td>
<td><p>Max. retail price</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>AED</p></td>
<td><p>Max. retail price</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>SED</p></td>
<td><p>Max. retail price</p></td>
<td><p>+[BED]+ [AED]</p></td>
</tr>
<tr class="even">
<td><p>E-Cess</p></td>
<td><p>Excl. line amount</p></td>
<td><p>+[SED]</p></td>
</tr>
<tr class="odd">
<td><p>SHE- cess</p></td>
<td><p>Excl. line amount</p></td>
<td><p>+[SED]</p></td>
</tr>
</tbody>
</table>


The **Price incl. tax** check box is selected for all the tax components in the **Formula designer** form. The excise rate percentage for BED is 10%, AED is 10%, SED is 5%, E-Cess is 1% and SHE cess is 1%. The journal line is validated and posted.

According to this example, excise is calculated in the Invoice register journal as follows:

BED = (4,757.37 \* 10%) = 475.74

AED = (4,757.37 \* 10%) = 475.74

SED = (5,708.85 \* 5 / 100) = 285.44; (4,757.37 + 475.74 + 475.74 =5,708.85)

E-cess = (285.44\*1%) = 2.85

SHE-cess = (285.44 \* 1%) = 2.85

Max. retail price = Tax basis + Excise = 4,757.37 + 1242.63 = 6000


> [!NOTE]
> <P>The tax basis and the taxes are calculated automatically by the Microsoft Dynamics AX application based on the formula designer.</P>



The amount origin and the tax amounts that are calculated are displayed in the **Temporary sales tax transactions** form.

An excise duty of INR 1,242.63 is calculated. When the purchase order is posted, the recoverable accounts of the tax components are debited with the 50 percent of the related excise taxes, and the RG23A deferred accounts of the tax components are debited with the remaining 50 percent of the related excise taxes. The RG23A Part I register is updated with the quantity and the RG23A Part II register is updated with the excise tax amount.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Press CTRL+N to create a new purchase order.

3.  Select **Subscription** in the **Purchase type** field.

4.  The procedure for invoicing a purchase subscription is similar to invoicing a purchase order.
    

    > [!NOTE]
    > <P>For more information, see "Post a purchase order" in the Applications and Business Processes Help.</P>



## See also

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj664798\(v=ax.60\))

[(IND) Claim percentage (form)](https://technet.microsoft.com/en-us/library/jj710873\(v=ax.60\))

[(IND) Item sales tax groups (modified form)](https://technet.microsoft.com/en-us/library/jj710918\(v=ax.60\))

  


