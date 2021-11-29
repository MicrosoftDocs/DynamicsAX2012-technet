---
title: (IND) Set up EXIM authorization schemes for DFIA
TOCTitle: (IND) Set up EXIM authorization schemes for DFIA
ms:assetid: 567b574c-4f40-4e4b-8557-1cd0de57109e
ms:mtpsurl: https://technet.microsoft.com/library/JJ677824(v=AX.60)
ms:contentKeyID: 49385787
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- EXIM
- DFIA
- EXIM authorization scheme
- Duty Free Import Authorization
audience: Application User
ms.search.region: India
---

# (IND) Set up EXIM authorization schemes for DFIA 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you enable the Duty Free Import Authorization (DFIA) incentive scheme and set up the tax ledger posting groups that are attached to individual indirect tax codes, set up the details for the DFIA scheme by using the **EXIM Authorization schemes** form.

1.  Click **General ledger** \> **Common** \> **EXIM Authorization schemes**. On the **EXIM Authorization schemes** list page, on the **Action Pane**, in the **New** group, click **EXIM Authorization schemes**.

2.  In the **EXIM Authorization schemes** form, in the **Authorization type** field, select **DFIA**.
    

    > [!NOTE]
    > <P>The options that are available depend on the settings in the <STRONG>Incentive scheme parameters</STRONG> form.</P>
    > <UL>
    > <LI>
    > <P>If the <STRONG>Advance Authorization</STRONG> check box is selected, but the <STRONG>Duty Free Import Authorization</STRONG> check box is cleared, the <STRONG>Authorization type</STRONG> field displays <STRONG>AA</STRONG>. To continue setting up a DFIA scheme, you must first enable the scheme in the <STRONG>Incentive scheme parameters</STRONG> form. For more information, see <A href="ind-set-up-incentive-scheme-parameters-for-dfia.md">(IND) Set up incentive scheme parameters for DFIA</A>.</P>
    > <LI>
    > <P>If the <STRONG>Duty Free Import Authorization</STRONG> check box is selected, but the <STRONG>Advance Authorization</STRONG> check box is cleared, the <STRONG>Authorization type</STRONG> field displays <STRONG>DFIA</STRONG>.</P>
    > <LI>
    > <P>If both the <STRONG>Advance Authorization</STRONG> and the <STRONG>Duty Free Import Authorization</STRONG> check boxes are selected, the <STRONG>Authorization type</STRONG> field first displays <STRONG>AA</STRONG>, but you can select <STRONG>DFIA</STRONG>.</P></LI></UL>



3.  Click **New**. The **Authorization ID** and **Date/Time** fields for the new scheme automatically display the authorization number of the license scheme and the date and time when the authorization was created.
    

    > [!NOTE]
    > <P>The authorization number is created automatically, based on the number sequence specified on the <STRONG>Number sequences</STRONG> tab in the <STRONG>Incentive scheme parameters</STRONG> form.</P>



4.  In the **Product group** field, select the product group that applies to the scheme.

5.  In the **Port ID** field, select the name of the EXIM port.

6.  In the **Authorization basis** field, select one of the following options:
    
      - **Confirmed orders** – Select this option to base your application on confirmed orders from your customers. For more information, see [(IND) Create EXIM authorization schemes for confirmed sales orders](ind-create-exim-authorization-schemes-for-confirmed-sales-orders.md).
    
      - **Export orders** – Select this option to base your application on your export orders, if you are eligible to do this. For more information, see [(IND) Create EXIM authorization schemes for export orders](ind-create-exim-authorization-schemes-for-export-orders.md).
    
      - **Purchase** – Select this option to indicate that you purchased the license on the open market. For more information, see [(IND) Record the purchase of a DFIA or AA license](ind-record-the-purchase-of-a-dfia-or-aa-license.md). This option is available only if the **Allow purchase** check box is selected in the **Incentive scheme parameters** form.
    
    The **Annual consumption** option does not apply to DFIA.

7.  Click the **Lines** FastTab. The **Text** field displays information that was entered in the **Authorization purchase details** or **Authorization sale details** form.
    
    This field is available only if the **Allow purchase** or **Allow sale** check box is selected in the **Incentive scheme parameters** form. You can change the information in this field in some cases, such as when you purchase or sell a license.


> [!NOTE]
> <P>If you purchased the license on the open market, the <STRONG>Authorization basis</STRONG> field displays <STRONG>Purchase</STRONG>, and the <STRONG>Purchase value</STRONG> field displays the purchase value of the license.</P>
> <P>If you sold the license on the open market, the <STRONG>License status</STRONG> field displays <STRONG>Sold</STRONG>, and the <STRONG>Sale value</STRONG> field displays the sale value of the license.</P>



## See also

[(IND) EXIM Authorization schemes (form)](https://technet.microsoft.com/library/jj664625\(v=ax.60\))

[(IND) Incentive scheme parameters (form)](https://technet.microsoft.com/library/jj677946\(v=ax.60\))

  


