---
title: (IND) Sales tax hierarchies
TOCTitle: (IND) Sales tax hierarchies
ms:assetid: 1b865da6-19f0-4a13-8d2c-050319de6415
ms:mtpsurl: https://technet.microsoft.com/library/Dn479043(v=AX.60)
ms:contentKeyID: 59632411
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales tax
- sales tax hierarchy
- sales tax hierarchy structure
- sales tax payment
- sales tax settlement
audience: Application User
ms.search.region: India
---

# (IND) Sales tax hierarchies 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up sales tax information to settle sales tax and to generate sales tax payments. In Microsoft Dynamics AX, you can set up sales tax information such as tax types, tax components, and tax record types using sales tax hierarchies. You can then retrieve and use the sales tax information that you configure using the sales tax hierarchy during the settlement and payment process.

You can perform the following tasks to set up and use a sales tax hierarchy:

  - Set up the parameter to use the sales tax hierarchy.

  - Set up a sales tax hierarchy that is based on the default hierarchical structure. The levels of the sales tax hierarchy are determined by the structure.

  - Create a tax setoff rule that is used to set off the output tax using the input tax.

  - Set up and maintain a sales tax hierarchy profile. You can create multiple hierarchy profiles and versions based on your requirements.

  - Settle a sales tax transaction using the sales tax hierarchy, and then generate a sales tax payment.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



## What is a sales tax hierarchical structure and how can I use it?

Microsoft Dynamics AX provides a default sales tax hierarchical structure with multiple levels that do not refer to tax reporting codes, such as tax types, tax components, excise record types, or service accounting codes. You can set up a sales tax hierarchy that is based on the default structure, in which each node in the hierarchy represents the corresponding tax information, such as the tax component or the excise record type. You can then use the sales tax hierarchy to set up tax setoff rules, set up sales tax hierarchy profiles, and settle sales tax transactions.

## How many levels can I create in a sales tax hierarchy?

You can create multiple levels in a sales tax hierarchy based on your requirements. For example, you can set up a sales tax hierarchy to set off excise duty with three levels: tax type, tax component, and tax record type. However, for a hierarchy that is used to configure VAT, you can create a two level hierarchical structure with a tax type and a tax component.

## Can I create multiple sales tax hierarchies?

Yes. You can set up multiple sales tax hierarchies and multiple versions of a sales tax hierarchy based on your requirements. You can activate a sales tax hierarchy version and use it to set up a sales tax hierarchy profile. You can also customize the structure of the sales tax hierarchy based on your requirements, and then use the structure to set up a sales tax hierarchy.

## What actions can I perform on an existing sales tax hierarchy?

You can perform the following actions on an existing sales tax hierarchy:

  - Set up multiple versions of the sales tax hierarchy based on your requirements.

  - Copy the nodes and setoff rules for a selected sales tax hierarchy version to use as the template for a new hierarchy version.

  - Synchronize a sales tax hierarchy version to match the tax components that you have configured.

  - Activate a sales tax hierarchy version. When you activate a setoff hierarchy version, all of the unsettled transactions are validated and updated against the active hierarchy and version.

  - Enable or disable a selected node from a sales tax hierarchy.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(IND) Set up and use a sales tax hierarchy](ind-set-up-and-use-a-sales-tax-hierarchy.md)

  


