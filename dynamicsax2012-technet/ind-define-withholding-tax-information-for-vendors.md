---
title: (IND) Define withholding tax information for vendors
TOCTitle: (IND) Define withholding tax information for vendors
ms:assetid: c1bfad9a-3ad6-4245-8054-0d33cfbba163
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664873(v=AX.60)
ms:contentKeyID: 49386203
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Define withholding tax information for vendors [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up withholding taxes in the form of tax deducted at source (TDS), permanent account numbers (PAN), and tax account numbers (TAN) for vendors.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Open the vendor record that you want to modify or, on the **Action Pane**, on the **Vendor** tab, in the **New** group, click **Vendor** to create a new vendor record.

2.  If you created a new vendor record, enter the required information. For more information, see [Vendors (form)](https://technet.microsoft.com/en-us/library/aa592162\(v=ax.60\))

3.  On the **Invoice and delivery** FastTab, select the **Calculate withholding tax** check box to calculate withholding tax for the vendor.

4.  In the **Withholding tax group** field, enter the default withholding tax group to use in vendor transaction payment journals.

5.  On the **Tax information** FastTab, in the **Status** field, select the status of the Permanent Account Number (PAN) for the vendor. The following options are available:
    
      - **Not available** – The vendor does not have a PAN.
    
      - **Received** – You have received a valid PAN from the vendor.
    
      - **Applied** – The vendor has applied for a PAN.
    
      - **Invalid** – You have received a PAN from the vendor, but it is not valid.

6.  If the PAN status is **Received**, enter the PAN in the **Number** field.

7.  If the PAN status is **Applied**, enter the reference number in the **Reference number** field.

8.  In the **Nature of assessee** field, select the nature of assessee category that the vendor belongs to.

9.  On the **Addresses** FastTab, select the address for which you are assigning a tax account number, and then click **More options** \> **Advanced**.

10. In the **Manage addresses** form, on the **Tax registration** FastTab, in the **Withholding tax** field group, select the tax account number for the selected address.
    

    > [!NOTE]
    > <P>This field displays the TAN or withholding tax code that is created for the vendor's registration number type in the <STRONG>Enterprise tax registration numbers</STRONG> form.</P>



## See also

[(IND) Vendors (modified form)](https://technet.microsoft.com/en-us/library/jj664890\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

