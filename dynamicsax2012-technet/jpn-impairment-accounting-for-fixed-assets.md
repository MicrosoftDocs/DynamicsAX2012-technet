---
title: (JPN) Impairment accounting for fixed assets
TOCTitle: (JPN) Impairment accounting for fixed assets
ms:assetid: bfc8ef29-1793-4ceb-b8b8-f58519813ae4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn530766(v=AX.60)
ms:contentKeyID: 59683046
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fixed assets
- fixed asset
- Japan
- impaired asset
- impaired assets
- impairment
- impairment accounting
- impairments
- JP - 00014
audience: Application User
ms.search.region: Japan
---

# (JPN) Impairment accounting for fixed assets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can perform the following tasks to set up and calculate fixed asset impairments using Microsoft Dynamics AX.

  - Generate a list of fixed assets that are possibly impaired. You can then review and calculate the undiscounted cash flow, fair value, or recoverable amounts of each asset in the list manually to determine whether the fixed assets are impaired.

  - Update impairment indicators, such as undiscounted cash flow of the fixed assets.

  - Run the impairment recognition test using the impairment indicators to generate a list of impaired fixed assets.

  - You can specify recoverable values that indicate the extent to which the fixed assets are impaired, and then create journal transactions for these impaired fixed assets. You can specify the details about the impairment before you post the journal.

  - View the details of the impairment transactions for fixed assets.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



## How can I identify impairments in fixed assets in AX 2012?

You can use impairment indicators to identify impairment in fixed assets. You can generate a list of fixed assets that are possibly impaired in the **Impairment review** form. You can calculate the undiscounted cash flow manually, and then update impairment indicators for the fixed assets in the **Update impairment indicators** form. When you run the impairment recognition test, you can use the impairment indicators that you updated to identify impairments in fixed assets.

## Can I select which assets I want to test for impairment?

Yes. You can select which assets you want to test for impairment. To specify the criteria, click **Query** in the **Impairment recognition test** form.

## How often can I check my fixed assets for impairment?

You can create a batch job to set up Microsoft Dynamics AX to check the fixed assets for impairment according to a schedule.

## Are there types of fixed assets that are excluded from impairment testing and accounting?

Yes. The following types of fixed assets are excluded from impairment testing and accounting:

  - Leased fixed assets

  - Goodwill fixed assets

## Can I generate reports that I can use to review impaired assets and impairment amounts?

Yes. You can generate the following reports that contain information about impaired assets and impairment accounting:

  - **Fixed asset transactions** report

  - **Fixed asset impairment transactions** report

  - **Review fixed assets for impairment** report

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(JPN) Set up impairment accounting for fixed assets](jpn-set-up-impairment-accounting-for-fixed-assets.md)

[(JPN) Identify impaired assets and post journals for impairment](jpn-identify-impaired-assets-and-post-journals-for-impairment.md)

  


