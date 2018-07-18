---
title: (RUS) Generate and print an Inventory act (INV-11) report
TOCTitle: (RUS) Generate and print an Inventory act (INV-11) report
ms:assetid: 88afd3c1-911e-4cc6-9c68-d6acda762042
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678456(v=AX.60)
ms:contentKeyID: 49387685
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate and print an Inventory act (INV-11) report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you generate the deferrals inventory act report, you must create deferrals and writing off transactions in the deferrals journal.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>




> [!NOTE]
> <P>For more information, see <A href="rus-create-a-deferral-manually.md">(RUS) Create a deferral manually</A>, <A href="rus-generate-a-deferrals-write-off-voucher-for-one-deferral.md">(RUS) Generate a deferrals write-off voucher for one deferral</A>, and <A href="rus-generate-a-deferrals-write-off-voucher-for-all-deferrals.md">(RUS) Generate a deferrals write-off voucher for all deferrals</A>.</P>



1.  Click **General ledger** \> **Periodic** \> **Deferrals** \> **Deferrals counting journal**.

2.  Press CTRL+N to create a new journal.
    

    > [!NOTE]
    > <P>You cannot create more than one deferrals counting journal with the same counting date.</P>



3.  In the **Journal number** field, select a journal number.

4.  In the **Name** field, select the journal name with the journal type **Deferrals**.

5.  In the **Resolution number** field, enter the resolution number for the counting journal.

6.  In the **Resolution date** field, select the resolution date for the counting journal.

7.  In the **Counting start date** field, select the starting date of the deferrals counting period. This field displays the current date by default.
    

    > [!NOTE]
    > <P>The <STRONG>Counting end date</STRONG> field displays the ending date of the deferrals counting period specified in the <STRONG>End deferrals counting</STRONG> form.</P>



8.  Click the **Officials** tab to set up the officials' names, positions, and titles.

9.  In the **Position** field, select the position title of the official.

10. In the **Employee name** field, select the name of the official from the list of company employees.

11. In the **Job title** field, select the job title of the employee.

12. Click **Lines** to open the **Deferrals counting journal line** form to view the created journal lines.
    

    > [!NOTE]
    > <P>You can add new lines manually.</P>



13. In the **Model number** field, select the deferral model number of the created journal lines.
    

    > [!NOTE]
    > <P>The <STRONG>Counting start date</STRONG> and <STRONG>Counting end date</STRONG> fields display the starting date and ending date of the deferrals counting period specified in the <STRONG>Deferrals counting journal</STRONG> form.</P>



14. In the **Deferral ID** field, view or modify the deferral code.

15. In the **Name** field, view or modify the deferral name.

16. In the **Date attached** field, view or modify the deferral creation date.

17. In the **Writing off time** field, view or modify the write-off period for the deferral.

18. In the **Writing off amount** field, view or modify the amount written off between the creation of the deferral and the beginning of the counting period.

19. In the **Remaining amount** field, view or modify the amount to be written off in the future.

20. In the **Deferrals amount** field, view or modify the deferral amount in the default currency.

21. Click **Close** to open the **End deferrals counting** form.

22. In the **Counting end date** field, enter the date for closing the journal.
    

    > [!NOTE]
    > <P>The date that you specify in this field is displayed in the <STRONG>Counting end date</STRONG> field in the <STRONG>Deferrals counting journal</STRONG> form.</P>



23. Click **Print** to open the **Deferrals counting** form.

24. In the **Model number** field, select the deferral model number.

25. Click **OK** to print the Inventory act report using the MS Excel template for the selected model number.

26. Press CTRL+S or close the form.

## See also

[(RUS) Deferrals counting journal (form)](https://technet.microsoft.com/en-us/library/jj839697\(v=ax.60\))

[(RUS) Deferrals counting journal line (form)](https://technet.microsoft.com/en-us/library/jj841094\(v=ax.60\))

[(RUS) Deferrals (form)](https://technet.microsoft.com/en-us/library/jj923560\(v=ax.60\))

[(RUS) Deferrals models (form)](https://technet.microsoft.com/en-us/library/jj678655\(v=ax.60\))

[(RUS) Deferrals transactions (form)](https://technet.microsoft.com/en-us/library/jj678472\(v=ax.60\))

  


