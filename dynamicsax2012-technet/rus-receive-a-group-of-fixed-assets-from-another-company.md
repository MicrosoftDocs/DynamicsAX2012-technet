---
title: (RUS) Receive a group of fixed assets from another company
TOCTitle: (RUS) Receive a group of fixed assets from another company
ms:assetid: dd224f6b-5ca3-428a-86a3-098bc4066710
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711675(v=AX.60)
ms:contentKeyID: 49387998
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Receive a group of fixed assets from another company [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can register the receipt of several fixed assets or inventory assets at a time by using transfer journals. This can be done when the transferring company has posted asset numbers in the FA journal. If information about value models is not displayed, you must enter or modify the information manually.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets (Russia)** \> **Journals** \> **Transfer journals** \> **Receipt from another company**.

2.  On the **Overview** tab, press CTRL+N.

3.  In the **Date** field, enter the date of the transfer of the assets from the other company.

4.  In the **Company accounts ID** field, enter the account ID of the company that is receiving the assets, if this company is in the same database.
    

    > [!NOTE]
    > <P>A journal number is displayed in the <STRONG>Journal number</STRONG> field, based on the configured number sequence. You can also enter the journal number manually.</P>



5.  Click **Lines** and press CTRL+N in the **Lines of FA transfer journal** form.

6.  In the **Source** field, select the inventory number of the asset being accepted from the other company.
    

    > [!NOTE]
    > <P>If you have selected an asset number in the <STRONG>Source</STRONG> field and a full correspondence of value models has been set up between the transferring and accepting companies, then information in the fields on the <STRONG>Value models</STRONG> tab are displayed. Otherwise, you must enter or modify the information manually.</P>



7.  Click **Create fixed asset**.
    

    > [!NOTE]
    > <P>This button is available only if an asset number is displayed in the <STRONG>Source</STRONG> field, but no destination is selected. This may occur if the recipient is not specified in the asset transfer transaction to another company.</P>



8.  In the **Create fixed asset** form, select the FA group that the asset belongs to. An inventory number for the fixed asset or inventory asset will be assigned automatically.

9.  Click **OK**. An asset record will be created and a destination will be displayed.

10. In the **Lines of FA transfer journal** form, click **Creating from issue** to automatically create lines in the **Receipt from another company** form.

11. Select the journal in the upper pane of the **Adding fixed assets from issue journals for another company** form, and then click **Copy journal** to copy all the information from the specified transfer journal into the receipt journal.

12. In the lower pane of the form, click **Copy journal line** to copy individual lines of the transfer journal into the receipt journal.

13. In the **Receipt from another company** form, click **Close**. The information from the receipt will be updated in the asset records.

14. Click **Fixed assets (Russia)** \> **Journals** \> **FA journal**.

15. Click **Lines** and enter the receipt transaction in the journal lines. This process is similar to creating an acquisition transaction.
    

    > [!NOTE]
    > <P>The date of the transaction in the <STRONG>Fixed asset</STRONG> form cannot be earlier than the date when the receipt was registered in the asset history. You must use a group transaction to create lines. Lines will be automatically created for all fixed assets for which history information about receipt from another company has been specified.</P>



16. Click **Validate** \> **Validate** to validate the journal.

17. Click **Post** \> **Post** to create the transactions in the ledger and in fixed assets.
    

    > [!NOTE]
    > <P>You can view the information about the transfer of assets between companies in the <STRONG>Receipt from another company</STRONG> form.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

