---
title: (BEL) Set up Belgisch Luxemburgs Wissel Instituut (BLWI) information
TOCTitle: (BEL) Set up Belgisch Luxemburgs Wissel Instituut (BLWI) information
ms:assetid: 4e663121-3766-4814-bbec-2d844dcd2e08
ms:mtpsurl: https://technet.microsoft.com/library/Gg212744(v=AX.60)
ms:contentKeyID: 36057055
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Belgium
---

# (BEL) Set up Belgisch Luxemburgs Wissel Instituut (BLWI) information 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A Belgisch Luxemburgs Wissel Instituut (BLWI) declaration report is a declaration of the foreign trade of goods and the state of bank accounts outside of Belgium. It includes customer transactions, vendor transactions, and financial transactions for specific bank accounts and currencies.

You must set up default currencies, countries/regions, country/region groups, and payment purpose codes before you can set up BLWI information.

## Set up BLWI parameters

1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **BLWI** \> **BLWI parameters**.

2.  On the **General** link, select the **BLWI** check box to activate BLWI.

3.  In the **Central bank purpose code** field, select a central bank purpose code.

4.  Enter the name of the contact person at the National Bank of Belgium (NBB), telephone number, fax number, and email address, if required.

5.  In the **Check BLWI code on journals** field, select the indication level for the BLWI code for journals. Select from the following options.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Indication level</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>None</strong></p></td>
    <td><p>No information is provided for errors or warnings.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Error</strong></p></td>
    <td><p>A message is displayed if there are errors or warnings.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Warning</strong></p></td>
    <td><p>The ledger journal or invoice is not posted if there are errors or warnings.</p></td>
    </tr>
    </tbody>
    </table>


6.  Close the form to save your changes.

## Set up BLWI country/region groups

1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **BLWI** \> **BLWI country/region groups**.

2.  Press CTRL+N to create a new row number in the monthly report.

3.  In the **Group ID** and **Description** fields, enter a group ID and description.

4.  Select the **BLWI reporting** check box to print trade totals for this country on the BWLI report.

5.  Click the **BLWI country/region** tab and select a country/region code to assign to the country/region group.

6.  Click **Initialization** to update the tables with a default set of values.

7.  Click **Translations** to select the country/region group in the language that the report is printed in.

8.  Close the form to save your changes.

## Set up BLWI currencies

1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **BLWI** \> **BLWI currencies**.

2.  Press CTRL+N and select a currency.

3.  Select the **Report in this currency** check box to print reports in that currency.

4.  In the **Column number** field, enter a column number in which to print the currency for the report. Different currencies can be printed in separate columns.

5.  Close the form to save your changes.

## See also

[(BEL) Set up State 11 information](bel-set-up-state-11-information.md)

[(BEL) Create and transfer transactions to the BLWI](bel-create-and-transfer-transactions-to-the-blwi.md)

  


