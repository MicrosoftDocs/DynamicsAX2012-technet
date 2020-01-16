---
title: (IND) Enter the authorization approval details for DFIA
TOCTitle: (IND) Enter the authorization approval details for DFIA
ms:assetid: de12cc62-5cad-4cdf-98c9-26121af7136f
ms:mtpsurl: https://technet.microsoft.com/library/JJ710887(v=AX.60)
ms:contentKeyID: 49386300
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- approval
- (IND)
- India
- DFIA
- authorization approval
audience: Application User
ms.search.region: India
---

# (IND) Enter the authorization approval details for DFIA 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After the customs authority approves your application for a Duty Free Import Authorization (DFIA) and issues an authorization number for it, use this procedure to enter the approval details into Microsoft Dynamics AX.

1.  Click **General ledger** \> **Common** \> **EXIM Authorization schemes**.

2.  In the **EXIM Authorization schemes** list, in the **Authorization type** field, select **DFIA**. All records that were created for the authorization type DFIA appear in the grid.

3.  Select the relevant authorization, and then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

4.  In the **EXIM Authorization schemes** form, on the **Overview** FastTab, click **Functions**, and then click **Approve**.
    

    > [!NOTE]
    > <P>The <STRONG>Approve</STRONG> option is available only when the status of the authorization is <STRONG>Applied</STRONG>.</P>



5.  In the **Authorization approval details** form, on the **Authorization information** FastTab, do the following:
    
    1.  Enter the authorization identification number and the issue date.
    
    2.  Select the **Transferable** check box, if the authorization is transferable.
    
    3.  In the **Import assessable value** field, enter the allowed cost, insurance, and freight (CIF) value for the authorization.
    
    4.  In the **Import expiration date** field, enter the expiration date for applying the incentive scheme to imports.
    
    5.  In the **Export assessable value** field, enter the allowed Free On Board (FOB) value for the authorization.
    
    6.  In the **Export expiration date** field, enter the expiration date of the export obligation for the authorization.

6.  On the **Tax information** FastTab, do the following:
    
    1.  In the **Tax ledger posting group** field, select the tax ledger posting group that you want to post the taxes to. The tax ledger posting group must have a tax type of **Customs**. The tax type is specified in the **Tax ledger posting groups** form.
    
    2.  In the **IEC number** field, select the importer-exporter code (IEC) number for the company.
    
    3.  In the **Transaction date** field, select the date on which to post the voucher for the authorization to the ledger.
    
    4.  On the **Tax** tab, press CTRL+N, and then, in the **Tax component** field, select the tax component to specify where the exempt tax amount is posted. The ledger account that is selected in the **DFIA receivable account** field in the **Tax ledger posting groups** form appears in the **Ledger account** field.
    
    5.  In the **Amount** field, enter the exempt duty amount in the default currency. The amount is posted to the DFIA receivable account that appears in the **Ledger account** field.
    
    6.  In the **Offset account** field, select the offset account to post the exempt duty amount to. The default account is the account that is selected in the **Benefit account** field in the **Incentive scheme parameters** form. You can change the offset account if you need to.
    
    7.  In the **Tax code** field, select the tax code for the exempt duty amount.

## See also

[(IND) Authorization approval details (form)](https://technet.microsoft.com/library/jj677814\(v=ax.60\))

[(IND) Set up EXIM authorization schemes for DFIA](ind-set-up-exim-authorization-schemes-for-dfia.md)

  


