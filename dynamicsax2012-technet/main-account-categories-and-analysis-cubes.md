---
title: Main account categories and analysis cubes
TOCTitle: Main account categories and analysis cubes
ms:assetid: c46186f1-b4bf-4554-b2c9-ab7aa27897cf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213640(v=AX.60)
ms:contentKeyID: 36993128
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Main account categories and analysis cubes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The default main account categories and the analysis cubes that are provided with Microsoft Dynamics AX are designed to work together. Consider the following points if you want to change either the default main account categories or the analysis cubes:

  - You cannot delete the default main account categories.

  - Use caution if you change the name of a default main account category. If the new name has a different meaning than the default name, key performance indicators (KPIs) that use data from that main account category might show incorrect data. For example, you change the name of main account category 1 from Cash to Cost of Goods Sold. KPIs that use that main account category continue to use main account category 1 as if it contains the Cash amounts.

  - You can add main account categories. To incorporate data from the main account categories into KPIs and other calculated measures, you must also revise the relevant calculations.


> [!NOTE]
> <P>When you use the <STRONG>SQL Server Analysis Services project wizard</STRONG>, the wizard verifies that at least one account is associated with each main account category that is used by calculated measures and KPIs. If no account is associated with a main account category, a warning message is displayed.</P>



The following sections provide information about the default main account categories, and the KPIs and calculated measures that use them.

