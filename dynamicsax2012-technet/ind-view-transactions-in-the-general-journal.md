---
title: (IND) View transactions in the general journal
TOCTitle: (IND) View transactions in the general journal
ms:assetid: e5b0af3c-6e08-40aa-a409-3dc9f0814f8a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710910(v=AX.60)
ms:contentKeyID: 49386322
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) View transactions in the general journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can view or edit the transferred information from the tax journal to the journal voucher. When you transfer the tax journal to the general journal, the sales tax code, the sales tax group, the item sales tax group, the customs tariff code, VAT, Service tax and the debit amount for the account number is displayed in the journal voucher. You can also create journal voucher lines without transferring the tax journal.


> [!NOTE]
> <P>For information about creating a tax journal and transferring it to the general journal, see <A href="ind-create-a-tax-journal-for-customs.md">(IND) Create a tax journal for customs</A>, <A href="ind-create-tax-journals-for-vat.md">(IND) Create tax journals for VAT</A>, and <A href="ind-create-a-tax-journal-for-service-tax.md">(IND) Create a tax journal for service tax</A>.</P>



1.  Click **General ledger** \> **Journals** \> **General journal**. Click **Lines** to open Journal voucher form
    

    > [!NOTE]
    > <P>For more information, see "General journal lines (form)" in the Applications and Business Processes Help.</P>



2.  Select the account type and account number in the **Account type** and **Account** fields.

3.  Modify the amount in the **Debit** or **Credit** field.

4.  On the **General** tab, select the tax code in the **Sales tax code** field.

5.  Select the sales tax group in the **Sales tax group** field and the item sales tax group in the **Item sales tax group** field.

6.  Modify the assessable value that is set in the **Debit** or **Credit** field on the **Overview** tab.
    

    > [!NOTE]
    > <P>If the transaction currency is other than the base currency, the assessable value is converted to the base currency using the customs exchange rate, based on the transaction date.</P>



7.  View or modify the tax information for the selected tax journal in the **Tax Information** tab.
    

    > [!NOTE]
    > <P>If the transaction currency is other than the base currency, the assessable value is converted to the base currency using the customs exchange rate, based on the transaction date.</P>



8.  Click **Sales tax** to view the calculated sales tax details and modify the amount that the sales tax is adjusted to in the **Temporary sales tax transactions** form.

9.  Click **Formula designer** to view the formula defined for the item tax group and the tax group.

10. Press CTRL+S or close the form.

## See also

[(IND) Formula designer (form)](https://technet.microsoft.com/en-us/library/jj677983\(v=ax.60\))

[(IND) Setting up Value Added Tax (VAT)](ind-setting-up-value-added-tax-vat.md)

[(IND) Journal voucher - General journal (modified form)](https://technet.microsoft.com/en-us/library/jj678053\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664487\(v=ax.60\))

[(IND) Create a tax journal for customs](ind-create-a-tax-journal-for-customs.md)

[(IND) Create tax journals for VAT](ind-create-tax-journals-for-vat.md)

[(IND) Create a tax journal for service tax](ind-create-a-tax-journal-for-service-tax.md)

  


