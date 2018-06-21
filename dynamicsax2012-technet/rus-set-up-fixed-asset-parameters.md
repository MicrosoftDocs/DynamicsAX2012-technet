---
title: (RUS) Set up fixed asset parameters
TOCTitle: (RUS) Set up fixed asset parameters
ms:assetid: 979c9aaf-9749-4665-9eb5-5c59c1ee537e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678510(v=AX.60)
ms:contentKeyID: 49387739
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up fixed asset parameters [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets (Russia)** \> **Setup** \> **Parameters**.

2.  In the **Base value model** and **Tax value model** fields, select the value models for accounting and tax business functions, respectively.

3.  In the **Minimal depreciation** field, enter the minimum depreciation amount when depreciating a fixed asset with the **Reducing remainder** method.

4.  Select the **Allow multiple putting into operation** check box to enter multiple acquisitions.
    

    > [!NOTE]
    > <P>If this check box is selected, you can register multiple acquisition transactions for a fixed asset. This allows you to register changes in the cost of the asset over time.</P>



5.  Select the **Require reasons for asset changes** check box if a reason must be entered to explain changes in depreciation.

6.  Select the appropriate reason codes and move them from the **Not required** list to the **Required** list.

7.  Select the **Autonumeration FA** check box to activate automatic numbering.

8.  Select the **Barcode equals FA number** check box to automatically assign bar codes for fixed asset numbers.
    

    > [!NOTE]
    > <P>If this check box is selected, a bar code number that is the same as the fixed asset number will be automatically generated for the fixed asset and displayed in the <STRONG>Fixed assets</STRONG> form.</P>



9.  Select the **Barcodes autonumeration** check box to activate automatic numbering of bar codes with a number series.
    

    > [!NOTE]
    > <P>This check box is not activated, if <STRONG>Barcode equals FA number</STRONG> check box is selected.</P>



10. In the **Round-off** field, enter the value by which transaction amounts must be rounded for accounting purposes.

11. In the **Posting profile** field, select the default posting profile to be used if no posting profile is specified for the value models.

12. In the **Language** field, select a language for the fixed asset documents.

13. In the **Reservation** field, select **Manual**, **Automatic**, or **Explosion** to specify the type of reservation of items during assembly or disassembly of a fixed asset.

14. Click the **Tax reporting** tab, and then, in the **Sales tax code** field, select values for **Assessed tax**, **Transport tax**, and **Land tax**.

15. In the **Compression** field, select the level of compression from the following options:
    
      - **Tax** – When you create a fixed asset tax journal in the ledger, the detailing of the journal lines is generated according to the tax codes.
    
      - **Total** – When you generate transactions in the fixed asset tax journal in the ledger, the total of the transactions is generated without detailing according to the tax codes.

16. On the **Document** tab in the **Document location** field, select the folder where the fixed asset documents are to be saved.

17. On the **Financial dimensions** tab, select the financial dimension codes for the fixed asset transactions.

18. On the **Document types** tab, select a number series for the various types of fixed asset documents.

19. On the **Number sequence code** tab, select a number series for the various fixed asset references, such as **FA number**, **Bar code**, **FA revaluation**, **FA inventory**, **FA transfer**, **Writing off on lifetime**, and **Assessed tax register journal number**.

20. Press CTRL+S or close the form.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

