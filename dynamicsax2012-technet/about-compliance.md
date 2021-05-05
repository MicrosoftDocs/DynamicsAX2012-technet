---
title: About compliance
TOCTitle: About compliance
ms:assetid: 72714ad3-a947-431b-b841-0f4834483161
ms:mtpsurl: https://technet.microsoft.com/library/Hh271563(v=AX.60)
ms:contentKeyID: 36384194
author: Khairunj
ms.author: daxcpft
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- standard
- practices
- security
- controls
- audit
- procedures
- compliance
- operating
- EPComplianceHome
- detection
- effectiveness
- government
- industry
- organizations
- SOP
- SOPs
- standards
audience: Application User
ms.search.region: Global
---

# About compliance 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In business, compliance generally refers to the requirement to follow certain rules or laws, meet certain standards, and follow certain practices. Compliance standards can originate from external or internal sources, and a compliance requirement can be mandatory or optional. From tax reporting forms to how you place a label on a box for a customer, compliance requirements help drive the ways in which businesses operate.

The **Compliance** site provides a central location for users in your organization to manage the internal controls, business process content, and reporting for your organization's compliance program.

## Internal and external compliance requirements

Although internal compliance requirements might not seem as pressing as external requirements, they often provide more opportunity for improved business performance. For example, your organization might require that when a customer returns a product, the reason for the return must be recorded. This additional data requirement adds a step for the receiving department, but knowing why items are being returned can help you make adjustments that might reduce the number of returns in the future.

External compliance requirements are often either government- or industry-driven.

  - Government regulations – Government compliance regulations span the complete range of business operation activities from tax collection and reporting, to the verification of manufacturing quality and material tracing capabilities, to corporate governance.

  - Industry organizations – Prominent industry organizations can use their influence to try to protect certain interests, such as human safety and health or financial security. The industry-specific compliance requirements that apply to your organization depend on the work that your organization does.

An excellent understanding of the sources of compliance for your organization can help you plan ahead, and adopt and retire compliance requirements as those requirements and your organization evolve.

## Types of compliance requirements

Compliance requirements can affect the design standards, quality standards, processes, and reporting aspects of an organization. Compliance requirements fall into the following categories:

  - Standard operating procedures – Standard operating procedures can help make sure that efficient, consistent actions are used. They can be used as tools to train new people to perform a particular function or task.

  - Documented transactions – Many compliance requirements focus on recording exactly what occurred, when, and by whom. In many cases, the transaction should be captured as close as possible to the source of the transaction activity, with regard to both time and location.

  - Data integrity – If you document transactions electronically to meet compliance requirements, there must be assurances that the data is available, secure, and tamper proof. To help guarantee data integrity, systems and procedures, such as backup processors and disk systems, must be implemented to help make sure that data is available at all times.

  - Audit trails – In addition to other compliance requirements, there must be a trail of exactly what occurred with the data, when it changed, and who or what made the change. This trail of changes is often referred to as an audit trail.

  - Segregation of duties or responsibilities – In a chain of related processes, it is sometimes desirable to separate the authority of people so that they can manage only subsets of an activity. For example, if an individual enters an expense report, a different individual must approve it. Therefore, two or more people are required to complete the process. In some situations, an additional level of control is needed and a second individual must approve the transaction.

  - Detection mechanisms – It is important to identify, in a timely manner, activities or transactions that fail compliance requirements. A detection mechanism might be automated, such as system logic that identifies when a piece of data falls outside a certain range, or through an audit trail record. Manual detection mechanisms include transaction or process reviews by an auditor.

## Access the Compliance site

To access the **Compliance** site, click **Compliance** on the top link bar. The main areas of the **Compliance** site include the following:

  - **Compliance Home** – The central location for all compliance-related information. This page includes Web Parts that display alerts, key risk indicators (KRIs), control effectiveness, and document status information.

  - **Compliance resources** – A document library where compliance white papers and other resources are stored. For more information, see [About compliance resources](about-compliance-resources.md).

  - **Internal controls** – A control environment where internal controls for your organization are managed. For more information, see [Manage internal controls](manage-internal-controls.md).

  - **My substance entry** – A page where substance information is entered. For more information, see [My meter readings and substance entries](my-meter-readings-and-substance-entries.md).

  - **My meter entry** – A page where meter information is entered. For more information, see [My meter readings and substance entries](my-meter-readings-and-substance-entries.md).

  - **Process documentation** – A document library where all organizational business processes are stored. For more information, see [About process documentation](about-process-documentation.md).

  - **Database logs** – A filtered view of the database log for your organization. For more information, see [About database logs](about-database-logs.md).

  - **Audit cases** – A list of cases that are related to audit violations. For more information, see [About audit cases](about-audit-cases.md).

  - **Reports** – Compliance-related reports based on information from Microsoft Dynamics AX. For more information, see [About compliance reports](about-compliance-reports.md).

