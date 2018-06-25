---
title: (NOR) Set up a bank account for vendors
TOCTitle: (NOR) Set up a bank account for vendors
ms:assetid: b1b96094-92af-42ce-8a99-394f7fd7bcbb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg232397(v=AX.60)
ms:contentKeyID: 36058983
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (NOR) Set up a bank account for vendors [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
    \-or-
    
    Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor account and click **Setup** \> **Bank accounts** to open the **Vendor bank accounts** form. You can use this form to transfer payments to a vendor.

3.  Press CTRL+N to create a new bank account for the vendor.

4.  On the **General** FastTab, in the **Bank account** field, enter the identification code for the vendor bank account.

5.  In the **Bank account number** field, enter the vendor bank account number.

6.  In the **SWIFT code** field, enter the SWIFT (Society for Worldwide Inter-bank Financial Telecommunication) code or BIC (Bank Identifier Code) for the vendor’s bank. If the SWIFT code or the BIC code is not available, specify the country/region code for the receiving bank.

7.  In the **Routing number type** field, select the code that identifies the type of routing number used for international payments.

8.  In the **Routing number** field, enter the routing number of the vendor’s bank. You can specify the routing number for banks that do not have SWIFT codes.

9.  Close the forms to save your changes.

10. Click **General ledger** \> **Setup** \> **Currency** \> **Currency exchange rates**.

11. In the **Exchange rate type** field, select the exchange rate type for the currency used for the vendor payment file.

12. Press CTRL+N to create a new exchange rate for the currency.

13. In the **Start date** field, select the date to apply the exchange rate.

14. In the **Exchange rate** field, enter the exchange rate.

15. Close the form to save your changes.

16. Click **Organization administration** \> **Setup** \> **Addresses** \> **Address format** \> **Country/region**.

17. Press CTRL+N to add a new country/region.

18. In the **Country/region** field, enter the three-character ISO code for the vendor’s country/region. The ISO country/region and currency codes are used for banking transactions with vendors in other countries or regions.

19. Close the form to save your changes.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

