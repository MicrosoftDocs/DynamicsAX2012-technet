---
title: (RUS) Generate the Cash Inventory Act (Inv-15) report
TOCTitle: (RUS) Generate the Cash Inventory Act (Inv-15) report
ms:assetid: 45e6e60b-b668-460d-b453-0702f4400e01
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665334(v=AX.60)
ms:contentKeyID: 49387422
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate the Cash Inventory Act (Inv-15) report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The total counted amount and the posted amount of all journals are displayed in the Cash Inventory Act (Inv-15) report. When you check the **Supplement** check box, the cash counting statement report is printed along with the additional information, such as the exchange rates, total counted amount, and total posted amount, in primary currencies.

1.  Click Click **Cash and bank management** \> **Reports** \> **External** \> **Cash counting statement**.

2.  In the **Cash** field, select a cash account code.

3.  In the **Document number** field, enter the cash counting statement number.

4.  In the **Counting date** field, select the transaction date. Whenever you select the **Cash** or **Counting date** fields, the lines in the grid are recreated.
    
    The following fields are displayed:
    
      - The **More currencies** check box is automatically selected if you selected the **More currencies** check box for cash in the **Cash accounts** form. This check box cannot be edited.
    
      - The total counted amount and the total posted amount in default currency in the grid are displayed in the **Total counted** and the **Total posted** fields in the **Totals** field group.
        

        > [!NOTE]
        > <P>Whether the cash account is in one currency or multiple currencies, the voucher in the account is valued in rubles on the date of inventory.</P>



5.  Click CTRL + N to create a new line.
    

    > [!NOTE]
    > <P>You cannot delete the created lines in the grid.</P>



6.  In the **Asset type** field, select the cash counting statement type from the following options:
    
      - **Cash**
    
      - **Stamps**
    
      - **Securities**
    
      - **Other**

7.  In the **Text** field, enter the description for the **Other** cash counting statement type. The description for the other types of cash counting statement is displayed.
    
    The following fields are displayed:
    
      - In the **Currency** field, the current currency code is displayed. In the **Counted amount (currency)** field, enter the counted amount in the specified currency.
    
      - The **Foreign currency revaluation** check box is automatically selected if the selected cash counting statement type has an exchange adjustment counted for the current currency.
    
      - In the **Posted amount (currency)** field, the posted amount in the specified currency is displayed.
    
      - In the **Exchange rate** field, the exchange rate in foreign currency is displayed.
    
      - In the **Counted amount** and **Posted amount** fields, the counted amount and the posted amount in default currency are displayed.

8.  Press **OK** to generate the report.
    

    > [!NOTE]
    > <P>If the <STRONG>Exchange adjustment</STRONG> check box is not selected for all the lines, an error message is displayed.</P>



## See also

[(RUS) Cash accounts (form)](https://technet.microsoft.com/en-us/library/jj665230\(v=ax.60\))

[(RUS) Cash counting statement (INV-15) (form)](https://technet.microsoft.com/en-us/library/jj711603\(v=ax.60\))

  


