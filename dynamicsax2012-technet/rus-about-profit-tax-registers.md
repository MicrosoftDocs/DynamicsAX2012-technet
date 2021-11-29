---
title: (RUS) About profit tax registers
TOCTitle: (RUS) About profit tax registers
ms:assetid: a19f5352-38a9-45db-870d-98cbeef3fce6
ms:mtpsurl: https://technet.microsoft.com/library/JJ856175(v=AX.60)
ms:contentKeyID: 50407014
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- profit tax
- registers
- tax registers
audience: Application User
ms.search.region: Russia
---

# (RUS) About profit tax registers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Legal entities can use registers to disclose their revenues and expenses. The registers are used to track revenue and expense data from the time that primary documents, such as sales invoices and delivery notes, are first entered into Microsoft Dynamics AX by using the calculation of cost prices for production. The data from the registers is used to confirm the declared profit of the legal entity.

Microsoft Dynamics AX serves as a data source for various registers, such as fixed assets, inventory management, production, general ledger, accounts receivable, accounts payable, and personnel accounts. The registers are interrelated: Calculated registers use the data from voucher registers, and then totals registers use the data from calculated registers. However, the basis for all of the registers is the revenue or expense code.

The registers are classified based on the information that they contain:

  - Registers of intermediate calculations – These registers store and display information to support the calculation of intermediate figures that are essential to generate a tax base.

  - Registers of the account status of the tax account unit – These registers contain systematized information about account object figures that apply to more than one tax reporting period. The registers of a specific group provide information about the status of an account object for the current period and changes to the object status of the tax account over time.

  - Registers of the generation of report data – These registers provide information about the order that the values for the tax declaration were received.

The following tables provide information about the inventory number and the corresponding type of register in Microsoft Dynamics AX.

  - Registers of on-account calculations
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Inventory number</p></th>
    <th><p>Type of register in Microsoft Dynamics AX</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>1</p></td>
    <td><p><strong>Calculation of temporary tax differences</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>2</p></td>
    <td><p><strong>Accounts receivable movement</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>3</p></td>
    <td><p><strong>Accounts receivable - bad debt reserve movement</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>4</p></td>
    <td><p><strong>Accounts receivable inventory act</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>5</p></td>
    <td><p><strong>Accounts receivable - bad debts reserve</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>6</p></td>
    <td><p><strong>Cash payment receipt</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>7</p></td>
    <td><p><strong>Cash payment issue</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>8</p></td>
    <td><p><strong>Account payable movement</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>9</p></td>
    <td><p><strong>Accounts payable inventory act</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>10</p></td>
    <td><p><strong>IA depreciation</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>11</p></td>
    <td><p><strong>Standard expenses rate for deferred periods</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>12</p></td>
    <td><p><strong>Standard expenses rate for current period</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>13</p></td>
    <td><p><strong>Standard expenses in current period</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>14</p></td>
    <td><p><strong>Incomes and expenses that do not influence the tax base</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>15</p></td>
    <td><p><strong>FA/IA sale</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>16</p></td>
    <td><p><strong>FA depreciation</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>17</p></td>
    <td><p><strong>Calculation of constant tax differences</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>19</p></td>
    <td><p><strong>Outlay - realized</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>20</p></td>
    <td><p><strong>Exchange adjustment in accounting</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>21</p></td>
    <td><p><strong>Amount difference in tax accounting</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>22</p></td>
    <td><p><strong>Goods cost calculation</strong></p></td>
    </tr>
    </tbody>
    </table>


  - Registers of the account status of the tax account unit
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Inventory number</p></th>
    <th><p>Type of register in Microsoft Dynamics AX</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>23</p></td>
    <td><p><strong>FA - information about object</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>24</p></td>
    <td><p><strong>IA - object information</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>25</p></td>
    <td><p><strong>Deferrals</strong></p></td>
    </tr>
    </tbody>
    </table>


  - Registers for the generation of report data
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Inventory number</p></th>
    <th><p>Type of register in Microsoft Dynamics AX</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>26</p></td>
    <td><p><strong>Goods issued</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>27</p></td>
    <td><p><strong>Incomes - current period</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>28</p></td>
    <td><p><strong>Outlay - realized</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>29</p></td>
    <td><p><strong>Outlays - Unrealized</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>30</p></td>
    <td><p><strong>Outlays - other unrealized</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>31</p></td>
    <td><p><strong>Non warehoused items</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>32</p></td>
    <td><p><strong>Warehoused items</strong></p></td>
    </tr>
    </tbody>
    </table>


## See also

[(RUS) Set up the expense and income codes for tax registers](rus-set-up-the-expense-and-income-codes-for-tax-registers.md)

[(RUS) View the register tree structure](rus-view-the-register-tree-structure.md)

[(RUS) Set up additional tax register parameters](rus-set-up-additional-tax-register-parameters.md)

  


