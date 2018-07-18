---
title: (JPN) Set up a consolidated invoice for a vendor
TOCTitle: (JPN) Set up a consolidated invoice for a vendor
ms:assetid: 491e16a5-2d73-46b9-b87d-438548bc5c87
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711044(v=AX.60)
ms:contentKeyID: 49386455
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- consolidation
- JPN
- (JPN) Set up the consolidation date for a vendor
audience: Application User
ms.search.region: Japan
---

# (JPN) Set up a consolidated invoice for a vendor 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can consolidate multiple purchase orders into one invoice, based on a consolidation date that is specified in the **Vendors** form. You can also set up holiday due date control, the cutoff day for consolidation, and the number sequence for consolidation invoices. For more information, see [Vendors (form)](https://technet.microsoft.com/en-us/library/aa592162\(v=ax.60\)).

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click the **General** link, and then select the **Consolidated invoice for vendor** check box.

3.  In the **Holiday due date control** field, select the option to use if the calculated due date falls on a holiday:
    
      - **Following day** – Set the due date to the next business day.
    
      - **Previous day** – Set the due date to the previous business day.
        

        > [!NOTE]
        > <P>This field is available only if you select the <STRONG>Use holiday calendar</STRONG> check box in the <STRONG>Legal entities</STRONG> form. For more information, see</P>



4.  Select the **Use cut-off day** check box to use the cutoff day to calculate the due date.

5.  Click the **Number sequences** FastTab.

6.  In the **Number sequence code** field, select the number sequence code for the **Consolidation ID** reference.

7.  Close the form.

8.  Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**. On the **All vendors** list page, double-click a vendor account.

9.  In the **Vendors** form, click the **Payment** FastTab.

10. In the **Consolidation day** field, enter the date when you want the invoices to be consolidated. You can enter a numeric value between 1 and 31. If the last day of the month falls on a date that has a number that is less than the numeric value that you have specified, the invoices are consolidated on the last business day of the month. For example, if you specify 31 for the consolidation date, and the current month has fewer than 31 days, the invoices are consolidated on the last business day of that month. Therefore, the invoices for April 2012 would be consolidated on April 30, 2012, because that is the last business day of the month. If the consolidation date is set to 0 (zero), the vendor’s invoices will not be consolidated.
    

    > [!NOTE]
    > <P>This field is available only if you select the <STRONG>Consolidated invoice for vendor</STRONG> check box in the <STRONG>Accounts payable parameters</STRONG> form.</P>



11. Close the forms.

## See also

[(JPN) Set up the terms of payment and the cutoff day for a vendor](jpn-set-up-the-terms-of-payment-and-the-cutoff-day-for-a-vendor.md)

[(JPN) Mark purchase invoices for consolidation and calculate due dates](jpn-mark-purchase-invoices-for-consolidation-and-calculate-due-dates.md)

[(JPN) About consolidating invoices](jpn-about-consolidating-invoices.md)

[(JPN) Accounts payable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj710993\(v=ax.60\))

  


