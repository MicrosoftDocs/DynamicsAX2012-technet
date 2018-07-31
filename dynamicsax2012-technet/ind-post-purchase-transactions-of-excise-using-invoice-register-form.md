---
title: (IND) Post purchase transactions of excise using Invoice register form
TOCTitle: (IND) Post purchase transactions of excise using Invoice register form
ms:assetid: e68288bf-3fb5-44f2-9ab2-0fcdb58b4ec5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710891(v=AX.60)
ms:contentKeyID: 49386304
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Post purchase transactions of excise using Invoice register form 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can post purchase transactions with excise details using the **Invoice register** form. The procedure is similar to posting transactions in the **General journal** form.


> [!NOTE]
> <P>The excise registers will not be updated when you post a journal from the invoice register.</P>



1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice register**.

2.  Create a journal line in the invoice register. The procedure to create a journal line for excise transactions in the **Invoice register** form is similar to creating journal lines in the **General journal** form.
    

    > [!NOTE]
    > <P>For more information see, "Create and validate a journal and journal lines" in the Application and Business Processes Help.</P>



3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.
    
    The formula for the calculation of excise is defined in the **Formula designer** form as illustrated in the following table.
    
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
    <td><p>SHE-cess</p></td>
    <td><p>Excl. line amount</p></td>
    <td><p>+[SED]</p></td>
    </tr>
    </tbody>
    </table>


4.  Select the **Price incl. tax** check box for all the tax components in the **Formula designer** form. The excise rate percentage for BED is 10 percent, AED is 10 percent, SED is 5 percent, E-Cess is 1 percent, and SHE- cess is 1 percent.

5.  Validate and post the journal line in the **Invoice register** form.
    
    **Example**
    
    Suppose that you create an invoice journal in the invoice register. The credit amount in the journal line is INR 9,000, and the maximum retail price of the item is INR 6,000. The excise record type selected is RG23C. Set the claim percentage for CENVAT to 50 percent in the **Claim percentage** form.
    
    According to the example, excise is calculated in the Invoice register journal as follows:
    
    BED = (4,757.37\*10%) = 475.74
    
    AED = (4,757.37\*10%) = 475.74
    
    SED = (5,708.85\*5/100) = 285.45; (4,757.37 + 475.74 + 475.74 = 5,708.85)
    
    E-cess = (285.44\*1%) = 2.85
    
    SHE-cess = (285.44\*1%) = 2.85
    
    Max. Retail Price = Tax basis + Excise = 4,757.37 + 1242.63 = 6,000
    

    > [!NOTE]
    > <P>The tax basis and the taxes are calculated automatically by the Microsoft Dynamics AX application. The amount origin and the tax amounts calculated are displayed in the <STRONG>Temporary sales tax transactions</STRONG> form. An excise duty of INR 1,242.63 is calculated.</P>

    
    When the journal is posted, the recoverable accounts of the tax components are debited with the 50 percent of the related excise taxes and the RG23C deferred accounts of the tax components are debited with the remaining 50 percent of the related excise taxes. However, the RG23C Part II register is not updated with the excise tax amount.

## See also

[(IND) Formula designer (form)](https://technet.microsoft.com/en-us/library/jj677983\(v=ax.60\))

[(IND) Claim percentage (form)](https://technet.microsoft.com/en-us/library/jj710873\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664487\(v=ax.60\))

  


