---
title: (IND) Record the purchase of a DFIA or AA license
TOCTitle: (IND) Record the purchase of a DFIA or AA license
ms:assetid: ccf57c51-db58-4c64-922a-b7967f7019cc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664919(v=AX.60)
ms:contentKeyID: 49386247
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- authorization
- (IND)
- India
- AA
- DFIA
- Purchase authorization
audience: Application User
ms.search.region: India
---

# (IND) Record the purchase of a DFIA or AA license 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to record a Duty Free Import Authorization (DFIA) that was purchased on the open market.


> [!NOTE]
> <P>This procedure also applies to the Advance Authorization (AA) incentive scheme for eligible purchases.</P>



1.  Click **General ledger** \> **Common** \> **EXIM Authorization schemes**.

2.  On the **EXIM Authorization schemes** list page, on the **Action Pane**, in the **New** group, click **EXIM Authorization schemes**.

3.  In the **EXIM Authorization schemes** form, in the **Authorization type** field, select **DFIA**.

4.  Click **New** to create a new DFIA authorization scheme.
    
    The identification number for the authorization scheme appears automatically in the **Authorization ID** field.
    

    > [!NOTE]
    > <P>The authorization number is generated automatically, based on the number sequence that is specified for the incentive scheme on the <STRONG>Number sequences</STRONG> tab in the <STRONG>Incentive scheme parameters</STRONG> form.</P>



5.  In the **Product group** field, select the relevant product group.

6.  In the **Port ID** field, select the port ID that applies to the scheme.

7.  In the **Authorization basis** field, select **Purchase**.
    

    > [!NOTE]
    > <P>The <STRONG>Purchase</STRONG> option appears only if the <STRONG>Allow purchase</STRONG> check box is selected in the <STRONG>DFIA</STRONG> area in the <STRONG>Incentive scheme parameters</STRONG> form.</P>



8.  Click **Functions**, and then click **Purchase** to open the **Authorization purchase details** form.

9.  On the **Authorization information** FastTab, enter the following information:
    
      - In the **Authorization number** field, enter the authorization number that was issued by the customs tax authority.
    
      - In the **Issue date** field, select the date when the authorization was issued.
    
      - Select the **Transferable** check box if you want the authorization to be transferable.
        

        > [!NOTE]
        > <P>This check box is available only if the status of the license is <STRONG>Approved</STRONG>.</P>

    
      - In the **Purchase value** field, enter the purchase value of the authorization.
    
      - In the **Text** field, enter a description or other information about the authorization.
    
      - In the **Import assessable value** field, enter the cost, insurance, and freight (CIF) value that is allowed for the authorization.
    
      - In the **Expiration date** field, select the last date on which the authorization scheme can be applied to imports.

10. At the top of the **Authorization information** FastTab, click **Importable Items**, and then do the following:
    
    1.  Click **New** to create a new line.
    
    2.  In the **Item number** field, select the number of the importable item. The item description appears in the **Product name** field, and the unit of measure appears in the **Unit** field.
    
    3.  Do one of the following:
        
          - In the **Quantity** field, enter the number of units of the item.
        
          - In the **Value** field, enter the value of the item.
    
    4.  Close the **Importable Items** form.

11. On the **Tax information** FastTab, enter the following information:
    
      - In the **Tax ledger posting group** field, select a ledger posting group that displays **Customs** in the **Tax type** column.
    
      - In the **IEC number** list, select the importer exporter code (IEC) number of the company.
    
      - In the **Transaction date** field, select the posting date of the purchase of the authorization.

12. On the **Tax** tab, press CTRL+N to create a new line.

13. In the **Tax component** field, select the tax component that is relevant to the incentive scheme.
    
    The **Ledger account** field displays the ledger account to which the duty amount that is exempt is posted.
    

    > [!NOTE]
    > <P>The association between the tax component and ledger account is maintained in the <STRONG>Tax ledger posting groups</STRONG> form.</P>



14. In the **Amount** field, enter the amount of duty that is exempt. Enter the amount in the default currency. This amount is posted to the receivable account of the selected incentive scheme.

15. In the **Offset account** field, select the offset ledger account to which the duty amount that is exempt is posted. The default account is the account that is selected for the DFIA incentive scheme in the **Incentive scheme parameters** form, in the **Benefit account** field. You can change the default account.

16. In the **Tax code** field, select the tax code for the duty amount that is exempt. Click **OK**.

17. The following message appears:
    
    **You are about to purchase the authorization license. After purchase no changes can be made to this authorization. Do you want to continue?**
    
    Click **Yes** to update the status of the license to **Approved**.
    

    > [!NOTE]
    > <P>The voucher transactions for the purchase are posted by using the number sequence for DFIA vouchers that is specified on the <STRONG>Number sequences</STRONG> tab in the <STRONG>Incentive scheme parameters</STRONG> form. The voucher is posted on the date that is specified in the <STRONG>Transaction date</STRONG> field.</P>



18. In the **EXIM Authorization schemes** form, on the **Lines** FastTab, click **Tax information**. In the **Posted tax information** form, in the **Tax ledger posting group**, **IEC number**, **Transaction date**, and **Tax component** fields, you can view details that are specified for the license.

19. Click **Voucher** to open the **Voucher transactions** form, where you can view the posted voucher entries.

20. Close the **Voucher transactions**, **Posted tax information**, and **EXIM Authorization schemes** forms.

## See also

[(IND) EXIM Authorization schemes (form)](https://technet.microsoft.com/en-us/library/jj664625\(v=ax.60\))

[(IND) Authorization purchase details (form)](https://technet.microsoft.com/en-us/library/jj664499\(v=ax.60\))

[(IND) Importable items (form)](https://technet.microsoft.com/en-us/library/jj664640\(v=ax.60\))

[(IND) Posted tax information (form)](https://technet.microsoft.com/en-us/library/jj664909\(v=ax.60\))

[(IND) Incentive scheme parameters (form)](https://technet.microsoft.com/en-us/library/jj677946\(v=ax.60\))

[(IND) Tax ledger posting groups (form)](https://technet.microsoft.com/en-us/library/jj664546\(v=ax.60\))

  


