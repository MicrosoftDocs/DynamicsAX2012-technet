---
title: Create facility agreements for the letter of guarantee
TOCTitle: Create facility agreements for the letter of guarantee
ms:assetid: b8e4fd9c-4f73-4461-a70a-e9528cea2ec1
ms:mtpsurl: https://technet.microsoft.com/library/Hh242761(v=AX.60)
ms:contentKeyID: 36059113
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Create facility agreements for the letter of guarantee
- facility agreements
audience: Application User
ms.search.region: Global
---

# Create facility agreements for the letter of guarantee 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to set up a bank facility agreement and enter letter of guarantee information. Before you set up a bank facility agreement, set up bank facility types and bank facility groups in the **Bank facilities** form.

## Set up bank facilities

1.  Click **Cash and bank management** \> **Setup** \> **Bank documents** \> **Bank facilities**.

2.  On the **Facility groups** link, press CTRL+N to create a new bank facility group.

3.  In the **Facility group** field, enter the bank facility group name for the letter of guarantee transaction.

4.  In the **Description** field, enter the description of the bank facility group.

5.  Click the **Facility types** link.

6.  Press CTRL+N to create a new bank facility type.

7.  In the **Facility type** field, enter the name of the bank facility type that is related to the bank facility agreement.

8.  In the **Description** field, enter the description of the bank facility type.

9.  In the **Facility group** field, select the bank facility group for the facility type.

10. In the **Facility nature** field, select **Letter of guarantee**.

11. Close the form to save your changes.

## Create a bank facility agreement

1.  Click **Cash and bank management** \> **Setup** \> **Bank documents** \> **Bank facility agreements**.

2.  Press CTRL+N to create a new bank document facility agreement.

3.  On the right pane, in the **Agreement number** field, enter the bank agreement number for the transaction.

4.  In the **Bank account** field, select the bank account number for which the letter of guarantee is open.

5.  In the **Start date** field, select the starting date of the bank facility agreement. You can view the currency to be used for the invoicing transaction in the **Currency** field.

6.  In the **End date** field, select the ending date of the agreement.
    

    > [!NOTE]
    > <P>Facility agreements cannot have overlapping dates. For example, if Agreement A extends from January 01, 2010 to August 31, 2010, you cannot create another facility agreement that begins or ends within that period.</P>



7.  Click the **General** FastTab, and then click **Add line** to add a bank document facility agreement line item.

8.  In the **Facility type** field, select the facility type for the bank facility agreement. Be sure that the facility nature for the selected facility type is **Letter of guarantee**.

9.  In the **Limit** field, enter the amount negotiated with the bank. The **Amount used** field displays the amount currently used for the letter of guarantee.

10. Press CTRL+S to activate the **Letter of guarantee** FastTab.

11. Enter the calculation method and percentage details for the **Cash margin**, **Issuance commission**, **Extension commission**, **Increase value commission**, or **Decrease value commission**, as appropriate.

12. Close the form to save your changes.

## See also

[Bank facility agreement details (form)](https://technet.microsoft.com/library/hh209692\(v=ax.60\))

[Letter of guarantee (form)](https://technet.microsoft.com/library/hh227662\(v=ax.60\))

[Create a letter of guarantee request for a purchase order](create-a-letter-of-guarantee-request-for-a-purchase-order.md)

[Create a letter of guarantee request for a sales order](create-a-letter-of-guarantee-request-for-a-sales-order.md)

  