## Default main account categories

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Reference ID</p></th>
<th><p>Main account category</p></th>
<th><p>Description</p></th>
<th><p>Typical main account type</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p><strong>CASH</strong></p></td>
<td><p>Cash</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p><strong>CASHEQUIV</strong></p></td>
<td><p>Cash equivalents</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p><strong>SHORTTERMINVEST</strong></p></td>
<td><p>Short term investments</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p><strong>AR</strong></p></td>
<td><p>Accounts receivable</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>5</p></td>
<td><p><strong>INV</strong></p></td>
<td><p>Inventory</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>6</p></td>
<td><p><strong>NOTESREC</strong></p></td>
<td><p>Notes receivable</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>7</p></td>
<td><p><strong>WIP</strong></p></td>
<td><p>Work in process</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>8</p></td>
<td><p><strong>PREPAIDEXP</strong></p></td>
<td><p>Prepaid expenses</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>9</p></td>
<td><p><strong>OTHERCA</strong></p></td>
<td><p>Other current assets</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>10</p></td>
<td><p><strong>LONGTERMINVEST</strong></p></td>
<td><p>Long term investments</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>11</p></td>
<td><p><strong>PPE</strong></p></td>
<td><p>Property, plant, and equipment</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>12</p></td>
<td><p><strong>ACCUDEP</strong></p></td>
<td><p>Accumulated depreciation</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>13</p></td>
<td><p><strong>INTANASSET</strong></p></td>
<td><p>Intangible assets</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>14</p></td>
<td><p><strong>OTHERASSET</strong></p></td>
<td><p>Other assets</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>15</p></td>
<td><p><strong>AP</strong></p></td>
<td><p>Accounts payable</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>16</p></td>
<td><p><strong>NOTESPAY</strong></p></td>
<td><p>Notes payable</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>17</p></td>
<td><p><strong>CURRENTMATLTD</strong></p></td>
<td><p>Current maturities on long term debt</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>18</p></td>
<td><p><strong>TAXPAY</strong></p></td>
<td><p>Taxes payable</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>19</p></td>
<td><p><strong>INTPAY</strong></p></td>
<td><p>Interest payable</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>20</p></td>
<td><p>–<strong>DIVPAY</strong></p></td>
<td><p>Dividends payable</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>21</p></td>
<td><p><strong>LEASEPAY</strong></p></td>
<td><p>Leases payable (Current)</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>22</p></td>
<td><p><strong>SINKPAY</strong></p></td>
<td><p>Sinking fund payable (Current)</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>23</p></td>
<td><p><strong>OTHERCURLIA</strong></p></td>
<td><p>Other current liabilities</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>24</p></td>
<td><p><strong>LONGTERMDEBT</strong></p></td>
<td><p>Long term debt</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>25</p></td>
<td><p><strong>COMMONSTOCK</strong></p></td>
<td><p>Common stock</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>26</p></td>
<td><p><strong>PREFERREDSTOCK</strong></p></td>
<td><p>Preferred stock</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>27</p></td>
<td><p><strong>ADDPAIDINCAPCOM</strong></p></td>
<td><p>Additional paid in capital – Common</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>28</p></td>
<td><p><strong>ADDPAIDINCAPPREF</strong></p></td>
<td><p>Additional paid in capital – Preferred</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>29</p></td>
<td><p><strong>RETEARN</strong></p></td>
<td><p>Retained earnings</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>30</p></td>
<td><p><strong>TREASTOCK</strong></p></td>
<td><p>Treasury stock</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>31</p></td>
<td><p><strong>COMMONDIV</strong></p></td>
<td><p>Common dividends</p></td>
<td><p>Not included in KPIs</p></td>
</tr>
<tr class="even">
<td><p>32</p></td>
<td><p><strong>PREFERREDDIV</strong></p></td>
<td><p>Preferred dividends</p></td>
<td><p>Not included in KPIs</p></td>
</tr>
<tr class="odd">
<td><p>33</p></td>
<td><p><strong>SALES</strong></p></td>
<td><p>Sales</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="even">
<td><p>34</p></td>
<td><p><strong>SALERETDIS</strong></p></td>
<td><p>Sales returns and discounts</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="odd">
<td><p>35</p></td>
<td><p><strong>COGS</strong></p></td>
<td><p>Cost of goods sold</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="even">
<td><p>36</p></td>
<td><p><strong>SELLEXP</strong></p></td>
<td><p>Selling expense</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="odd">
<td><p>37</p></td>
<td><p><strong>ADMINEXP</strong></p></td>
<td><p>Administrative expense</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="even">
<td><p>38</p></td>
<td><p><strong>MANUEXP</strong></p></td>
<td><p>Manufacturing expense</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="odd">
<td><p>39</p></td>
<td><p><strong>TANDEEXP</strong></p></td>
<td><p>Travel and entertainment expenses</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="even">
<td><p>40</p></td>
<td><p><strong>PROJEXP</strong></p></td>
<td><p>Project operation expense</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="odd">
<td><p>41</p></td>
<td><p><strong>SALARYEXP</strong></p></td>
<td><p>Salaries expense</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="even">
<td><p>42</p></td>
<td><p><strong>OTHEREMPEXP</strong></p></td>
<td><p>Other employee expenses</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="odd">
<td><p>43</p></td>
<td><p><strong>INTEXP</strong></p></td>
<td><p>Interest expense</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="even">
<td><p>44</p></td>
<td><p><strong>TAXEXP</strong></p></td>
<td><p>Tax expense</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="odd">
<td><p>45</p></td>
<td><p><strong>DEPREXP</strong></p></td>
<td><p>Depreciation expense</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="even">
<td><p>46</p></td>
<td><p><strong>INCTAXEXP</strong></p></td>
<td><p>Income tax expense</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="odd">
<td><p>47</p></td>
<td><p><strong>OTHEREXP</strong></p></td>
<td><p>Other expenses</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="even">
<td><p>48</p></td>
<td><p><strong>OTHERINC</strong></p></td>
<td><p>Other income</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="odd">
<td><p>49</p></td>
<td><p><strong>CHRNOTUSEWORKCAP</strong></p></td>
<td><p>Charges not using working capital</p></td>
<td><p>Not included in KPIs</p></td>
</tr>
<tr class="even">
<td><p>50</p></td>
<td><p><strong>REVNOTPRODWORKCAP</strong></p></td>
<td><p>Revenues not producing working capital</p></td>
<td><p>Not included in KPIs</p></td>
</tr>
<tr class="odd">
<td><p>51</p></td>
<td><p><strong>GAINLOSSASSET</strong></p></td>
<td><p>Gain/loss on asset disposal</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="even">
<td><p>52</p></td>
<td><p><strong>AMORTINTAGASSET</strong></p></td>
<td><p>Amortization of intangible assets</p></td>
<td><p><strong>Profit and loss</strong></p></td>
</tr>
<tr class="odd">
<td><p>53</p></td>
<td><p><strong>STATISTICAL</strong></p></td>
<td><p>Statistical accounts</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>54</p></td>
<td><p><strong>ENCUMBRANCE</strong></p></td>
<td><p>Encumbrance</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="odd">
<td><p>55</p></td>
<td><p><strong>PRE-ENCUMBRANCE</strong></p></td>
<td><p>Pre-encumbrance</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
<tr class="even">
<td><p>1001</p></td>
<td><p><strong>CONSOLIDATIONS</strong></p></td>
<td><p>Consolidations</p></td>
<td><p><strong>Balance sheet</strong></p></td>
</tr>
</tbody>
</table>


