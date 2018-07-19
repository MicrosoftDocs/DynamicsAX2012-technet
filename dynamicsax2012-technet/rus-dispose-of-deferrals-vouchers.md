---
title: (RUS) Dispose of deferrals vouchers
TOCTitle: (RUS) Dispose of deferrals vouchers
ms:assetid: 14fc4f68-8b8a-4c11-90fb-85108c03fa5d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711414(v=AX.60)
ms:contentKeyID: 49387232
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Dispose of deferrals vouchers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

2.  Press CTRL+N to create a new line, and enter the required details.

3.  In the **Name** field, enter the name of the journal.

4.  In the **Description** field, enter a short description of the journal.

5.  In the **Journal type** field, select **Deferrals**.

6.  In the **Voucher series** field, select the number sequence that is used for voucher numbering.

7.  Press CTRL+S or close the form.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/en-us/library/aa552517(v=ax.60)">Journal names setup (form)</A>.</P>



8.  Click **General ledger** \> **Journals** \> **Deferrals journal**.

9.  Press CTRL+N to create a new line, and enter the required details.

10. In the **Name** field, select the deferrals journal name.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/en-us/library/aa557917(v=ax.60)">Journal header (form)</A>.</P>



11. Click **Lines** to open the **Journal voucher** form.

12. Click **Group operations** \> **Disposal** to open the **Disposal** form.

13. In the **Disposal date** field, select the disposal date of the transaction.

14. Select the **Retirement on life time** check box to generate the disposal based on the specified disposal date specified in the deferrals card.

15. Click **Select** to open the **Inquiry** form, and set up the filter criteria.

16. Click **OK** to return to the **Journal voucher** form.
    

    > [!NOTE]
    > <P>The disposal voucher details are displayed for the selected deferrals on the specified date.</P>



17. To dispose of one deferral voucher, press CTRL+N in the **Journal voucher** form to open the **Create new line** form.

18. In the **Transaction date** field, select the disposal date of the transaction.

19. In the **Transactions type** field, select **Disposal**.

20. In the **Deferral ID** field, select the deferral code.

21. In the **Model number** field, select the deferral models number.
    

    > [!NOTE]
    > <P>If the model code is not specified in the journal, then all models that were created for the given deferral will be selected.</P>



22. Click **OK** and return to the **Journal voucher** form.

23. Click **Functions** \> **Edit line** to edit the journal before posting.

24. Click **Post** \> **Post** to post the reversal voucher.

25. Press CTRL+S or close the form. The deferrals and ledger transactions specified in the posting profile are generated. To view the performed transactions, click **General ledger** \> **Common Forms** \> **Deferrals** \> **Deferral models** \> **Writing off transactions**.
    

    > [!NOTE]
    > <P>The status field displays <STRONG>Closed</STRONG> for the deferral and the line is marked in gray in the <STRONG>Deferrals models</STRONG> form. You can post only the reversal voucher if it is the <STRONG>Writing off</STRONG> transaction type and <STRONG>Closed</STRONG> status.</P>



## See also

[(RUS) Create new line (form)](https://technet.microsoft.com/en-us/library/jj678398\(v=ax.60\))

  


