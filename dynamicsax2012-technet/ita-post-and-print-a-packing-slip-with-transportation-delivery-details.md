---
title: (ITA) Post and print a packing slip with transportation delivery details
TOCTitle: (ITA) Post and print a packing slip with transportation delivery details
ms:assetid: d2074768-636d-4f9d-8e11-f7db7609ef23
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242922(v=AX.60)
ms:contentKeyID: 36059503
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Italy
- packing slip
- Transportation delivery
---

# (ITA) Post and print a packing slip with transportation delivery details 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you ship goods to customers, the shipment must contain a transportation delivery document (TDD). The TDD provides information about the customer, contractor, owner, and loader involved in the shipment. To print a packing slip with transportation delivery details, you must first set up transportation delivery details.

## Set up transportation delivery details

To print the transportation document and shipping information on a packing slip, you must set up the transportation delivery details in the **Accounts receivable parameters** and **Form setup** forms.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click the **Shipments** link, and then in the **Carrier name** field, select the name of the carrier for the customer shipment.

3.  Select the **Use transportation document information on packing slip** check box to display the transportation details on the packing slip when it is posted.

4.  Close the form to save your changes.

5.  Click **Accounts receivable** \> **Setup** \> **Forms** \> **Form setup**.

6.  Click the **Packing slip** link, and then select the **Shipping details** check box to print shipping information, including the carrier details, on the packing slip.

7.  Select the **Transportation document** check box to print the transportation document details on the packing slip.
    

    > [!NOTE]
    > <P>This check box is available only if the <STRONG>Use transportation document information on packing slip</STRONG> check box is selected in the <STRONG>Accounts receivable parameters</STRONG> form.</P>



8.  Close the form to save your changes.

## Post and print a packing slip with transportation delivery details

You can post and print a packing slip with a TDD for a customer shipment. The TDD will contain the following details:

  - The name and primary address of the shipping contractor.

  - The name and primary address of the shipment loader.

  - The name and primary address of the owner of the goods.

  - Any additional declarations, notes, or instructions.

  - The name of the individual who created the packing slip.

If the details of the contractor, loader, owner, and compiler are not set in the **Packing slip posting** form, the name and address of the legal entity are printed on the packing slip.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select an open sales order, and then click **Pick and pack** \> **Packing slip** to open the **Packing slip posting** form. For more information, see [Sales posting (form)](https://technet.microsoft.com/en-us/library/aa550287\(v=ax.60\)).

3.  On the **Parameters** tab, in the **Quantity** field, select **All**.

4.  Select the **Posting** check box to post the packing slip.

5.  Select the **Print packing slip** check box to print the packing slip when it is posted.

6.  Click the **Bill of lading** tab, and then in the **Carrier name** field, select the name of the carrier.

7.  Click the **Transportation document** tab. In the **Compiler** field, apply the filter to sort the compiler names, and then select the name of the person who created the packing slip.

8.  In the **Contractor**, **Loader**, and **Owner** fields, select the type of party as **Carrier**, **Legal entities**, **Customer**, or **Vendor** to filter the transportation party, and then select the name for each party.

9.  In the **Additional declarations**, **Additional notes**, and **Additional instructions** fields, enter any additional information to be printed on the packing slip.

10. Click **OK** to post and print the packing slip with the transportation document information.

11. Close the form to save your changes.

## See also

[Form setup (form)](https://technet.microsoft.com/en-us/library/aa589956\(v=ax.60\))

[Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\))

[Sales posting (form)](https://technet.microsoft.com/en-us/library/aa550287\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

