---
title: (USA) About year-end 1099 reporting
TOCTitle: (USA) About year-end 1099 reporting
ms:assetid: 56f8df2e-6a13-4967-9454-adf0316abaff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242471(v=AX.60)
ms:contentKeyID: 36057326
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- 1099 transmitter
- Electronic and magnetic filing
---

# (USA) About year-end 1099 reporting [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you do business with vendors that are subject to United States 1099 tax, you must track the amount that you pay to each vendor and report that information to the U.S. tax authorities at the end of the calendar year. The vendors are typically individuals who are not employees and who provide services to your organization. You must also send a statement to each 1099 vendor that you do business with, informing them of the amount that you are reporting to the tax authorities.

For each vendor that you have set up to be a 1099 vendor, the amounts are tracked within Microsoft Dynamics AX throughout the year. On invoice lines, you use the **1099 box** and **1099 amount** fields to track 1099 amounts. Even if you do not enter a value in the **1099 amount** field, any payment that is posted for the invoice amount contributes to the 1099 total for the specified 1099 box. If you do enter a 1099 amount, the amount that you entered is used instead of the posted payment amount.

After you post a payment, you can modify any 1099 amount using the **Tax 1099 transactions** form. Some invoice lines for a vendor might need 1099 tracking whereas others do not. You can clear the **1099 box** field for any invoice line that needs no 1099 tracking.

If you set up a 1099 vendor during the calendar year after you have already processed transactions for that vendor, you can update the previous transactions to be 1099 transactions. Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. select a vendor, and then click **List** \> **Update 1099** to update transactions. This calculates 1099 amounts for paid invoices that are in the specified date range, according to the settings on the **Tax 1099** tab in the **Vendors** form.


> [!NOTE]
> <P>You can run the process to update 1099 amounts for only one vendor at a time.</P>



We recommend that you review IRS rule changes for the applicable tax year before you set up and process 1099 statements.

When you are ready to process 1099 statements, use the **Tax 1099 summary** form (Click **Accounts payable** \> **Periodic** \> **Vendor settlement for 1099s**.) See [(USA) Vendor settlement for 1099s (form)](https://technet.microsoft.com/en-us/library/aa582697\(v=ax.60\)) for more information.

## Example of a typical year-end 1099 process

You might follow these steps to generate either an export file or a printed 1099 statement to send to the vendor, IRS, or tax firm that transmits the 1099 forms to the IRS on behalf of your organization.

1.  Click **Accounts payable** \> **Setup** \> **Tax 1099** \> **1099 fields**. Then verify the minimum amounts that are required for 1099 reporting for the current tax year.

2.  Print a **Tax 1099 summary** report and a **Tax 1099 detail report** (**Accounts payable** \> **Reports** \> **Tax 1099**) to review vendor information and locate any vendors who might need changes.
    

    > [!NOTE]
    > <P>To minimize the amount of data that you see, you can click <STRONG>Select</STRONG> to apply a filter.</P>

    
    If you view a report and notice a problem, you can fix it.
    
    **Example**
    
    Because of a new tax regulation, you notice that a 1099-G form is not required for a vendor.
    
      - If the 1099-G form is the only 1099 tax form that the vendor will receive, you can clear the **Report 1099** check box in the **Vendors** form so the vendor will not receive any 1099 forms.
    
      - Click **Accounts payable** \> **Periodic** \> **Vendor settlement for 1099s**. The **Tax 1099 transactions** form contains 1099 information from paid invoices, and you can modify that information.

3.  Click **Accounts payable** \> **Periodic** \> **Vendor settlement for 1099s**. You can print the 1099 tax information in paper form or transmit 1099 tax information by electronic or magnetic filing.
    
    After you post a payment for an invoice, the invoice amount appears in the **Tax 1099 summary** form. When totals for a box reach the amount in the **1099 fields** form, the **IRS reportable** check box is selected. After you load the printer with blank 1099 tax forms, you can print data to the form. You can also create an export file.
    

    > [!NOTE]
    > <P>If you try to create an export file and a form opens that displays validation errors, you can click <STRONG>1099 software vendor</STRONG> and <STRONG>1099 transmitter</STRONG> in the <STRONG>Tax 1099 validation errors</STRONG> form to enter missing field values. Then click <STRONG>Recheck for errors</STRONG> to revalidate the file.</P>



## Create a copy of a 1099 form

At any point during the year, a vendor might request that you provide a copy of their 1099 form. To print a copy, click **Print** in the **Tax 1099 summary** form. If a vendor asks for a list of all invoices that were included on a 1099 form, you can print the **Tax 1099 detail report**.

## About partial payments and cross-company payment settlements

If you make a partial payment for an invoice, the 1099 amount is saved to reflect the partial payment. For example, if the invoice amount is 200.00 and the 1099 amount is 50.00, and the payment is 100.00 (50 percent of the invoice), the 1099 amount that is saved is 25.00 instead of 50.00.

If an invoice is paid by another company (cross-company payment settlements), the company that makes the payments must create the 1099 statements. For more information, see [Scenario: Single-company and cross-company payment settlements](scenario-single-company-and-cross-company-payment-settlements.md).

## About 1099-G and 1099-S forms

If your organization is in the public sector, you can submit 1099-G or 1099-S forms to the IRS.


> [!NOTE]
> <P>(USA) This functionality is available only if the legal entity’s address is in the United States and the <STRONG>Public Sector 1099G</STRONG> or <STRONG>Public Sector 1099S</STRONG> configuration keys are selected.</P>



If you use these forms, the following tips provide more information:

  - An individual 1099 report is associated with each 1099-S invoice. You can use the **Tax 1099 detail report** to view detailed 1099-S information.

  - The G-2 fields are summarized by reporting year for each vendor. If you report G-2 information for more than the current reporting year, a **G-2** reporting field is displayed on the **Tax 1099 summary** report.

  - In the lines of many journals, you cannot enter an S-2 amount. This amount is the same as the **1099 amount** field. However, you can enter S-2 details on the **1099** tab in these forms. Also, you cannot select **S-5** in these forms because you must manually enter this amount in the **S-5 buyer part of real estate tax** field. Click **Accounts payable** \> **Periodic** \> **Vendor settlement for 1099s**.

## About the 1099-OID form

An original issue discount (OID) is a type of interest that is created when debt instruments, such as bonds or notes, are issued at a discount. The OID is the difference between the stated redemption price of the instrument at maturity and its original issue price. The redemption price is the face value of the bond or note, and the issue price is the amount for which the bond or note was first sold by the issuer.

An OID is treated as taxable income for the owner of the debt obligation. The issuer must report the issue of the bonds or notes to the Internal Revenue Service (IRS) using the 1099-OID form within 30 days of the date of issue. The issuer is liable for a penalty of one percent of the issue price, up to a maximum of USD 50,000, if the OID is not reported.

## See also

[(USA) Form 1099 checklist](usa-form-1099-checklist.md)

[(USA) Prerequisites for filing 1099 statements](usa-prerequisites-for-filing-1099-statements.md)

[(USA) Set up vendors for 1099 reporting](usa-set-up-vendors-for-1099-reporting.md)

[(USA) 1099 transmitter (form)](https://technet.microsoft.com/en-us/library/aa587975\(v=ax.60\))

[(USA) Post a vendor payment journal and generate a 1099 OID report](usa-post-a-vendor-payment-journal-and-generate-a-1099-oid-report.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

