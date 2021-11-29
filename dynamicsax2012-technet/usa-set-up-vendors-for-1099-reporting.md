---
title: (USA) Set up vendors for 1099 reporting
TOCTitle: (USA) Set up vendors for 1099 reporting
ms:assetid: ea66f8ce-1d0e-441a-a65c-90a4a3139f12
ms:mtpsurl: https://technet.microsoft.com/library/Aa551492(v=AX.60)
ms:contentKeyID: 36059851
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: USA
---

# (USA) Set up vendors for 1099 reporting 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you post vendor transactions, set up 1099 information for each vendor who receives a 1099 statement. See [(USA) About year-end 1099 reporting](usa-about-year-end-1099-reporting.md) for more information.


> [!NOTE]
> <P>We recommend that you review Internal Revenue Service (IRS) rule changes for the applicable tax year before you set up and process 1099 statements.</P>



1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  Double-click a vendor account, and then click the **Tax 1099** FastTab.

3.  Select the **Report 1099** check box to include transaction and 1099 information for the vendor on the 1099 report. If this check box is not selected, 1099 information for the vendor is not included on the 1099 report, and the electronic or magnetic files do not include amounts for the vendor.

4.  In the **Federal tax ID** field, enter the taxpayer identification number for the vendor. In the **Tax ID type** field, select the type of tax ID that you used in the **Federal tax ID** field.

5.  In the **1099 box** field, enter the default value that appears on each transaction line that is created for the vendor. You must do this to include transactions for the vendor on the 1099 report and in electronic or magnetic media files.

6.  Select the **Foreign entity indicator** check box if the vendor organization is owned by an entity outside the United States.

7.  Select the **Second TIN** check box if your organization has been notified two times in three calendar years that the vendor provided an incorrect name.

8.  In the **Name to use on the 1099** field, select **Vendor name**. You can select **Doing business as** if a doing-business-as (DBA) name is available. If you select **Doing business as**, enter the alternate name in the **DBA** field.

9.  In the **Name control** field, enter the alphanumeric name control ID that the IRS requires to be printed on the mailing label to help validate the vendor’s Employer Identification Number (EIN).

10. Select the **CUSIP** check box to indicate that the Committee on Uniform Security Identification Procedures (CUSIP) identification number applies for the debt instrument.

11. In the **CUSIP ID** field, enter the nine-character alphanumeric CUSIP number to identify the debt instrument.

12. In the **CUSIP details** field, enter the abbreviation of the stock exchange and issuer, coupon rate, and year of maturity.
    

    > [!NOTE]
    > <P>You can enter the CUSIP details only if the <STRONG>CUSIP</STRONG> check box is not selected.</P>



13. In the **Nominee details** field, enter the names of the nominee and issuer.

14. In the **Investor type** field, select the type of investor from the following options:
    
    1.  **None**
    
    2.  **Owner** – The owner of the debt instrument.
    
    3.  **Nominee/broker** – A broker who represents the owner of the debt instrument.

15. On the **Action Pane**, on the **Vendor** tab, click **Vendor state tax IDs**.

16. Create a record for each state in which the vendor receives payments from your organization. Enter the state tax ID and, if tax identification information is available, select the tax ID type.

17. If local income tax was withheld during the year, select the **Local income tax withheld** check box.

18. Close the forms to save your changes.

## See also

[(USA) Form 1099 checklist](usa-form-1099-checklist.md)

[Vendors (form)](https://technet.microsoft.com/library/aa592162\(v=ax.60\))

[Vendor transactions (form)](https://technet.microsoft.com/library/aa572427\(v=ax.60\))

  


