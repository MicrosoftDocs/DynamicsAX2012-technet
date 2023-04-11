---
title: (EEUR) Set up monetary unit declensions
TOCTitle: (EEUR) Set up monetary unit declensions
ms:assetid: 6d259616-910d-447c-8a35-c3ffe3086234
ms:mtpsurl: https://technet.microsoft.com/library/JJ677562(v=AX.60)
ms:contentKeyID: 49384865
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Set up monetary unit declensions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

1.  Click **General ledger** \> **Setup** \> **Currency** \> **Currencies**.

2.  Press CTRL+N to create the currency that your company uses, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Currencies (form)" in Applications and Business Processes Help.</P>



3.  Click **Declension** to open the **Monetary unit declensions** form.

4.  In the **Language** field, select the language for which to populate the declension fields for currency units.

5.  In the **Name of units** field group, in the **Singular nominative** field, enter the currency name in the singular nominative.

6.  In the **Plural nominative** field, enter the currency name in the plural nominative.

7.  In the **Singular genitive** field, enter the currency name in the singular genitive.

8.  In the **Plural genitive** field, enter the currency name in the plural genitive.
    

    > [!NOTE]
    > <P>The <STRONG>Singular genitive</STRONG> and <STRONG>Plural genitive</STRONG> fields are available, depending on the language that you select in the <STRONG>Language</STRONG> field.</P>



9.  In the **Name of parts** field group, in the **Singular nominative** field, enter the name of the fractional currency in the singular nominative.

10. In the **Plural nominative** field, enter the name of the fractional currency in the plural nominative.

11. In the **Singular genitive** field, enter the name of the fractional currency in the singular genitive.

12. In the **Plural genitive** field, enter the name of the fractional currency in the plural genitive.

13. In the **Shortcut name of units** field, enter the International Organization for Standardization (ISO) code that identifies the currency. For example, enter **LTL** to identify Litas.

14. In the **Shortcut name for parts** field, enter the shortcut name for parts of the currency.

15. Select the **Conjunction 'and' between units and parts** check box to print the conjunction "and" between units and parts. For example, the amount LTL 100.20 is displayed as "100 Litas and 20 Centas" on invoices or reports.

16. Press CTRL+S or close the form.


> [!NOTE]
> <P>This data is used when reports and primary forms are printed. The code for the invoice currency is printed if the invoice currency differs from the default currency of the company.</P>



## See also

[(EEUR) Monetary unit declensions (form)](https://technet.microsoft.com/library/jj710691\(v=ax.60\))

  


