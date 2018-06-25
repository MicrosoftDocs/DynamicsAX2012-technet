---
title: Set up promissory notes
TOCTitle: Set up promissory notes
ms:assetid: 0309fe79-43fc-491b-b230-1d6ede75367c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569701(v=AX.60)
ms:contentKeyID: 36055936
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up promissory notes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A promissory note is a written agreement in which the maker of the note promises to pay a certain amount at a certain time.

When you use promissory notes as payment for vendor invoices, you debit the vendor account. You will typically settle the invoice with the promissory note on the due date. When you receive notification from the bank that the promissory note has been honored, you can close the promissory note. In Microsoft Dynamics AX, you use journals to manage promissory notes.

Use the following procedures to set up promissory notes for your business. Some setup options for promissory notes are available only when specific configuration keys are selected. For more information, see [Country/region-specific topics for Microsoft Dynamics AX](country-region-specific-topics-for-microsoft-dynamics-ax.md).

## Set up posting profiles for promissory notes

Use the **Vendor posting profiles** form to set up posting profiles to use when you post promissory notes, promissory note remittances, or invoice remittances.

1.  Click **Accounts payable** \> **Setup** \> **Vendor posting profiles**.

2.  Click **New** or press CTRL+N to create a vendor profile. Enter an identifier, such as PN, and then enter a description, such as Promissory note.

3.  On the **Setup** FastTab, in the **Summary account** field, select the summary account to post the promissory note amounts to:
    
      - For promissory notes, this account is credited when a promissory note is posted and is debited when a remittance is posted.
    
      - For promissory note remittances, this account is credited when a remittance is posted and is debited when the remittance is settled.
    
      - For invoice remittances, this account is credited when a remittance is posted and is debited when the remittance is settled. This account offsets the vendor summary account in these transactions.

4.  Select values for other account fields, as appropriate.

5.  Repeat steps 2 through 4 to create the posting profiles for promissory note remittances and invoice remittances.

6.  Close the form.

## Set up accounts payable parameters for promissory notes

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click the **Ledger and sales tax** tab.

3.  In the **Promissory notes** field, select the default posting profile to use when you post a promissory note or a redrawn promissory note.

4.  In the **Invoice remit** field, select the default posting profile to use when you post an invoice remittance.

5.  In the **Remit promissory note** field, select the default posting profile to use when you post a vendor bank remittance.

6.  Select the **Warn if payment proposal uses multiple methods of payment** check box if a message should be displayed when a payment proposal includes more than one method of payment for the same journal line.

7.  Click the **Number sequences** tab.

8.  In the **Note ID** row, select a number sequence to identify promissory note payment files.

9.  In the **Remittance number** row, select a number sequence to identify remittance files.

10. Close the form.

## Set up journal names for promissory notes

Create at least four journal names to use for promissory notes. For each promissory note journal, you can use the **Promissory note** tab on the corresponding journal voucher form to enter information about the promissory note. After promissory note journal lines are posted, you can see them in the **Promissory note journal** inquiry form and in the **Promissory note statistics** form.

1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

