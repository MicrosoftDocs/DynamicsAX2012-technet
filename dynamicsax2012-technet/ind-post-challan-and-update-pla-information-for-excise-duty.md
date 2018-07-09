---
title: (IND) Post challan and update PLA information for excise duty
TOCTitle: (IND) Post challan and update PLA information for excise duty
ms:assetid: 67996478-eb68-4910-9832-edda403e0e96
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677886(v=AX.60)
ms:contentKeyID: 49385851
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Post challan and update PLA information for excise duty [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. Click **Lines**.
    
    –or–
    
    Click **General ledger** \> **Journals** \> **General journal**. Click **Lines**.

2.  Enter the required information and post the journal.

3.  Click **Functions** \> **Challan information** to open the **Challan information** form and update the challan information.
    
    The **Challan information** option is available for the following account combinations:
    
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
    <tr class="odd">
    <td><p>Vendor account</p></td>
    <td><p>Positive amount</p></td>
    <td><p></p></td>
    <td><p>Ledger account</p></td>
    </tr>
    <tr class="even">
    <td><p>Ledger account</p></td>
    <td><p>Negative amount</p></td>
    <td><p></p></td>
    <td><p>Vendor account</p></td>
    </tr>
    <tr class="odd">
    <td><p>Vendor account</p></td>
    <td><p></p></td>
    <td><p>Negative amount</p></td>
    <td><p>Ledger account</p></td>
    </tr>
    <tr class="even">
    <td><p>Ledger account</p></td>
    <td><p></p></td>
    <td><p>Positive amount</p></td>
    <td><p>Vendor account</p></td>
    </tr>
    </tbody>
    </table>


4.  Select the **Excise** in the **Tax type** field.

5.  Enter the challan number in the **Challan number** field. The excise duty that must be paid to the excise authority is deposited in the bank using the T.R.6 challan.

6.  Enter the date of the challan in the **Date** field.

7.  Enter the description of the challan in the **Text** field.

8.  Close the form.

9.  Click **Functions** \> **Update PLA** to open the **Update PLA** form. The **Update PLA** option is available only when you update the excise and challan information for the posted transaction.

10. View the journal line amount of the transaction in the **Journal amount** field.

11. View the total of the amounts of the tax components in the **Component amount in Total** field.

12. Select the tax ledger posting group in the **Tax ledger posting group** field.

13. Select the Excise Control Code (ECC) number in the **ECC number** field.

14. Select the **Settle Interim PLA** check box for transactions that have the same ECC number and if the **Post to interim PLA** check box is selected in the **Sales tax payment** form. If the **Settle Interim PLA** check box is selected, the credit balance that is available in the interim PLA is reversed and transferred to the PLA, and also the PLA register is updated.

15. Select the excise tax component in the **Tax component** field, and view the PLA account for the excise component in the **PLA account** field.

16. Enter the amount that must be updated to the PLA in the **Amount** field.

17. Click **Post** to post the PLA voucher. The tax component amounts are debited to the personal ledger accounts.
    

    > [!NOTE]
    > <P>The <STRONG>Post</STRONG> button is activated only if the amount in the <STRONG>Journal amount</STRONG> field is equal to the amount in the <STRONG>Component amount in total</STRONG> field.</P>



18. Close the **Update PLA** form.

19. Click **Inquiries** \> **PLA Voucher** in the **Journal voucher** form to view the details of the PLA voucher.

## See also

[(IND) Challan information (form)](https://technet.microsoft.com/en-us/library/jj677847\(v=ax.60\))

[(IND) Journal voucher - General journal (modified form)](https://technet.microsoft.com/en-us/library/jj678053\(v=ax.60\))

[(IND) Set up excise tax components](ind-set-up-excise-tax-components.md)

[(IND) Set up excise settlement periods](ind-set-up-excise-settlement-periods.md)

[(IND) Journal voucher - Vendor payment journal (modified form)](https://technet.microsoft.com/en-us/library/jj664794\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

