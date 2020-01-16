---
title: (IND) View transactions with customs duty
TOCTitle: (IND) View transactions with customs duty
ms:assetid: 01aa2aa1-36ae-48ba-bec2-af6739374621
ms:mtpsurl: https://technet.microsoft.com/library/JJ664428(v=AX.60)
ms:contentKeyID: 49385518
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) View transactions with customs duty 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Customs inquiry** form to create queries that display transactions that customs tax is calculated for. You can also use this form to run queries for details about customs tax, such as the date of issue or receipt of goods, bill of entry, import and export invoices, and the shipping bill. The **Customs** check box must be selected on the Sales tax area in the **General ledger parameters** form. (Click **General ledger** \> **Setup** \> **General ledger parameters**.)


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Customs** \> **Customs**.

2.  In the **Customs inquiry** form, select the query to modify in the **Select query** field.

3.  Click **Modify** to modify, save, or delete the current query.

4.  Select the Importer Exporter Code (IEC) number for the company's address in the **IEC number** field.

5.  Enter the tax settlement period for the selected IEC number in the **Tax settlement period** field.

6.  Select the starting date of the period in the **From date** field and the ending date in the **To date** field.

7.  Select the required fields from the **Available** list.

8.  Click **\>** to add items from the **Available** list to the **Selected** list.

9.  Click **\<** to remove items from the **Selected** list.

10. Click **Top**, **Up**, **Down**, or **Bottom** to rearrange the order of items.

11. Select or clear the **Header note** check box to indicate whether the header note must be defined and displayed, and then enter the text for the header note in the **Header note** field, if needed.

12. Select or clear the **Footer note** check box to indicate whether the footer note must be defined and displayed, and then enter the text for the footer note in the **Footer note** field, if needed.

13. Click **Inquiry** to create or update the selected query in the **Inquiry** form.
    

    > [!NOTE]
    > <P>For more information, see "Inquiry (form)" in the Applications and Business Processes Help.</P>



14. Click **Total** to select the amount fields to display in the **Total** form. Only the amount-related fields that are in the **Selected** list can be added in this form. Close the **Total** form.

15. Click **OK** to open the **Customs transactions** form, where you can view the details of the inquiry.

16. You can click **Voucher** in the **Customs transactions** form to open the **Voucher transactions** form to view ledger account details.

17. You can click **Misc. charges** in the **Customs transactions** form to view the details of the misc. charges transactions in the **Misc. charges transactions** form.

18. You can click **Totals** to view the total amount in the **Totals** - **Customs** form.

19. Click **Tax components** in the **Totals** - **Customs** form to open the **Tax components** - **Customs** form, where you can view customs duty amount information for the tax components and currency details.

20. Close the **Tax components** - **Customs** form and the **Totals** - **Customs** form.

## See also

[(IND) Customs inquiry (form)](https://technet.microsoft.com/library/jj664926\(v=ax.60\))

[(IND) Customs transactions (form)](https://technet.microsoft.com/library/jj710932\(v=ax.60\))

[(IND) Totals - Customs (form)](https://technet.microsoft.com/library/jj664748\(v=ax.60\))

[(IND) Tax components - Customs (form)](https://technet.microsoft.com/library/jj664589\(v=ax.60\))

[(IND) Bill of entry journal (form)](https://technet.microsoft.com/library/jj677988\(v=ax.60\))

  


