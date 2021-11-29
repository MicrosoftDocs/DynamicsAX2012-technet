---
title: (RUS) Set up a cash account
TOCTitle: (RUS) Set up a cash account
ms:assetid: 77d50c40-fc1c-4cd0-b4c0-2852bffcf13d
ms:mtpsurl: https://technet.microsoft.com/library/JJ678373(v=AX.60)
ms:contentKeyID: 49387604
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a cash account 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



As a rule, the cash account corresponds with the company's cash office. General settings, such as the document number sequence group, default transaction currency, and cash balance limits, are stipulated in the cash account.

1.  Click **Cash and bank management** \> **Common** \> **Cash accounts**.

2.  Click CTRL+N to create a new line.

3.  In the **Cash** field, enter a unique code to identify the cash account.

4.  In the **Name** field, enter a description of the cash account.

5.  In the **Currency** field, select the default currency to register the cash transaction.

6.  Click the **General** tab.

7.  In the **Number sequence group** field, select a number sequence group to allocate different number sequences to different cash reference types.

8.  Click the **Validation** tab.

9.  In the **Currency** field, select the default currency for cash transactions.

10. Select the **More currencies** check box to allow posting of operations using other currencies to the cash account.

11. Select the **Negative cash** check box to allow a negative cash account balance in any currency.

12. Click **Balance limit** to open the **Balance limit** form, and then set up the cash balance limit.

13. In the **Currency Type** field, select either **Default Currency** or **Indicated Currency** as the currency type.

14. In the **Currency** field, select the current currency code.
    

    > [!NOTE]
    > <P>You can select the current currency code only if <STRONG>Indicated Currency</STRONG> is selected in the <STRONG>Currency Type</STRONG> field.</P>



15. In the **Balance limit type** field, select either **Maximum** or **Minimum** as the cash balance limit type.

16. In the **Check balance limit** field, select the response for error-checking during posting. The options are:
    
      - **Accept** – Exceeding the current balance limit amount is allowed.
    
      - **Warning** – Exceeding the current limit amount is allowed but a warning is displayed.
    
      - **Error** – The voucher cannot be posted and an error message is displayed if the limit is exceeded.

17. In the **Balance Limit** field, enter the cash balance limit for the amount.

18. Press CTRL+S or close the **Balance limit** form and return to the **Cash accounts** form.

19. Press CTRL+S or close the form.

## See also

[(RUS) Balance limit (form)](https://technet.microsoft.com/library/jj711356\(v=ax.60\))

[(RUS) Cash accounts (form)](https://technet.microsoft.com/library/jj665230\(v=ax.60\))

  


