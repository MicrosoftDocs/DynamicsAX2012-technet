---
title: (RUS) Set up a dimension group
TOCTitle: (RUS) Set up a dimension group
ms:assetid: 7b63fc27-8289-497b-ba2e-8216b9bf584d
ms:mtpsurl: https://technet.microsoft.com/library/JJ923547(v=AX.60)
ms:contentKeyID: 52075395
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a dimension group 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up a dimension group for each translation group. You can use the **Dimension groups** form to set up rules for the translation of dimensions from the source company to the target company. A separate rule group is created for converting dimensions for each translation group. A set of dimension conversion options is then determined for this group.

1.  Click **General ledger** \> **Setup** \> **Translation** \> **Dimension groups**.

2.  In the **Rule group** field, select the translation group that the dimension conversion rules are set up for.
    

    > [!NOTE]
    > <P>You can set several conversion rules for one translation group.</P>



3.  In the right pane, in the **Dimension group** field, enter a unique dimension group code.

4.  In the **Description** field, enter a text description for the dimension group.

5.  On the **Rules for dimensions** FastTab, click **Add** to create a new line.

6.  In the **Dimension** field, select the dimension type for the source company that the conversion rule is being configured for.

7.  In the **From dimension code** and **To dimension code** fields, select the first and last value for the interval to set the dimension value interval.

8.  In the **Conversion method** field, select one of the following methods, according to which the translated transaction for the source company is converted:
    
      - **No changes** – The current dimension is transferred without changes.
    
      - **Company code** – The current dimension is changed to the source company code.
    
      - **Value** – The current dimension is replaced with the value that is entered by the customer or vendor.
    
      - **Customer/Vendor** – The current dimension is replaced with the customer or vendor code.

9.  In the **To dimension** field, select the dimension type from the list for the target company that the values are being transferred to.

10. In the **To dimension code** field, select the target company code that the source company transaction dimension is to be moved to during translation.
    

    > [!NOTE]
    > <P>This field is enabled only when you select <STRONG>Value</STRONG> in the <STRONG>Conversion method</STRONG> field.</P>



## See also

[(RUS) Dimension groups (form)](https://technet.microsoft.com/library/jj681876\(v=ax.60\))

  