The following duties control access to the **Compliance** site:

  - **Inquire into audit policies**

  - **Maintain audit policies**

  - **Inquire into compliance policies**

  - **Enable compliance process**

  - **Review compliance process performance**

  - **Inquire into compliance reference data**

## Compliance charts

You can view the statistical status of your organization's internal controls, based on the documents on the **Compliance** site, by using the **Control Effectiveness** and **Document Status** charts that are displayed on the site home page. The control document template that is provided with the **Compliance** site contains a property called **Control Effectiveness**. When a control is tested, the owner of the control can set this property for the control.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Chart</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Control Effectiveness</strong></p></td>
<td><p>Displays the total number of control documents and their control effectiveness values. The following rating statuses are available:</p>
<ul>
<li><p><strong>Not effective</strong> – The control has been tested and is considered ineffective.</p></li>
<li><p><strong>Effective</strong> – The control has been tested and is considered effective.</p></li>
<li><p><strong>Not rated</strong> – The control has not been tested.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Document Status</strong></p></td>
<td><p>Displays the progress of all compliance document types or one specific document type. Progress is measured based on whether compliance workflow assignments have been marked as completed. The following progress statuses are available:</p>
<ul>
<li><p><strong>Not started</strong> – No compliance workflow assignments are marked as completed.</p></li>
<li><p><strong>In progress</strong> – At least one, but not all, compliance workflow assignment is marked as completed.</p></li>
<li><p><strong>Completed</strong> – All compliance workflow assignments are marked as completed. Document types that do not contain any workflow steps are also marked as completed.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Filter the Document Status chart

1.  Click **Compliance** on the top link bar. The **Compliance** site home page is displayed.

2.  In the **Document Status** Web Part, in the **Filter by** list, select the document type to view.
    

    > [!NOTE]
    > <P>The <STRONG>Filter by</STRONG> option is available only when more than one type of document has been created on the <STRONG>Internal controls</STRONG> page.</P>



## Related features

In addition to the **Compliance** site, you can use the following Microsoft Dynamics AX features to help guarantee compliance with applicable regulations:

  - Task recorder – Help create business process documentation.

  - Microsoft Active Directory directory service – Set security for users and user groups who have access to the network.

  - SharePoint site security – Set security for users and user groups who have access to Enterprise Portal for Microsoft Dynamics AX.

  - Role-based security – Set security for users and roles in Microsoft Dynamics AX. This includes external applications that interact with the system automatically.

  - Alerts – Monitor users who perform actions in Microsoft Dynamics AX.

  - Database log – Monitor users who change the database that stores Microsoft Dynamics AX transactional data.

  - Case management – Record, update, track, follow up on, and close issues that are raised by customers, vendors, or employees, or that are created through your audit processes.

  - Policies – Specify policies to evaluate expense reports, vendor invoices, and purchase orders for compliance with policy rules that you create. All of the rules that are associated with an audit policy are run in batch mode according to the schedule that you specify.

  - Audit cases – Group together multiple policy violations and associate them with cases.

  - Workflow – Set up workflow tasks that have optional approvals for business processes in Microsoft Dynamics AX.

  - Journal approvals – Sign off on financial journals based on specific criteria.

  - Electronic signature – Sign off on selected processes that are required for life sciences.

  - Audit trail – View related journals and transactions in General ledger, and track changes to tables that contain an electronic signature, and therefore must have an audit trail in order to comply with the FDA regulations in 21 CFR Part 11.

  - Planning and budgeting – Control expected expenditures.

  - Period close – Control expected expenditures.

  - Financial reporting – Analyze financial performance.

  - Transaction drill-down – View transactions.

## Troubleshooting compliance

## The Work list Web Part is empty

If the **Work list** Web Part is empty, alerts have not yet been set up and assigned to users.

  - Set up alerts or workflow notifications in the Microsoft Dynamics AX client.

## KRI Web Parts display errors

If errors appear in a KRI Web Part, the required Microsoft SQL Server Analysis Services cube or Microsoft SQL Server Reporting Services report has not been deployed.

  - Deploy the cube or report. For more information, see the Microsoft Dynamics AX Installation Guide.

## See also

[Working with internal controls](working-with-internal-controls.md)

[Audit activities and reporting](audit-activities-and-reporting.md)

  


