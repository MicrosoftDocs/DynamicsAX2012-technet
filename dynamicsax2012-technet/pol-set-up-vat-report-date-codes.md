---
title: (POL) Set up VAT report date codes
TOCTitle: (POL) Set up VAT report date codes
ms:assetid: 1d6386e8-8643-481f-ad56-baabd102a220
ms:mtpsurl: https://technet.microsoft.com/library/JJ678146(v=AX.60)
ms:contentKeyID: 49386869
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Set up VAT report date codes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Value-added tax (VAT) transactions are selected for the VAT register report based on the date of the VAT register. The VAT register date is specified according to business and tax rules. In Microsoft Dynamics AX, the VAT register date is based on the VAT codes that you define.

You can define the setup for the VAT register date in the **VAT report date codes** form.

The VAT date code can be selected in the **Customers** and **Vendors** forms. When you generate a sales order or purchase order for a customer or vendor, the value in the VAT code field is also used in the **Sales order**, **Free text invoice**, and **Purchase order** forms. When you post an invoice, this value is transferred to the **Invoice posting** form.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **VAT report date codes**. Click **New** to create a new line.

2.  In the **VAT report date code** field, enter an identification code for the VAT report.

3.  In the **Description** field, enter the description of the VAT code.

4.  In the **Include in VAT report** field, select the method to use for VAT reporting. Select one of the following options:
    
      - **With VAT report date** – The whole amount of the invoice is shown on the report if the calculated date in the **Date of VAT register** field in the **Invoice posting** form is in the date interval of the report.
    
      - **With VAT report date not later than** – The whole invoice amount is shown on the report if the date in the **Date of VAT register** field is in the date interval of the report. The date is calculated based on the information in the **Counted from** and **Number of days** fields.
    
      - **With date of physical payment** – If you select the **Partial settlements** check box, the settled part of the invoice amount is shown on the report if the reporting interval includes the payment dates.
        
        If the **Partial settlements** check box is not selected, the invoice amount is not shown on the report until the invoice is completely settled.
    
      - **With date of physical payment not later than** – If you select the **Partial settlements** check box, settlements that occur in the date interval for the report are shown. If the calculated value in the **Date of VAT register** field is in the report date interval, the whole invoice amount, except the settled amounts for the previous period, are shown on the report.
        
        If the **Partial settlements** check box is not selected, select **Transaction date** or **VAT date** in the **Counted from** field to specify the criterion that is used to calculate the date of the VAT register.

5.  If you want the value in the **Date of VAT register** field to equal the value in the **Due date** field in the **Invoice posting** form, select the **VAT date is the same as payment date** check box.

6.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

7.  Open the customer or vendor record to select the VAT report date code.

8.  On the **Invoice and delivery** FastTab, in the **VAT report date code** field, select the VAT code.

## See also

[(POL) VAT report date codes (form)](https://technet.microsoft.com/library/jj678227\(v=ax.60\))

[(POL) Sales orders (modified form)](https://technet.microsoft.com/library/jj678144\(v=ax.60\))

  