## KPIs that use default main account categories

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>KPI</p></th>
<th><p>Main account category reference ID</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Accounts payable</strong></p></td>
<td><p>15</p></td>
</tr>
<tr class="even">
<td><p><strong>Accounts payable turnover</strong></p></td>
<td><p>5, 15, 35</p></td>
</tr>
<tr class="odd">
<td><p><strong>Accounts receivable</strong></p></td>
<td><p>4</p></td>
</tr>
<tr class="even">
<td><p><strong>Accounts receivable turnover</strong></p></td>
<td><p>4, 33-34</p></td>
</tr>
<tr class="odd">
<td><p><strong>All other org. assets</strong></p></td>
<td><p>3, 8-9, 11-12, 14</p></td>
</tr>
<tr class="even">
<td><p><strong>Average collection period</strong></p></td>
<td><p>4, 33</p></td>
</tr>
<tr class="odd">
<td><p><strong>Average days to pay</strong></p></td>
<td><p>5, 15, 35</p></td>
</tr>
<tr class="even">
<td><p><strong>Cash and cash equivalents</strong></p></td>
<td><p>1-2</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cash position</strong></p></td>
<td><p>1-2</p></td>
</tr>
<tr class="even">
<td><p><strong>Cash ratio</strong></p></td>
<td><p>1-2, 15-23</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cost of goods sold</strong></p></td>
<td><p>35</p></td>
</tr>
<tr class="even">
<td><p><strong>Current ratio</strong></p></td>
<td><p>1-9, 15-23</p></td>
</tr>
<tr class="odd">
<td><p><strong>Debt to equity</strong></p></td>
<td><p>15-30</p></td>
</tr>
<tr class="even">
<td><p><strong>Debt to total assets</strong></p></td>
<td><p>1-24</p></td>
</tr>
<tr class="odd">
<td><p><strong>Earnings before income tax</strong></p></td>
<td><p>33-42, 45-48</p></td>
</tr>
<tr class="even">
<td><p><strong>Expense budget variance</strong></p></td>
<td><p>35-47, 51-52</p></td>
</tr>
<tr class="odd">
<td><p><strong>Gross profit</strong></p></td>
<td><p>33-35</p></td>
</tr>
<tr class="even">
<td><p><strong>Gross profit margin</strong></p></td>
<td><p>33-35</p></td>
</tr>
<tr class="odd">
<td><p><strong>Interest payable</strong></p></td>
<td><p>19</p></td>
</tr>
<tr class="even">
<td><p><strong>Inventory and work in progress</strong></p></td>
<td><p>5, 7</p></td>
</tr>
<tr class="odd">
<td><p><strong>Inventory turnover</strong></p></td>
<td><p>5, 35</p></td>
</tr>
<tr class="even">
<td><p><strong>Long-term debt</strong></p></td>
<td><p>24</p></td>
</tr>
<tr class="odd">
<td><p><strong>Long-term investment</strong></p></td>
<td><p>10</p></td>
</tr>
<tr class="even">
<td><p><strong>Net income</strong></p></td>
<td><p>33-48</p></td>
</tr>
<tr class="odd">
<td><p><strong>Notes payable</strong></p></td>
<td><p>16</p></td>
</tr>
<tr class="even">
<td><p><strong>Notes receivable</strong></p></td>
<td><p>6</p></td>
</tr>
<tr class="odd">
<td><p><strong>Other liabilities</strong></p></td>
<td><p>17-18, 20-23</p></td>
</tr>
<tr class="even">
<td><p><strong>Quick ratio</strong></p></td>
<td><p>1-4, 6, 15-23</p></td>
</tr>
<tr class="odd">
<td><p><strong>Return on total assets</strong></p></td>
<td><p>1-14, 33-48, 51-52</p></td>
</tr>
<tr class="even">
<td><p><strong>Revenue budget variance</strong></p></td>
<td><p>33-34, 48, 51</p></td>
</tr>
<tr class="odd">
<td><p><strong>Times interest earned</strong></p></td>
<td><p>33-43, 45, 47-48, 51-52</p></td>
</tr>
<tr class="even">
<td><p><strong>Total expenses</strong></p></td>
<td><p>35-47, 51-52</p></td>
</tr>
<tr class="odd">
<td><p><strong>Total revenue</strong></p></td>
<td><p>33-34, 48, 51</p></td>
</tr>
</tbody>
</table>


## See also

[Create a main account](create-a-main-account.md)

[Set up main account categories](set-up-main-account-categories.md)

  


