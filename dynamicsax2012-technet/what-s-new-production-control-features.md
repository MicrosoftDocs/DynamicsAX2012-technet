---
title: "What's new: Production control features"
TOCTitle: Production control features
ms:assetid: 91bc99f6-4530-4fa1-8617-96e767ad0e1d
ms:mtpsurl: https://technet.microsoft.com/library/Dn527181(v=AX.60)
ms:contentKeyID: 59623310
author: Khairunj
ms.date: 12/10/2014
mtps_version: v=AX.60
---

# What's new: Production control features 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

We have changed and added functionality in the [Production control](production-control.md) area for Microsoft Dynamics AX 2012. To learn more, refer to the tables that apply to your version of the product.

## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 8

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use additional production processes in a warehouse</p></td>
<td><p>It’s now possible to use the following production processes in a warehouse:</p>
<ul>
<li><p>Deliver picked materials to the exact locations where the materials are consumed in production.</p></li>
<li><p>Define a specific output location for a production order or a batch order. This enables the warehouse worker to know exactly where to pick up the goods for put away work.</p></li>
<li><p>Generate put away work for warehouse-enabled items when you use the reporting as finish process on the client. (Previously you could only do this from a Microsoft Dynamics AX mobile device.)</p></li>
</ul>
<p>For more information, see blog posts on the <a href="https://blogs.msdn.com/b/axmfg/">Dynamics AX Manufacturing R&amp;D Team blog</a> and <a href="set-up-production-processes-in-a-warehouse.md">Set up production processes in a warehouse</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Additional options are introduced that affect the release step and material reservations for production orders</p></td>
<td><p>A new option for automating material reservations has been added to the <strong>Reservation</strong> field in the <strong>Production orders</strong> form, where the value is set for a specific production order. A new option has also been added to the <strong>Production control parameters</strong> form, where the default value is specified.</p>
<p>If you select <strong>Release</strong>, all materials are reserved when the production order is released.</p>
<p>If you use production processes in the <strong>Warehouse management</strong> module, some new options are available. A <strong>Release to warehouse</strong> field has been added to certain production forms, and contains the following options:</p>
<ul>
<li><p><strong>Require full reservation</strong> – Select this option if you want to create wave lines and picking work only if all of the materials that are required by a production order can be reserved when the order is released. If all materials are not available, wave lines and work are not created. However, the status of the production will change to <strong>Released</strong>.</p></li>
<li><p><strong>Allow partial reservation</strong> – Select this option if you want to create wave lines even though some of the materials that are required by a production order are not available when the order is released. If the materials become available later, you can release the order again by using the new <strong>Release to warehouse</strong> button.</p></li>
</ul>
<p>A new <strong>Release to warehouse</strong> button has been added to the <strong>Production orders</strong> form. This button will create a wave line for any reserved quantity on the bill of materials lines that is not already associated with a wave line. This button is used when the production order has a status of <strong>Released</strong>, and you must release additional materials to the warehouse.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 7 for Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Case management functionality is enhanced for documenting and releasing product changes to production</p></td>
<td><p>The Case management functionality now provides tools for documenting changes to a product. For example, you can track component substitutions in the bill of materials of formulas, or changes in the production route. Approvals and validations can be automated, so that you can manage the release of bills of materials, routes, and formulas to production processes.</p>
<p>For more information, see <a href="case-management.md">Case management</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 6 for Microsoft Dynamics AX 2012

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Constraint time modifications for production flow versions</p>
<p>(Lean manufacturing)</p></td>
<td><p>You can modify the activity relations in the production flow versions by using the <strong>Edit activity relation</strong> form. In earlier versions of Microsoft Dynamics AX, you entered start and end constraint times for an activity relation when you created it. Afterward, you could not change the constraint times. The same restriction applied for the cycle time ratios of the activity relation, which adjust the calculation of cycle times for the activities of a production flow based on the required takt time of the production flow version.</p>
<p>For more information, see <a href="key-tasks-set-up-a-production-flow.md">Key tasks: Set up a production flow</a>.</p></td>
</tr>
<tr class="even">
<td><p>Material date calculation for kanban jobs – Period-based versus job-based</p>
<p>(Lean manufacturing)</p></td>
<td><p>The material date calculation is based on the actual job schedule. When a job is sequenced in the schedule, the material date and time are recalculated based on the expected receipt date and time of the job. In Microsoft Dynamics AX 2012, the material date and time was always set to the start of the period, which caused dependent jobs to exceed their due date.</p>
<p>For more information, see the topic titled <a href="https://technet.microsoft.com/library/hh597153(v=ax.60)">Kanban schedule board (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Explosion of scheduled withdrawal kanbans that have automatic firming</p>
<p>(Lean manufacturing)</p></td>
<td><p>In previous releases, when capable to promise (CTP) explosion firmed a withdrawal kanban for a scheduled rule, the pegging to the required material was incorrect and the dynamic plan was inaccurate. This problem is fixed.</p></td>
</tr>
<tr class="even">
<td><p>Capable to promise moves a planned kanban based on the futures date</p>
<p>(Lean manufacturing)</p></td>
<td><p>You can now combine event kanbans together with CTP. The ability to move firmed orders based on CTP is limited to event kanbans, and occurs only when sales order lines are created. Further application of moving orders requires additional supply policies to ensure that planning is accurate.</p>
<p>To support forward scheduling of kanban jobs based on futures dates, you can move planned kanban jobs to later periods. This capability is also useful in the kanban scheduling board, where the new <strong>Schedule from date</strong> function has been added. When you schedule jobs for a futures date, the jobs are added at the end of the planning period, and planned according to the capacity that is available on the date. As opposed to automatic planning, the schedule from date function enables you to schedule jobs past the planning fence that is defined in the production flow model.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/hh597153(v=ax.60)">Kanban schedule board (form)</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Define a formula, and perform batch balancing of a potency item used in production</p>
<p>(Process manufacturing, production, and logistics)</p></td>
<td><p>You can use potency management to define an item as having a specific concentration of an active ingredient, adjust the quantity of material that is required in the production of the item, calculate the amount of money that is paid to a vendor for the item, and select an ingredient type for a formula line.</p>
<p>For more information, see the topic titled <a href="about-potency-management.md">About potency management</a>.</p></td>
</tr>
<tr class="even">
<td><p>Configure an item to inherit shelf life and batch attributes from intermediate items of the finished goods</p>
<p>(Process manufacturing, production, and logistics)</p></td>
<td><p>You can configure an item to update its batch attributes and shelf life information from the ingredients of the formula that is used to produce the item. You can use shelf life inheritance to define items so that the inventory batch with the earliest shelf life dates is updated or inherited by the product characteristics of the finished items. For batch attributes, you can define attributes for both the finished items and their ingredients, and select which ingredients pass along their characteristics or attribute values to the finished items. You can also select to have co-products updated with this same shelf life and batch attributes.</p>
<p>For more information, see the topic titled <a href="define-formula-ingredients-for-shelf-life-inheritance.md">Define formula ingredients for shelf life inheritance</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create an attribute-based pricing formula for a potency item</p>
<p>(Process manufacturing, production, and logistics)</p></td>
<td><p>You can set up a batch attribute-based pricing formula for a potency item. You can define certain items that can be invoiced based on the actual potency of the material received.</p>
<p>For more information, see the topic titled <a href="set-up-an-attribute-based-pricing-formula-for-a-potency-item.md">Set up an attribute-based pricing formula for a potency item</a>.</p></td>
</tr>
<tr class="even">
<td><p>Add a batch attribute actual value to a registered inventory batch</p>
<p>(Process manufacturing, production, and logistics)</p></td>
<td><p>You can add the actual value of a base inventory batch attribute to the registered inventory batch of a purchase order.</p>
<p>For more information, see the topic titled <a href="add-batch-attribute-actual-values-to-a-registered-inventory-batch.md">Add batch attribute actual values to a registered inventory batch</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create sequences for production</p>
<p>(Process manufacturing, production, and logistics)</p></td>
<td><p>You can use product sequencing to define one or more sequences to assign to a various item. Product sequencing provides a method to sort production into a required order so that the changeover times are automatically reduced in production.</p>
<p>For more information, see the topic titled <a href="set-up-product-sequences.md">Set up product sequences</a>.</p></td>
</tr>
<tr class="even">
<td><p>Updated features for lean manufacturing</p>
<p>(Lean manufacturing)</p></td>
<td><p><strong>Reverse empty kanbans</strong></p>
<p></p>
<p>You can reverse the status of a handling unit that is assigned to a kanban, from <strong>Empty</strong> to <strong>Received</strong>. This may be necessary if a user erroneously registers the status as <strong>Empty</strong>. When you reverse the status of the handling unit, the following conditions apply:</p>
<ul>
<li><p>The status of the handling unit changes from <strong>Empty</strong> to <strong>Received</strong>.</p></li>
<li><p>The transactions for consumption from kanban supermarkets are reversed.</p></li>
<li><p>For kanbans that are generated for a fixed-quantity kanban rule, the invalid kanban that was generated may be deleted.</p></li>
<li><p>If circulating cards are used, the connection between the kanban and a kanban card is reestablished.</p></li>
</ul>
<p>For more information, see the topic titled <a href="https://technet.microsoft.com/library/jj677366(v=ax.60)">Reverse empty handling unit (form)</a>.</p>
<p><strong>Flush material on any activity</strong></p>
<p>For production flows that consist of multiple process activities, you can assign picking activities for specific item and product dimensions to any of the activities. This also applies to activities that consume semi finished products. When kanbans are created, the Kanban board for process jobs displays the picking lines for each job, and material consumption is registered against the corresponding job. Forward-flushed material is registered when a job is prepared. Back-flushed material is registered when a job is completed.</p>
<p></p>
<p>This feature changes the way that picking lines for kanbans that span over multiple activities are saved to the database. In Microsoft Dynamics AX, picking lines for kanbans are associated with the first activity, regardless of the flushing principle of the item on the BOM (bill of materials) line. In Microsoft Dynamics AX 2012 R2, picking lines that have the finish flushing principle are associated with the last activity of the kanban by default.</p>
<p>A migration script upgrades active kanbans that have multiple activities to the new model.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>User interface updates and new functionality for manufacturing execution and time and attendance features</p></td>
<td><p>Workflow for worker registrations – A new workflow approval process is used for the approval of worker registrations. The workflow determines who can approve registrations and whether automatic approval of registrations is allowed. A new calculation engine for calculating time registrations has also been implemented.</p>
<ul>
<li><p>The previous Employee form is obsolete – The Employee form, which was used in Shop floor control in previous versions, is obsolete. The data from that form is now incorporated into the Worker form in Human resources.</p></li>
<li><p>Updated pay engine – The pay engine has been redesigned so that time registrations are posted on a daily basis by using a standard cost price. When a production order or project is completed, the real cost price is calculated if a supervisor or a manager selects to use real cost price calculation. This approach enables real costs to be calculated at the end of a production order or project, based on the payroll transactions generated continuously through the duration of that production order or project.</p></li>
</ul>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="approve-time-and-attendance-registrations.md">Approve time and attendance registrations</a></p></li>
<li><p><a href="https://technet.microsoft.com/library/hh209054(v=ax.60)">Worker (form)</a></p></li>
<li><p><a href="analyze-production-costs.md">Analyze production costs</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Production and sales schedule</p></td>
<td><p>Use the <strong>Supply schedule</strong> form to see an overview of the current demand and supply situation for a product or product family. In the form, you can do the following:</p>
<ul>
<li><p>View product supply information that is filtered according to location, master plan, and time period.</p></li>
<li><p>Monitor and analyze the supply situation.</p></li>
<li><p>Make changes to the planned supply.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Shop floor control module is divided into two new feature sets</p></td>
<td><p>The Shop floor control (SFC) module has changed considerably in Microsoft Dynamics AX 2012. It is no longer called Shop floor control, and has been divided into the following feature areas:</p>
<ul>
<li><p>Time and attendance - Time and attendance features contain all previous SFC functionality for registering work time, such as clock-in and clock-out and registration on indirect activities, and attendance registration, such as absence registration. Time and attendance includes features to generate payroll information that a payroll system can use to calculate pay for workers. These features are available from the Human resources menu.</p>
<p>For more information, see the topic titled <a href="setting-up-time-and-attendance-information.md">Setting up time and attendance information</a>.</p></li>
<li><p>Manufacturing execution - Workers can create and transfer time registrations for specific production jobs or projects by using a job list registration form. Registration features for time, item consumption, and projects are available from the Production information management and Project management and accounting menus.</p>
<p>For more information, see the topic titled <a href="key-tasks-set-up-manufacturing-execution.md">Key tasks: Set up manufacturing execution</a>.</p></li>
</ul>
<p>Features for time and attendance and manufacturing execution can be used separately. However, using both sets of features provides the full functionality of the previous SFC module, level 3, including various extensions and updates for Microsoft Dynamics AX 2012.</p>
<p>The layout of the Registration form in manufacturing execution has been updated, and you can also use it to do the following:</p>
<ul>
<li><p>View the daily balance and logbook.</p></li>
<li><p>View attachments connected to a job or an operation.</p></li>
<li><p>View and print current activities.</p></li>
</ul>
<p>For more information, see the topic titled <a href="about-registration-for-manufacturing-execution.md">About registration for manufacturing execution</a>.</p></td>
</tr>
<tr class="even">
<td><p>Use the Period template to define schedules</p></td>
<td><p>You can set up a new period template that filters and displays data in user-defined time buckets. The template can give structure to large volumes of data, such as sales orders and forecast plans, by grouping the data in a time frame. The period template is introduced to display the master scheduling requirements. You can also use the template to create any type of schedule, such as a production, purchase, sales, and final assembly schedule.</p>
<p>For more information, see the topic titled <a href="https://technet.microsoft.com/library/hh209650(v=ax.60)">Period templates (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Inventory quantity is calculated automatically for catch weight items</p></td>
<td><p>For catch weight items, the inventory quantity can no longer be specified or changed at the point of invoicing. The quantity is now calculated from the catch weight quantity that the user has entered and the weight that is registered on the inventory transactions.</p>
<p>For more information, see the topic titled <a href="about-catch-weight-items.md">About catch weight items</a>.</p></td>
</tr>
<tr class="even">
<td><p>Upgrade from Lean manufacturing for Microsoft Dynamics AX 2009</p>
<p>(Lean manufacturing)</p></td>
<td><p>The Microsoft Dynamics AX 2012 lean manufacturing architecture has fundamentally changed from Lean manufacturing for Microsoft Dynamics AX 2009 and previous versions. The code is new, so there is no code upgrade task. If you have an earlier version of lean manufacturing, you can migrate your current version data when you upgrade. However, you must perform several pre-upgrade tasks. These include the following:</p>
<ul>
<li><p>Create the new lean manufacturing setup data. The setup data includes production flows and activities, which are used to create kanbans and kanban rules.</p></li>
<li><p>Map your current version data to the new setup data, so that it can be converted during the upgrade.</p>
<p>For more information, see the topic titled <a href="about-lean-manufacturing-migration.md">About Lean manufacturing migration</a>.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Use production flows and activities to model a lean manufacturing foundation</p>
<p>(Lean manufacturing)</p></td>
<td><ul>
<li><p>Identify your company’s basic business processes and product families, and map them as production flows.</p></li>
<li><p>Describe each production flow as a sequence of activities. A transfer activity defines a movement of material. A process activity defines a value-added operation that is applied to a product.</p></li>
<li><p>Set up work cells as resource groups that can run process activities.</p></li>
<li><p>Set up production flow models to define the capacity settings for each work cell.</p></li>
</ul>
<p>More detailed information about production flows can be found in the white paper titled <a href="https://go.microsoft.com/fwlink/?linkid=213164%26clcid=0x409">Lean Manufacturing: Production Flows and Activities</a>.</p></td>
</tr>
<tr class="even">
<td><p>Implement a lean replenishment system by using kanbans to signal demand requirements</p>
<p>(Lean manufacturing)</p></td>
<td><p>You can use kanbans to plan, track, and run production and replenishment operations that are based on pull signals. To create a kanban framework, set up kanban rules that govern when a kanban requirement is created, what is replenished, and how the replenishment is fulfilled. When a kanban is created, one or more kanban jobs are generated based on the kanban flow activities that are defined in the kanban rule. The kanban jobs are scheduled for the assigned work cell, based on the production flow model.</p>
<p>For more information, see the topic titled <a href="about-lean-manufacturing.md">About lean manufacturing</a> and the white paper titled <a href="https://download.microsoft.com/download/5/1/d/51dc9131-9607-4b17-958a-08785dda6af2/lean+manufacturing_kanban+and+pull+based+manufacturing_ax2012.pdf">Lean Manufacturing: Kanban and Pull Based Manufacturing‎</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Set up kanban rules to implement different replenishment strategies</p>
<p>(Lean manufacturing)</p></td>
<td><ul>
<li><p>Set up fixed-quantity kanban rules to replenish material handling units that are consumed from inventory.</p></li>
<li><p>Set up scheduled kanban rules to replenish requirements that are generated from master planning.</p></li>
<li><p>Set up event kanban rules to replenish requirements that are generated from sales order lines, production BOM lines, kanban lines, and minimum inventory settings.</p></li>
</ul>
<p>For more information, see the topic titled <a href="key-tasks-create-a-kanban-rule.md">Key tasks: Create a kanban rule</a>.</p></td>
</tr>
<tr class="even">
<td><p>Plan kanban quantities to replenish target inventory levels</p>
<p>(Lean manufacturing)</p></td>
<td><p>When you use fixed-quantity kanbans, you can calculate kanban quantities that are based on the product demand during a specific period. The kanban quantity calculation can take into account the forecasted demand, the demand from open orders, the historical demand, and safety stock requirements.</p>
<p>For more information, see the topic titled <a href="about-lean-manufacturing.md">About lean manufacturing</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Use the Kanban boards to view, plan, and run kanban jobs that are scheduled for a work cell</p>
<p>(Lean manufacturing)</p></td>
<td><ul>
<li><p>Kanban board for transfer jobs – Provides an overview of the current transfer jobs. You can perform tasks, such as updating and registering picking lists, and starting and completing transfer jobs.</p></li>
<li><p>Kanban board for process jobs – Provides an overview of the current production situation for a work cell. The information is grouped and displayed by tab to support different production-related roles and their main tasks, such as scheduling upcoming jobs, preparing picking lists, monitoring kanban levels in supermarkets, and registering kanban job status.</p></li>
<li><p>Kanban schedule board – Provides an overview of the kanban jobs that are scheduled for a work cell. The kanban jobs and status are displayed in planning periods that are defined in the production flow model. The capacity percentage per planning period is also displayed, so that you can monitor the scheduled load. You can complete tasks such as changing the status of kanban jobs and rescheduling kanban jobs to different planning periods.</p></li>
</ul>
<p>For more information, see the topic titled <a href="about-selecting-jobs-in-the-kanban-board-for-transfer-jobs-by-using-a-bar-code-reader.md">About selecting jobs in the Kanban board for transfer jobs by using a bar code reader</a>.</p></td>
</tr>
<tr class="even">
<td><p>Integrate the kanban framework with Microsoft Dynamics AX inventory transaction processes</p>
<p>(Lean manufacturing)</p></td>
<td><ul>
<li><p>Print kanban cards, circulating cards, and picking lists to support the use of kanbans. These documents are used to represent, track, and register kanban jobs in the warehouse and on the production floor. You can set up the parameters for printing these documents in the kanban rules.</p></li>
<li><p>Replenish material that is used to fulfill kanban job requirements. Picking activities that support kanban process jobs and kanban transfer jobs are fully integrated with existing Microsoft Dynamics AX inventory transaction processes. In addition, you can use barcode scanning to register picking and transfer activities in inventory.</p></li>
<li><p>Use the capable to promise (CTP) feature to obtain accurate ship date information when you enter a sales order. When you register a sales order line, the ship date is calculated based on the availability of the products, material, and resources that are needed to fulfill a specific customer demand.</p></li>
</ul>
<p>For more information, see the topic titled <a href="about-lean-manufacturing.md">About lean manufacturing</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Lean manufacturing supports purchasing and invoicing processes for services that are related to production flow activities that are subcontracted</p>
<p>(Lean manufacturing)</p></td>
<td><p>You can set up production flow activities that are subcontracted, assign purchase agreement lines and services to subcontracted activities, and create periodic purchase orders and receipt advices to support purchasing and invoicing the services.</p>
<p>For more information, see the white paper titled <a href="https://download.microsoft.com/download/f/c/6/fc6a5ced-d2bb-4d94-a04f-b7c80abec063/lean_manufacturing_production_flow_and_activities_ax2012.pdf">Lean manufacturing: Production flows and activities‎</a>.</p></td>
</tr>
<tr class="even">
<td><p>New operations resource model for planning operations and managing work center capabilities</p>
<p>Scheduling</p></td>
<td><p>The way that resources are grouped for the purpose of managing capacity has been separated from the way resource requirements are specified for manufacturing activities.</p>
<p>This separation enables resources to be used at multiple locations, and it removes the need to define resources multiple times, depending on how they are used or what they are used for. In addition, available capacity can be viewed by resource capability, which simplifies manual scheduling and exception handling.</p>
<p>As a result, the Microsoft Dynamics AX 2009 manufacturing “work center” concept has been redefined and is now called “resource.”</p>
<p>Because the way production capacity is managed is now separate from the way manufacturing requirements are specified, you can do the following:</p>
<ul>
<li><p>Use the same equipment at multiple locations. For example, you can move equipment and operators to different production locations, as needed, thereby sharing production equipment and production operators across sites.</p></li>
<li><p>More easily reschedule an operation and find a suitable replacement resource that can complete the required operation, thereby minimizing production delays.</p></li>
<li><p>Define capabilities to an operation resource (previously known as a work center) and match any requirements of an operation with the capabilities of any particular resource, thereby facilitating the identification of available production resources.</p></li>
</ul>
<p>More detailed information about the Operations Resource Model can be found in the white paper titled <a href="https://go.microsoft.com/fwlink/?linkid=213134%26clcid=0x409">Implementing the Operations Resource Model for Microsoft Dynamics AX 2012 applications</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Operations resource model: capability-based production scheduling</p>
<p>(Scheduling)</p></td>
<td><p>In Microsoft Dynamics AX 2009, you could use task groups could to specify alternative work centers, but only when using job scheduling. In Microsoft Dynamics AX 2012, resources can be allocated to jobs and operations by matching the capabilities of the resources with the requirements of the operation.</p>
<p>In Microsoft Dynamics AX 2012, alternative resources with the same capabilities are taken into consideration. This applies, regardless of whether you run job scheduling or operations scheduling. The selection process is the same, and consists of matching the requirements of the operation with the capabilities of the resources. Other constraints, such as location, resource working time, and resource type, are also considered when the production is planned.</p>
<p>As a result, task groups have become obsolete in Microsoft Dynamics AX 20122, and they have been removed.</p>
<p>More detailed information about the Operations Resource Model can be found in the white paper titled <a href="https://go.microsoft.com/fwlink/?linkid=213134%26clcid=0x409">Implementing the Operations Resource Model for Microsoft Dynamics AX 2012 applications</a>.</p></td>
</tr>
</tbody>
</table>


## See also

[About production parameters in Manufacturing execution](about-production-parameters-in-manufacturing-execution.md)

[About operations scheduling](about-operations-scheduling.md)

[About lean manufacturing](about-lean-manufacturing.md)

[Working with Process manufacturing production and logistics](working-with-process-manufacturing-production-and-logistics.md)

  


