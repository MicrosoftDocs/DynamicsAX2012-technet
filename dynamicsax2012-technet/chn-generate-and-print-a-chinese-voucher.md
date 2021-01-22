---
title: (CHN) Generate and print a Chinese voucher
TOCTitle: (CHN) Generate and print a Chinese voucher
ms:assetid: 1ea04af5-e801-4a92-a56a-6451a2f6fc10
ms:mtpsurl: https://technet.microsoft.com/library/JJ664006(v=AX.60)
ms:contentKeyID: 49384590
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Chinese
- batch printing
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Generate and print a Chinese voucher 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can print a Chinese voucher with tax information from the **Journal voucher** form. You can print the transaction voucher before or after you post the journal. You can compare the printed information to verify that it is the same information before and after posting, and that the information is correct. For example, if you select sales tax in a journal voucher, the final voucher information includes the sales tax, which could be different from what was part of the journal. So, the print result must be accurate, and it must be the same as the result that is generated after the final posting.


> [!NOTE]
> <P>You must select the <STRONG>Chinese voucher system</STRONG> check box in the <STRONG>General ledger parameters</STRONG> form to create voucher transactions with Chinese vouchers.</P>



Use the following procedures to generate, post, and print Chinese vouchers.

## Generate and post a Chinese voucher

Use the **Journal voucher** form to generate and print Chinese vouchers. You can choose to print the voucher before or after posting it. The printed voucher report yields the same result in both cases.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Click **New** to create a new journal. In the **Name** field, select the general journal that you created in the **Journal names** form. For more information, see [About journal names](about-journal-names.md).

3.  Enter information in other fields, as appropriate. The default field information from the **Journal names** form is displayed.

4.  Click **Lines** to open the **Journal voucher** form. Some of the fields might display default values from the **Journal** form.

5.  In the **Account type** and **Account** fields, select **Ledger** and the ledger account.

6.  In the **Description** field, select transaction text to describe the transaction.

7.  In the **Credit** field, enter the amount to pay the customer.

8.  In the **Offset account type** and **Offset account** fields, select **Ledger** and the offset account.

9.  In the **Sales tax group** and **Item sales tax group** fields, select the sales tax group and the item sales tax group. To print a voucher without posting it, see Print a Chinese voucher.

10. Click **Post** \> **Post** to post the journal.
    

    > [!NOTE]
    > <P>You can also submit a journal for approval before posting it. For more information, see <A href="chn-create-approve-and-post-a-general-journal.md">(CHN) Create, approve, and post a general journal</A>.</P>



11. Click **Inquiries** \> **Voucher** to view posted voucher transactions in the **Voucher transactions** form.

## Print a Chinese voucher

Use the **Ledger voucher** form to print Chinese vouchers. Before you print the transaction vouchers, you can run a continuity check to confirm that the vouchers are sequentially numbered, and that there are no gaps in the fiscal period. For more information, see [(CHN) Voucher continuity check log (form)](https://technet.microsoft.com/library/jj664113\(v=ax.60\)). The printed voucher displays the transaction details, tax information, and the history of renumbered Chinese vouchers, if any.

1.  Click **General ledger** \> **Journals** \> **General journal**. Select a general journal, and then click **Lines**. Click **Print** \> **Voucher**. 
    
    –or–
    
    Click **General ledger** \> **Journals** \> **Chinese vouchers**. Click **Print** \> **Voucher**. 
    
    –or–
    
    Click **General ledger** \> **Periodic** \> **China** \> **Chinese voucher print**.

2.  In the **Ledger voucher** form, on the **General** tab, in the **Journal number** field, select a journal number.

3.  In the **Chinese voucher** field, select the voucher number to print.

4.  In the **Transactions** field, select **Current**, **Operations**, or **Tax** as the transaction type.

5.  Select a printing method for the voucher from the following options:
    
      - **Pre-printed paper** – Select a print layout code in the **Print layout code** field. The print layout codes that are set up for the print layout group that is attached to the voucher type are available in this field. The **TR101 booking (Default currency)** print layout code prints the report in the default currency, and the **TW101 booking (Foreign currency)** print layout code prints the report in both the foreign currency and the default currency.
    
      - **Blank paper** - Indicate whether to print the voucher in the default currency or the foreign currency. The **Foreign currency** option prints the report in both the foreign currency and the default currency. In the **Maximum lines** field, enter the maximum number of lines to print.

6.  Click **OK** to print the payment vouchers.

To set up a batch printing job for Chinese vouchers, follow the steps in the **Print Chinese vouchers in a batch** section.

## Print Chinese vouchers in a batch

You can configure Microsoft Dynamics AX to automatically batch print Chinese vouchers on a recurring basis. A batch job is a task that is submitted to the instance of the Microsoft Dynamics AX server for automatic processing. For more information, see [Configure the workflow batch jobs](configure-the-workflow-batch-jobs.md).

1.  Click **General ledger** \> **Journals** \> **General journal**. Select a general journal, and then click **Lines**. Click **Print** \> **Voucher**. 
    
    –or–
    
    Click **General ledger** \> **Journals** \> **Chinese vouchers**. Click **Print** \> **Voucher**. 
    
    –or–
    
    Click **General ledger** \> **Periodic** \> **China** \> **Chinese voucher print**.

2.  In the **Ledger voucher** form, click the **Batch** tab to configure a batch job.

3.  Select the **Batch processing** check box.

4.  In the **Task description** field, accept the default description for this batch job, or enter a new description.

5.  In the **Batch group** field, select the batch group that this batch job will be part of.

6.  Click **Recurrence** to open the **Recurrence** form.

7.  Specify how often the report is printed, and then click **OK**. For more information, see [Recurrence (form)](https://technet.microsoft.com/library/aa616143\(v=ax.60\)).

8.  Click **Alerts** to open the **Set up alerts for batch jobs** form. For more information, see [Set up alert for batch job (form)](https://technet.microsoft.com/library/hh209082\(v=ax.60\)).

9.  Specify how and when you receive alerts for the batch job, and then click **OK**.

10. Click **OK** to print the report to the selected destination on a recurring basis.

## See also

[(CHN) Print layout (form)](https://technet.microsoft.com/library/jj664037\(v=ax.60\))

  


