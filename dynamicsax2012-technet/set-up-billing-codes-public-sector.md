---
title: Set up billing codes (Public sector)
TOCTitle: Set up billing codes (Public sector)
ms:assetid: 3db65013-1f98-4653-b222-6fdc19f71b63
ms:mtpsurl: https://technet.microsoft.com/library/Hh208523(v=AX.60)
ms:contentKeyID: 36056270
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- billing code setup
- setup billing code
audience: Application User
ms.search.region: Denmark, France
---

# Set up billing codes (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A billing code is a set of default values that are applied automatically to free text invoice lines where the billing code is selected. The departments in your organization can use billing codes for a defined type of service or charge. For example, a waste management department might bill certain customers for new containers. You can use the **Billing codes** form to specify the default values for billing charges that your organization uses regularly.

You can associate billing codes with posting definitions on the **Accounts receivable** tab of the **Transaction posting definitions** form. When a billing code is used on an invoice line, the posting definition that is associated with the billing code is used for posting the transaction to the ledger. For more information, see [Transaction posting definitions (form)](https://technet.microsoft.com/library/hh242550\(v=ax.60\)).

You cannot delete a billing code after it has been used on a free text invoice line.

1.  Click Click **Accounts receivable** \> **Setup** \> **Billing codes**.

2.  Click **New** to create a line for a new billing code.

3.  Enter a unique code in the **Billing code** field, such as **BusLic**.

4.  In the **Description** field, describe the charge represented by the billing code, such as **Business License Fees**.

5.  To restrict use of the billing code until a future date, or to specify an expiration date for the billing code, enter the appropriate **Effective** or **Expiration** date.
    

    > [!NOTE]
    > <P>You can create additional billing code versions with different date ranges that contain different values. For more information, see <STRONG>Create billing code versions</STRONG> later in this topic.</P>



6.  In the **Item sales tax group** field, select the item sales tax group to be used on the invoice line.

7.  Specify the interest code:
    
      - Select the **Use interest code from billing classification** check box to use the interest code specified on the billing classification when calculating interest for this billing code *–or–*
    
      - Select the **Interest code** that will be used to calculate interest for this billing code. This field not available if the **Use interest code from billing classification** check box is selected.
        

        > [!WARNING]
        > <P>If an <STRONG>Interest code</STRONG> is not selected and the <STRONG>Use interest code from billing classification</STRONG> check box is not selected, interest will not be calculated.</P>



8.  On the **Accounting distribution** tab, click **Add**.

9.  In the **Percent** field, enter a distribution percentage for the selected ledger account. By default, the distribution percentage for the first ledger account is 100 percent. The sum of all distribution percentages must be 100.
    

    > [!NOTE]
    > <P>If you change the first distribution percentage to be less than 100, each new line that you create receives a default percentage that is equal to 100 minus the sum of the previous percentages.</P>



10. In the **Ledger account** field, select the account that the billing charge is posted to.

11. On the **Rate** tab, select either **Line amount** or **Unit price** in the **Billing code determines** field to specify whether the calculated billing amount is used for the **Amount** field or the **Unit price** field on the invoice line.

12. Select either **Fixed rate** or **Rate script** in the **Rate type** field to determine the default billing amount:
    
      - **Fixed rate** - Enter a billing amount for the company currency in the **Amount** field. Repeat this step for each additional currency and billing amount.
        

        > [!NOTE]
        > <P>By default, the code for the company currency is displayed on the first line of the currency table. If you use the currency table, you must enter a billing amount for the company currency. You can change the amount, but you cannot delete the line.</P>

    
      - **Rate script** - Select the programming language and enter or paste the script. If you prefer to develop and debug the script in Visual Studio 2010, click the **Advanced editing** link (Optional). For more information, see [About billing code rate scripts (Public sector)](about-billing-code-rate-scripts-public-sector.md).

13. In the **Amount details** field, enter information that explains the charge represented by the billing code.
    
    The text that you enter is displayed in the **Free text invoice** form when you select a line where the corresponding billing code is used.
    

    > [!NOTE]
    > <P>This control is only available if you selected <STRONG>Fixed rate</STRONG> in the <STRONG>Rate type</STRONG> field.</P>



14. If you want to assign one or more **Billing code custom fields** to this billing code, click **Add** on the **Custom fields** tab. For more information, see [Billing code custom fields (form) (Public sector)](https://technet.microsoft.com/library/hh208512\(v=ax.60\)).

15. Optional: On the **Project** tab, select the project and category that will be entered on the **Free text invoice** form for the lines that use the selected billing code. The **Project** tab is available only if **Display project-related fields on free text invoices** is selected on the **Accounts receivable parameters** form. For more information, see [Billing codes (form) (Public sector)](https://technet.microsoft.com/library/hh208543\(v=ax.60\)).

16. If you want to create a new version of this billing code for a specific date range, click **New version**. For more information, see [Billing codes (form) (Public sector)](https://technet.microsoft.com/library/hh208543\(v=ax.60\)).

## Create billing code versions

You can create multiple versions of a billing code if a small amount of billing code information will change on a specified date. For example, you can create a billing code version that increases the current billing code fee at the end of the year. To do this, create the initial billing code with the expiration date set to the last day of this year, and then create a new version of the billing code that starts on the first day of the next year with the increased fee.

1.  Complete the steps earlier in this topic to create the billing code with the initial information and date range.

2.  Click **New version**.

3.  Enter the effective and expiration dates for the new version.

4.  Click **Create** to create the new billing code version.

5.  Click **Current records** to expand the billing code view options.

6.  Select the **Display all records** check box and then click **Apply** to view the new billing code version.

7.  Select the new billing code version and make any changes that apply to that version.

## See also

[Set up billing code custom fields (Public sector)](set-up-billing-code-custom-fields-public-sector.md)

  


