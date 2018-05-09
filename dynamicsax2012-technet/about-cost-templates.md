---
title: About cost templates
TOCTitle: About cost templates
ms:assetid: bcdeaa27-bdca-4a06-b751-42a556ee329f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498870(v=AX.60)
ms:contentKeyID: 36059143
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cost template
- cost line
---

# About cost templates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Cost templates are used in the calculations for revenue recognition for fixed-price projects.

In Microsoft Dynamics AX, a cost template is an attribute on an estimate project. The cost template and cost template lines determine which forecasts and which actual transactions are included to calculate the percentage of the project that is complete. The percent-complete value is then used to calculate how much revenue is recognized.

**Example**

You are working on a Web site design project for a customer for a flat fee of USD 10,000. You forecast that it will take 100 hours (USD 5,000) to complete the project. You also forecast two plane tickets and four nights in hotels for trips to the customer’s site (USD 1,800). This results in a total forecasted cost of USD 6,800.

When you run the fixed-price revenue recognition process to create an estimate at the end of the month, you find that you have worked 35 hours on the project to this point, without flights or hotel stays yet. You also had an assistant perform five hours of research for the project at a cost of USD 100, which you had not at first planned for.

When you calculate the percent complete value for this project, you have some choices to make:

  - Do you want to include all costs (hours and expenses) or just hours?

  - Do you want to include all hours or just planned hours?

  - Do you want to calculate the percent complete based on the dollar cost of the planned hours (USD 5,000) or just on the number of hours (100)?

Your answers to these questions determine the options that you set on the cost template and the categories that you select on the cost template lines.

The following table illustrates the results of different methods of calculating the percent-complete value for this scenario.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Completion based on</strong></p></th>
<th><p>Dollar cost or units</p></th>
<th><p>Percent complete</p></th>
<th><p>Calculation</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>All hours, no expenses</p></td>
<td><p>Dollar cost</p></td>
<td><p>37 percent</p></td>
<td><p>35 x USD 50 + USD 100 = USD 1,850</p>
<p>USD 1,850 / USD 5,000</p></td>
</tr>
<tr class="even">
<td><p>All hours, no expenses</p></td>
<td><p>Units</p></td>
<td><p>40 percent</p></td>
<td><p>40 hours/100 hours (including five unplanned hours)</p></td>
</tr>
<tr class="odd">
<td><p>Planned hours, no expenses</p></td>
<td><p>Dollar cost or unit</p></td>
<td><p>35 percent</p></td>
<td><p>35 / 100 hours</p>
<p>or</p>
<p>35 x USD 50 /5,000</p></td>
</tr>
<tr class="even">
<td><p>All hours and expenses</p></td>
<td><p>Dollar cost</p></td>
<td><p>27.2 percent</p></td>
<td><p>USD 1,850/ USD 6,800</p></td>
</tr>
</tbody>
</table>


Deciding which approach to take to create a cost template can depend on several considerations:

  - If you include unplanned hours in the cost template, you risk reaching 100 percent complete before the project is finished. This is because actual hours will be greater than planned hours. Therefore, if you use either of the first two methods listed in the earlier table, you should change the plan (forecasted units) when you become aware of deviations. In this case you would add or subtract hours based on your knowledge of what is required to finish the project. If the project will require another 65 hours to complete, you would add five hours to the plan for a total of 105. If you know that your assistant will have to perform another five hours of research, the total will be 110 hours, and so on.

  - If you use the third method listed in the table, you would only update the planned hours for your own time to keep the percent-complete calculation accurate. Your profitability will change when unplanned hours are logged, but you will remain on a known percent-complete trajectory.

  - If you use the fourth method listed in the table, the risk is that expenses will occur at irregular times and may not be reflected in your completion progress. Therefore, if the expenses are included, they can cause your percent complete to fluctuate more than is desirable. For example, because you did not take a flight yet, your percent complete was 27 percent instead of 35 percent or 37 percent if you were to base the calculation on time alone. If you had taken one trip for two nights and were able to forecast your flight and hotel costs accurately, the percent complete would have been 40.4 percent (USD 1850 for labor and USD 900 for expenses = USD 2750 / USD 6800 = 40.4 percent). Therefore, incurring the expenses for just one plane trip would change the percent complete from 27 percent to 40 percent.

## See also

[Create a cost template](create-a-cost-template.md)

[Cost template (form)](https://technet.microsoft.com/en-us/library/aa616683\(v=ax.60\))

[Configuring category groups, categories, and cost templates](configuring-category-groups-categories-and-cost-templates.md)

[Estimate (form)](https://technet.microsoft.com/en-us/library/aa590971\(v=ax.60\))

[Attach a project to an estimate](attach-a-project-to-an-estimate.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

