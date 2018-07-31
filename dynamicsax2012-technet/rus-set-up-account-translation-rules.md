---
title: (RUS) Set up account translation rules
TOCTitle: (RUS) Set up account translation rules
ms:assetid: 94e69904-41fe-4494-9764-79ec00abc091
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923562(v=AX.60)
ms:contentKeyID: 52075408
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up account translation rules 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Translation ledger account rules** form to set up translation rules for ledger accounts. These rules are used to correlate a source company’s accounts with a target company’s accounts, and they include conversion rules for currency and dimensions.

1.  Click **General ledger** \> **Setup** \> **Translation** \> **Ledger account rules**.

2.  In the **Rule group** field, select the translation group that account conversion rules are configured for. You can set several conversion rules for one translation group.

3.  On the **Overview** tab, in the **To account** field, select the ledger account from the target company’s chart of accounts to which the source company’s transactions are translated.

4.  In the **Main account** field, select the ledger account of the source company for translation.
    

    > [!NOTE]
    > <P>Depending on your entries in the <STRONG>Offset account</STRONG> and <STRONG>Crediting</STRONG> fields, the following transactions are translated:</P>
    > <UL>
    > <LI>
    > <P>All transactions.</P>
    > <LI>
    > <P>Only debit account transactions.</P>
    > <LI>
    > <P>Only credit account transactions.</P>
    > <LI>
    > <P>Account transactions that are related to the specified account.</P>
    > <LI>
    > <P>Debit account transactions that are related to the specified credit offset account.</P>
    > <LI>
    > <P>Credit account transactions that are related to the specified debit offset account.</P></LI></UL>



5.  In the **Crediting** field, select the type of transactions to translate, from the following options:
    
      - **No** – Translate only debit account transactions.
    
      - **Yes** – Translate only credit account transactions.
    

    > [!NOTE]
    > <P>Leave this field blank to translate both credit and debit transactions.</P>



6.  In the **Offset account** field, select the source company’s offset account.
    

    > [!NOTE]
    > <P>Leave this field blank to select transactions that have an offset account.</P>



7.  In the **Currency group** field, update the code for the currency conversion group. If the default currency group is configured for the translation rule group that is selected in the **Rule group** field, the value is displayed.

8.  In the **Dimension group** field, update the code for the dimension conversion group. If the default dimension group is configured for the translation rule group that is selected in the **Rule group** field, the value is displayed.

9.  In the **Priority** field, update the priority that is configured for the rule. If the default priority is selected for the translation rule group that is selected in the **Rule group** field, the value is displayed. The priority determines the order in which rules are processed during translation. The rule that has the lowest priority is processed first.

10. On the **General** tab, in the **Posting type** field, select a voucher type to translate only transactions that have that voucher type. For example, when **Petty cash** is selected in the **Posting type** field, only transactions in the bank module are translated.

11. In the **Posting type** field, select a voucher type to translate only transactions that have that voucher type for the offset account.

12. In the **Posting layer** field, select a type of transaction to translate only transactions that have that accounting type.

13. In the **Only reversing entry** field, select **Yes** to translate only reversing transactions, or select **No** to translate regular transactions.
    

    > [!NOTE]
    > <P>Leave this field blank to translate both regular and reversing transactions.</P>



14. In the **To posting layer** field, select the accounting type that the translated transactions are assigned to in the target company.

15. Click **Initialize** to open the **Initialize** form, and then click **Select** to set up the selection criteria.

16. Click **OK** to automatically create a line that has an account translation rule for all the ledger accounts for the target company.

## See also

[(RUS) Translation ledger account rules (form)](https://technet.microsoft.com/en-us/library/jj852145\(v=ax.60\))

  


