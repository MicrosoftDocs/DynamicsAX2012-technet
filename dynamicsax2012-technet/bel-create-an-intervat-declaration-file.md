---
title: (BEL) Create an INTERVAT declaration file
TOCTitle: (BEL) Create an INTERVAT declaration file
ms:assetid: 6b552fb8-6844-4f07-9382-eece9aa62cbe
ms:mtpsurl: https://technet.microsoft.com/library/Gg231784(v=AX.60)
ms:contentKeyID: 36057988
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- declaration
- INTERVAT
audience: Application User
ms.search.region: Belgium
---

# (BEL) Create an INTERVAT declaration file 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **INTERVAT tax declaration** form to enter tax header declaration information, general information, and date and signature information for the INTERVAT declaration file.

You can create the INTERVAT declaration as an XML file. You can also include corrections in the INTERVAT declaration from the previous year. Additionally, if you did not have transactions for a turnover report or an annual listing during the previous financial year, you can indicate that this is an empty annual listing. For more information, see [(BEL) Additional sales tax report boxes (form)](https://technet.microsoft.com/library/aa599851\(v=ax.60\)).


> [!NOTE]
> <P>You must secure the appropriate folders by using user or group permissions.</P>



1.  Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Belgium** \> **Additional sales tax report boxes**.

2.  Click **Create new set** to display the first settlement period that you created in the **Sales tax settlement periods** form.

3.  If you do not have any transactions to report for the settlement period, click the **General** tab, and then select the **Nil annual listing** check box.

4.  Close the form.

5.  Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Belgium** \> **INTERVAT tax declaration**.

6.  Click **New declaration**.

7.  Select a settlement period, and then in the **From date** field, enter the starting date of the reporting period.

8.  In the **Transaction date** field, select a transaction date.

9.  In the **File** field, select a file name and path to save the declaration.

10. Click **Settlement account**, and then in the **Settlement account** field, select a settlement account for the declaration.

11. Click **OK**.

12. Select the **Update** check box to update a previously submitted declaration.

13. In the **Replaced VAT declaration** field, enter the identification number of the declaration to replace.

14. Click **OK** to print the report.

15. In the **INTERVAT tax declaration** form, on the **Frame I: General information** tab, select the **Nil annual listing** check box if this is not the default option.

You can print a simplified report for a settlement period, and then verify the information in the INTERVAT declaration file. Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Sales tax payments**.

After you create the INTERVAT declaration file, you can upload the file by using the INTERVAT website.

## See also

[(BEL) Set up INTERVAT](bel-set-up-intervat.md)

[(BEL) INTERVAT tax declaration (form)](https://technet.microsoft.com/library/hh242885\(v=ax.60\))

[Set up and use a sales tax group](set-up-and-use-a-sales-tax-group.md)

[Create item sales tax groups](create-item-sales-tax-groups.md)

  


