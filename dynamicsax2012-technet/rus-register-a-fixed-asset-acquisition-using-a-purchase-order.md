---
title: (RUS) Register a fixed asset acquisition using a purchase order
TOCTitle: (RUS) Register a fixed asset acquisition using a purchase order
ms:assetid: b56fb8c8-1d33-4cfe-8905-fc36bb6f73c6
ms:mtpsurl: https://technet.microsoft.com/library/JJ711538(v=AX.60)
ms:contentKeyID: 49387863
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Register a fixed asset acquisition using a purchase order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can record the purchase of a fixed asset by creating a purchase order.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Press CTRL+N to create a new item in the fixed assets item group.
    

    > [!NOTE]
    > <P>For more information, see "Create an item" in the Applications and Business Processes Help.</P>



3.  In the **Item type** field, select **Fixed assets**, and then click the **General** tab.

4.  In the **FA group** field, select the fixed asset group.
    

    > [!NOTE]
    > <P>The information provided on the purchase line determines whether the fixed asset belongs to the specified fixed asset group.</P>



5.  Press CTRL+S or close the form.

6.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

7.  Press CTRL+N to create a new line.
    

    > [!NOTE]
    > <P>For more information, see "Create a purchase order" in the Applications and Business Processes Help.</P>



8.  Click the **Lines** tab in the lower pane.

9.  In the **Item number** field, select the fixed asset item number, and then click the **General** tab.

10. In the **FA number** field, select the fixed asset number.
    

    > [!NOTE]
    > <P>If the <STRONG>Association with warehouse</STRONG> check box in the <STRONG>Fixed Assets Parameters</STRONG> form is selected, you can enter only one fixed asset on each purchase line.</P>
    > <P>If the <STRONG>Association with warehouse</STRONG> check box is not selected, several purchases can be recorded on a purchase line. The number of fixed assets included on the purchase line must correspond to the fixed asset numbers in the <STRONG>FA number</STRONG> field. Even though one item might correspond to several fixed assets or inventory assets, records must be set up for each individual asset.</P>



11. In the **FA number** field, select the fixed asset number.
    

    > [!NOTE]
    > <P>If the fixed asset number is not created, then press CTRL+ALT+F4 to create a new fixed asset line in the <STRONG>Fixed assets</STRONG> form.</P>



12. Click **Posting** \> **Invoice** to post the purchase order invoice and generate vendor and ledger transactions.
    

    > [!NOTE]
    > <P>The invoice details are displayed in the <STRONG>Fixed assets</STRONG> form. The status is displayed as <STRONG>Bought</STRONG> in the <STRONG>Status</STRONG> field. If the fixed asset number is specified in the purchase order line, the purchase order must be posted or deleted in order create an asset or inventory transaction.</P>



## See also

[(RUS) Fixed asset parameters (form)](https://technet.microsoft.com/library/jj721462\(v=ax.60\))

[(RUS) Purchase orders (modified form)](https://technet.microsoft.com/library/jj733294\(v=ax.60\))

  


