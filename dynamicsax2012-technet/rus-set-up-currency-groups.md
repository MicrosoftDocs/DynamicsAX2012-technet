---
title: (RUS) Set up currency groups
TOCTitle: (RUS) Set up currency groups
ms:assetid: 89a30540-9326-49f6-91c9-5eabfc6a14d1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ856115(v=AX.60)
ms:contentKeyID: 50406413
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RTSLCurrencyRuleGroup
- MsDynAx060.Forms.RTSLCurrencyRuleGroup
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up currency groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



Set up currency groups to specify rules to convert currency from the source company's currency into the target company's currency.

1.  Click **General ledger** \> **Setup** \> **Translation** \> **Currency groups**.

2.  In the **Rule group** field, select the rule group for which the currency translation rule is to be set up.
    

    > [!NOTE]
    > <P>You can set several currency conversion rules for one translation group.</P>



3.  In the **Currency group** field, enter a unique currency group code.

4.  In the **Description** field, enter a text description for the currency group.

5.  On the **Currency conversion rules** tab, press CTRL+N to create a new line.

6.  In the **Currency** field, select the currency code for the source company.

7.  In the **Rate method** field, select the currency conversion method from the following options:
    
      - **No changes** – A transaction is created during translation for the target company whose amount and currency will equal that for the source company. The amount in the default and secondary currencies is calculated by using a conversion that corresponds to the target company's exchange rates.
    
      - **Use indexes** – If you select this option, on the **Indexes and amounts** tab, specify the rules for determining the transaction amounts for the target company using indexes.
    
      - **Use exchange rates** – If you select this option, on the **Indexes and amounts** tab, specify the rules for determining the transaction amounts in the transaction currency, default currency, and secondary currency using exchange rates.

8.  Click the **Indexes and amounts** tab.
    

    > [!NOTE]
    > <P>Select <STRONG>Use indexes</STRONG> in the <STRONG>Rate method</STRONG> field to activate the fields under the <STRONG>Inflation indexes</STRONG> field group, or select <STRONG>Use exchange rates</STRONG> in the <STRONG>Rate method</STRONG> field to activate the fields under the <STRONG>Amounts</STRONG> field group.</P>



9.  In the **Inflation (cur)** field, select the conversion index for transaction currency.

10. In the **Inflation (MST)** field, select the conversion index for a standard currency.

11. In the **Inflation (sec)** field, select the conversion index for a secondary currency.

12. In the **Amount (cur)** field, select the rule according to which the transaction amount is to be converted in the voucher currency.

13. In the **Amount (MST)** field, select the rule according to which the transaction amount is to be converted in the default currency.

14. In the **Amount (sec)** field, select the rule according to which the transaction amount is to be converted in the secondary currency.

15. Press CTRL+S or close the form.

## See also

[(RUS) Currency groups (form)](https://technet.microsoft.com/en-us/library/jj665220\(v=ax.60\))

  


