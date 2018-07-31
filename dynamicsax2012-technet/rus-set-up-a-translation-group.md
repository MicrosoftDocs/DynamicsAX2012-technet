---
title: (RUS) Set up a translation group
TOCTitle: (RUS) Set up a translation group
ms:assetid: 8c4c5791-29aa-49f3-aa26-2726262f8a9d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923558(v=AX.60)
ms:contentKeyID: 52075404
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a translation group 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create translation group rules for several companies to determine the imbalance and translation differences of ledger account transactions. Imbalance can occur when there is a difference in the transaction total that is caused by ledger account rule mismatches. You must post this amount difference that occurred because of an imbalanced ledger account to balance the voucher.

Translation difference is an imbalance in the default currency or the secondary currency, which can arise when the target company uses different exchange rates. Because of mismatches in currency rule group, some amounts are not translated.

1.  Click **General ledger** \> **Setup** \> **Translation** \> **Translation groups**.

2.  Press CTRL+N to create a new line.

3.  In the **Rule group** field, enter a unique translation group code.

4.  In the **To company** field, select the target company code for translation.

5.  In the **Description** field, enter a text description of the translation group.
    

    > [!NOTE]
    > <P>The value of the standard currency of the target company is updated automatically in the <STRONG>To currency</STRONG> field.</P>



6.  On the **Translation methods** FastTab, click **Methods initialization** to create a list of translation methods.

7.  In the **Method** field, select **Ledger translation**.

8.  Click the **Ledger parameters** FastTab. In the **Default currency group** field, select the currency group that is used by default for the account translation rules.

9.  In the **Default dimension group** field, select the dimension group that is used by default for the account translation rules.

10. In the **Default priorities** field, enter the priority that is used by default for the account translation rules.

11. Select the **New ledger vouchers** check box to create new ledger voucher numbers when you perform the translations.
    

    > [!NOTE]
    > <P>If the check box is not selected, ledger account transactions are translated to the ledger account of the target company with the voucher number of the source company.</P>



12. In the **Number sequence code** field, select the number sequence for the vouchers.
    

    > [!NOTE]
    > <P>The field is enabled if you select the <STRONG>New ledger vouchers</STRONG> check box.</P>



13. In the **Check translation difference** field, select one of the following messages about the translation difference validation for the default and secondary currencies:
    
      - **Error** – When the transaction is posted to the translation difference account, an error message is displayed and the translation session is canceled.
    
      - **Warning** – When the translation session is finished, a message about the amounts that are posted to the translation difference account is displayed. All transactions are translated to the ledger account of the target company.

14. In the **Ledger account** field, select the main account number that will reflect the translation differences for the target company's default and secondary currencies.
    

    > [!NOTE]
    > <P>A translation difference can occur when the debit and credit lines of the transaction have been translated to the target company at different exchange rates, or from rounding errors.</P>



15. In the **Check imbalance** field, select one of the following messages of validation when an imbalance occurs because of the following options:
    
      - **Error** – When the transaction is posted to the imbalance account, an error message is displayed and the translation session is canceled.
    
      - **Warning** – When the translation session completes, a message about the amounts that are posted to the imbalance account is displayed. All transactions are translated to the target company.

16. In the **Ledger account** field, select the account number that is used to accumulate the imbalance amounts in the target company transaction currency.
    

    > [!NOTE]
    > <P>An imbalance can occur during translation when a debit transaction is translated into the target company but the other credit transaction is not translated.</P>



## See also

[(RUS) Translation groups (form)](https://technet.microsoft.com/en-us/library/jj923574\(v=ax.60\))

[(RUS) Set up account translation rules](rus-set-up-account-translation-rules.md)

  


