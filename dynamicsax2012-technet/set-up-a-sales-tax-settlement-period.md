---
title: Set up a sales tax settlement period
TOCTitle: Set up a sales tax settlement period
ms:assetid: 535eec81-d317-4903-ab65-6ec7b28fcb5e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa548925(v=AX.60)
ms:contentKeyID: 36057296
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up a sales tax settlement period [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Set up a sales tax settlement periods by creating the sales tax settlement period, setting up the period length, and creating the individual settlement periods.

## Create the sales tax settlement period

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax settlement periods**.

2.  If necessary, click **New** to create a line for the sales tax settlement period.

3.  In the **Settlement period** field, enter a unique code for the settlement period.

4.  In the **Description** field, enter a name or description of the settlement period.

5.  In the **Authority** field, select the sales tax authority that receives the reports and payments that are related to the settlement period.

6.  In the **Terms of payment** field, select the terms of payment that reflect the requirements of the sales tax authority of the settlement period.
    
    **Example**
    
    Your organization settles sales taxes every quarter, and the sales tax authorities expect settlement 14 days after the close of the quarter. The sales tax settlement periods and deadlines are as follows:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Settlement period</p></th>
    <th><p>Deadline for reporting</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>January 1 through March 31</p></td>
    <td><p>April 14</p></td>
    </tr>
    <tr class="even">
    <td><p>April 1 through June 30</p></td>
    <td><p>July 14</p></td>
    </tr>
    <tr class="odd">
    <td><p>July 1 through September 30</p></td>
    <td><p>October 14</p></td>
    </tr>
    <tr class="even">
    <td><p>October 1 through December 31</p></td>
    <td><p>January 14 of the following year</p></td>
    </tr>
    </tbody>
    </table>
    
    You must settle your sales taxes on April 14. You select a value in the **Terms of payment** field that is equivalent to "Net 14 days". On April 10, you run the **Sales tax payments** job. The resulting due date for the settlement of sales taxes is April 14.
    
    To calculate sales tax for the first quarter, you must set the **Transaction date** field in the **Sales tax payment** form to the last day of the settlement period, which is March 31.

## Set up the length of the period

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax settlement periods**.

2.  Click the **General** tab.

3.  In the **Period interval** list, select the length of the interval.

4.  In the **Number of units** field, specify the number of units of the interval that make up the sales tax settlement period.

## Create the individual settlement periods

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax settlement periods**.

2.  Click the **Periods** tab.

3.  In the **From date** field, enter the first day of the first sales tax settlement period.

4.  In the **To date** field, enter the last day of the first period.

5.  Click **Add** to create additional periods. The date fields are filled in automatically based on the setup of the period length.
    
    **Example**
    
    In 2011, your organization settles its sales taxes every quarter. You create the first period by entering January 1, 2011 in the **From date** field and March 31, 2011 in the **To date** field. To create the other quarters of the year, click **Add** three times.

## See also

[Terms of payment (form)](https://technet.microsoft.com/en-us/library/aa588427\(v=ax.60\))

[Sales tax authorities (form)](https://technet.microsoft.com/en-us/library/aa552841\(v=ax.60\))

[Set up sales tax authorities](set-up-sales-tax-authorities.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

