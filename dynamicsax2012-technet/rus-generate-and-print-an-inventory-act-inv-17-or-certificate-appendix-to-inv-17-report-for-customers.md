---
title: (RUS) Generate and print an Inventory act (INV-17) or Certificate (Appendix to INV-17) report for customers
TOCTitle: (RUS) Generate and print an Inventory act (INV-17) or Certificate (Appendix to INV-17) report for customers
ms:assetid: f8f96e8d-b58a-45b4-a363-3411f73619e2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678645(v=AX.60)
ms:contentKeyID: 49388127
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Generate and print an Inventory act (INV-17) or Certificate (Appendix to INV-17) report for customers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The inventory data is collected from the **Accounts receivable inventory act** register by using the **Counting act** form that is displayed in the **Account receivable counting lines** form under the following conditions:

  - If an approved register already exists on the inventory start date and the period of the approved register is after the period that includes the inventory start date, data from the register is displayed in the **Account receivable counting lines** form.

  - If non-approved registers exist on the inventory start date and the period of the register is after the period that includes the inventory start date, the registers will be recalculated.

  - If there is no approved journal on the inventory start date, a new journal will be created in the **Tax register journal** form and the registers will be calculated.

  - If there is no approved journal but the period of the existing non-approved journal is not after the inventory start date, then it is not possible to calculate the register. You must delete the existing tax register journal manually.

Before you create and generate the inventory act report, you must set up the debt intervals and set up the **Accounts receivable inventory act** register.


> [!NOTE]
> <P>For more information, see <A href="rus-set-up-the-debt-interval-in-accounts-receivable.md">(RUS) Set up the debt interval in Accounts receivable</A>, <A href="rus-set-up-a-register-for-the-accounts-receivable-inventory-act.md">(RUS) Set up a register for the accounts receivable inventory act</A> , <A href="rus-calculate-the-accounts-receivable-inventory-act-register.md">(RUS) Calculate the accounts receivable inventory act register</A> and <A href="rus-create-a-tax-register-journal.md">(RUS) Create a tax register journal</A>.</P>



1.  Click Click **Accounts payable** \> **Periodic** \> **Account payable counting**.

2.  In the **Counting date** field, select the inventory date.
    

    > [!NOTE]
    > <P>The current date is displayed by default.</P>



3.  Select the **Contracts** check box to sort the lines by contract, with a total sum for each contract.

4.  Select the **Documents** check box to sort the lines by customer or vendor, with a total sum for each customer or vendor.
    

    > [!NOTE]
    > <P>If you select both the <STRONG>Contracts</STRONG> and <STRONG>Documents</STRONG> check boxes, the lines are sorted first by contract with totals, and then by vendor or customer with totals. If you do not select both check boxes, the lines are sorted by transaction date with an overall total.</P>



5.  Click **OK** to open the **Counting act** dialog box.

6.  Click **Yes** in the **Counting act** dialog box to open the **Account receivable counting lines** form to view the inventory data collected from the **Accounts receivable inventory act** register.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/en-us/library/jj841092(v=ax.60)">(RUS) Account receivable counting lines (form)</A>.</P>



7.  In the **Non-confirmed debt** field, enter the non-confirmed debt.
    

    > [!NOTE]
    > <P>The non-confirmed debt amount is updated automatically in the <STRONG>Non-confirmed debt</STRONG> field in the <STRONG>Register lines</STRONG> form of the <STRONG>Accounts receivable inventory act</STRONG> register. This field is editable only if the <STRONG>Contracts</STRONG> and <STRONG>Documents</STRONG> check boxes are not selected in the <STRONG>Counting act</STRONG> form.</P>



8.  Click **Original document** to open the original document for the transaction.

9.  Click **Print** \> **Counting act (INV-17)** to open the **Print Counting act** form for **Counting act (INV-17)**.
    
    –or–
    
    Click **Print** \> **Certificate (Appendix to INV-17)** to open the **Print Counting act** form for **Certificate (Appendix to INV-17)**.

10. In the **Counting date** field, select the inventory date.

11. In the **Document** field, enter the document number which identifies the reason for the inventory.

12. On the **Officials** tab, and in the **Position** field, select the position title of the official.

13. In the **Title** field, select the job title of the official.

14. In the **Employee name** field, select the name of the official from the list of company employees.

15. Click **OK** to print the **Counting act (INV-17)** or **Certificate (Appendix to INV-17)** report.

## See also

[(RUS) Counting act (form)](https://technet.microsoft.com/en-us/library/jj665262\(v=ax.60\))

[(RUS) Account receivable counting lines (form)](https://technet.microsoft.com/en-us/library/jj841092\(v=ax.60\))

[(RUS) Print counting act (form)](https://technet.microsoft.com/en-us/library/jj839668\(v=ax.60\))

[(RUS) Debt interval (form)](https://technet.microsoft.com/en-us/library/jj853236\(v=ax.60\))

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Tax register journal (form)](https://technet.microsoft.com/en-us/library/jj856114\(v=ax.60\))

[(RUS) Register journal lines (form)](https://technet.microsoft.com/en-us/library/jj839663\(v=ax.60\))

[(RUS) Register lines (form)](https://technet.microsoft.com/en-us/library/jj943751\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