2.  Click **New** or press CTRL+N, and then in the **Name** field, enter the journal name. For more information, see [Journal names setup (form)](https://technet.microsoft.com/en-us/library/aa552517\(v=ax.60\)).

3.  On the **General** FastTab, in the **Journal type** field, select one of the following options:
    
      - **Vendor draw promissory note**
    
      - **Vendor redraw promissory note**
    
      - **Customer bank remittance**
    
      - **Vendor settle promissory note**

4.  If you selected the **Customer bank remittance** journal type, specify how remittance fees are posted in the **Fees posting** field. You can select one of the following options:
    
      - **Keep fees in journal** – Retain the fees in the remittance journal. You will post the fees after the payment amounts have been posted.
    
      - **Transfer fees, keep voucher no.** – Post fees by using the same voucher number as the one used for the original payment. The remittance fees are transferred into the journal that is specified for the bank account for the remittance, and the original voucher number is retained.
    
      - **Transfer fees, new voucher no.** – Transfer the remittance fees into the fee journal that is specified for the bank account for the remittance and assign a new voucher number.

5.  Repeat steps 2 through 4 to set up at least one journal name for each journal type.

6.  Close the form.

## Set up methods of payment for promissory notes

Set up at least one method of payment for promissory notes. If you do business with more than one bank, set up a method of payment that corresponds to the bill of exchange remittance format required for each bank.

If you do business in more than one country/region, set up a method of payment that corresponds to the promissory note export format that is used in each country/region. For more information, see [Country/region-specific topics for Microsoft Dynamics AX](country-region-specific-topics-for-microsoft-dynamics-ax.md) and [Methods of payment - vendors (form)](https://technet.microsoft.com/en-us/library/aa618565\(v=ax.60\)).

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Click **New** or press CTRL+N, and then in the **Method of payment** field, enter an identifier, such as PN.

3.  In the **Period** field, select the period during which invoices in automatic payment proposals are combined:
    
      - **Invoice** – One payment transfer is created for each invoice.
    
      - **Date** – All invoices for a vendor that have the same due date are combined.
    
      - **Week** – All invoices for a vendor that have a due date in the same week are combined.
    
      - **Total** – All invoices for a vendor are combined into one payment.

4.  In the **Description** field, enter a name or short description for the method of payment.

5.  In the **Grace period** field, enter the number of days in which your business is allowed a cash discount after the specified period, if applicable.

6.  In the **Payment status** field, select the payment status that is required to post a payment that is assigned this method of payment. Select the payment status as **Sent** to indicate that the promissory note document must be printed or that an export file must be created before you can post a payment that uses this method of payment.

7.  In the **Payment type** field, select **Promissory note**.

8.  (FRA) If you are setting up a method of payment for French promissory notes, click the **General** FastTab. In the **Type of draft** field, select **Promissory note**.

9.  Click the **File formats** FastTab.

10. Select an export format. For example, in the **Export format** field, you can select **Promissory note document**, which is the promissory note document format required by several countries/regions, including Spain.
    

    > [!NOTE]
    > <P>If the <STRONG>Export format</STRONG> field list is empty, click <STRONG>Setup</STRONG>, and then select one of the available formats.</P>



11. (FRA) In the **Remittance format** field, select a remittance format.

12. Select the **Create and post draw journal automatically when posting invoices** check box to have a promissory note drawn and posted when a vendor invoice is posted. Clear the check box to manually draw promissory notes in a draw promissory note journal.

13. If a promissory note should be drawn automatically when a vendor invoice is posted, you can select the **Run export script** check box to automatically export the promissory note information to a file. Clear the check box to manually create a payment file for each bank account.

14. Select a journal name that uses the **Customer draw bill of exchange** journal type to post the payments to a draw promissory note journal.
    

    > [!NOTE]
    > <P>Be sure to select a journal name with the correct journal type. Other payment journal types are used with different methods of payment, such as checks.</P>



15. Click the **Payment attributes** FastTab, and then select the options to be included when you select invoices by using a payment proposal:
    
      - Select the **Third-party bank** check box to include the bank account for the vendor.
    
      - Select the **Payment account** check box to include the bank account for the method of payment.
    
      - Select other options, if required by the export format for your bank or country/region.
    

    > [!NOTE]
    > <P>The payment attributes are used only when you select invoices by using a payment proposal.</P>



16. Click **Payment fee setup**, and then enter the payment fees for the method of payment in the **Payment fee setup** form. The payment fees that you set up in this form are used as the default entries on the **Payment fee** tab when journal lines are created in a redraw promissory note journal, remittance journal, or settle promissory note journal. For more information, see [Vendor payment fee setup (form)](https://technet.microsoft.com/en-us/library/aa598976\(v=ax.60\)).

17. Click **Remittance files for vendors** to show a list of generated remittance files.

18. Repeat steps 2 through 17 to set up additional methods of payment, if necessary.

19. Close the form.

## Set up payment fees for promissory notes

If vendors charge a fee when you pay with a promissory note, you can set up payment fees. Payment fees are charges that are associated with the process of collecting payments from customers. Each payment fee can have multiple payment fee setup lines associated with it. Use setup lines to control how default amounts for payment fees are calculated. For example, you can create setup lines for methods of payment, payment specifications, currencies, and time periods. You can also create setup lines for a percentage or amount based on day intervals, such as an interest percentage based on the length of time that a payment is overdue.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Payment fee**.

2.  Click **New** or press CTRL+N, and then enter information for the payment fee. For more information, see [Vendor payment fee (form)](https://technet.microsoft.com/en-us/library/aa573151\(v=ax.60\)).

3.  Click **Payment fee setup** to open the **Payment fee setup** form. For more information, see [Vendor payment fee setup (form)](https://technet.microsoft.com/en-us/library/aa598976\(v=ax.60\)).

4.  Click the **General** tab.

5.  In the **Method of payment** field, select a method of payment to use for the payment fee. The method of payment for the payment fee may be different from the method of payment for the payment that the fee is based on.

6.  In the **Payment specification** field, select the payment specification to use for the method of payment.

7.  Repeat steps 2 through 6 to set up additional payment fees, if necessary.

8.  Close the form.

## Set up remittance fees for bank remittance files

You can set up remittance fees that are charged by a bank for each remittance file that is generated. The remittance fees are posted when the remittance has been confirmed, and the realized fee amounts are known. These fees are different from payment fees, which are paid to vendors and are attached to journal lines.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select a bank account or click **Bank account** to create a new account, and then enter information for the bank account. For more information, see [Bank accounts (form)](https://technet.microsoft.com/en-us/library/aa587660\(v=ax.60\)).

3.  Click the **Negotiable instrument** FastTab.

4.  In the **Fee journal** field, select a journal to use for the generated remittance fees.

5.  In the **Collection expenses fee**, **Discount interests fee**, and **Invoice remit fee** fields, enter the amounts charged by the bank for each type of remittance. For each type of fee, select a ledger account to post the fee expenses to.

6.  Close the form.

## Set up document layouts for promissory notes

Specify the document layout required for each bank account that you will generate printed promissory note documents for.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select or create a bank account, and then enter the bank account details. For more information, see [Bank accounts (form)](https://technet.microsoft.com/en-us/library/aa587660\(v=ax.60\)).

3.  Click the **Setup** tab, click **Promissory note**, and then set up the layout. For more information, see [Promissory note layout (form)](https://technet.microsoft.com/en-us/library/aa583563\(v=ax.60\)).

4.  Close the form.

## Set up vendors for promissory notes

For each vendor that you will pay by using a promissory note, you can set up a default method of payment for promissory notes.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Select an existing vendor, and then double-click the vendor account.

2.  In the **Vendors** form, click the **Payment** FastTab.

3.  In the **Method of payment** field, select a method of payment that is set up for promissory notes.

4.  Select a payment specification, if necessary.

5.  Close the form.

## See also

[Draw a promissory note](draw-a-promissory-note.md)

[Remit a promissory note](remit-a-promissory-note.md)

[Settle a promissory note](settle-a-promissory-note.md)

[Redraw a promissory note](redraw-a-promissory-note.md)

[Journal names setup (form)](https://technet.microsoft.com/en-us/library/aa552517\(v=ax.60\))

[Bank accounts (form)](https://technet.microsoft.com/en-us/library/aa587660\(v=ax.60\))

[Promissory note layout (form)](https://technet.microsoft.com/en-us/library/aa583563\(v=ax.60\))

[Vendor bank accounts (form)](https://technet.microsoft.com/en-us/library/aa589805\(v=ax.60\))

[Methods of payment - vendors (form)](https://technet.microsoft.com/en-us/library/aa618565\(v=ax.60\))

[Vendor payment fee (form)](https://technet.microsoft.com/en-us/library/aa573151\(v=ax.60\))

[Vendor payment fee setup (form)](https://technet.microsoft.com/en-us/library/aa598976\(v=ax.60\))

[Vendor posting profiles (form)](https://technet.microsoft.com/en-us/library/aa551972\(v=ax.60\))

[About payment types](about-payment-types.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

