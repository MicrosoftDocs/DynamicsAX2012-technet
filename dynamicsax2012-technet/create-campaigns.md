---
title: Create campaigns
TOCTitle: Create campaigns
ms:assetid: 7635e393-4e36-4f08-9927-6aeb515e2cec
ms:mtpsurl: https://technet.microsoft.com/library/Aa550035(v=AX.60)
ms:contentKeyID: 36811410
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- campaigns
- campaign
audience: Application User
ms.search.region: Global
---

# Create campaigns 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Campaigns are created as part of the business process for marketing. When you create a campaign, you can also create subcampaigns for the campaign's targets, owners, or dates.

## Create a campaign

1.  Click **Sales and marketing** \> **Common** \> **Campaigns** \> **All campaigns**.

2.  On the **Action Pane**, on the **Campaign** tab, in the **New** group, click **Campaign**.

3.  In the **New campaign** form, in the **Status**, **Type**, **Group**, and **Target** fields, select a status, type, group, and target for the campaign.

4.  In the **Name** field, type a unique name for the campaign.

5.  If you want to create subcampaigns for the campaign, select a format for the identification numbers in the **Subcampaign ID format** field.

6.  If you want to attach a questionnaire to the campaign, select a questionnaire in the **Questionnaire** field.

7.  If necessary, select dates in the **Start date** and **End date** fields. The fields are filled in automatically, based on parameters that you specify in the **Campaigns** area in the **Sales and marketing parameters** form. All default values for campaigns are defined in the **Sales and marketing parameters** form, but the parameters can be changed if needed.

8.  Microsoft Dynamics AX 2012 R3 includes support for catalog source codes. If you want to associate a source code with the campaign, enter the source code in the **Source code** field. If you enter a code here, you receive a message that asks whether you want to import the list of customers for the target market that is associated with the source code. For more information, see [Set up catalog source codes](set-up-catalog-source-codes.md).
    
    The **Source code** field is available only if the **Call center** and **Source code** configuration keys are enabled.

## Create subcampaigns

1.  Click **Sales and marketing** \> **Common** \> **Campaigns** \> **All campaigns**.

2.  Select the campaign for which you want to create a subcampaign, and then on the **Action Pane**, in the **New** group, click **Subcampaigns**.

3.  In the **New campaign** form, if a format is not already specified for the active campaign, specify a format for the identification numbers in the **Subcampaign ID format** field.
    
    To specify a format, enter number signs (\#) to indicate how many digits you want to add to the original campaign number to identify its subcampaigns.
    
    For example, if you enter -\#\# as the format, two digits are added to the end of the original campaign number. If the original campaign number is 1003, and you create three subcampaigns, the subcampaigns have the numbers 1003-01, 1003-02, and 1003-03.

4.  Enter the relevant data in the fields. Each subcampaign inherits base data from the parent campaign. However, you must enter some data manually.


> [!NOTE]
> <P>You can attach new subcampaigns to existing subcampaigns. Select a format, and then click <STRONG>Subcampaigns</STRONG> to create a multilevel hierarchy for the campaign.</P>



## Campaign options

You can specify options for marketing campaigns by making selections in the **Campaigns** form. (Click **Sales and marketing** \> **Common** \> **Campaigns** \> **All campaigns**. Select or create a campaign.)

  - Obtain a financial overview of the costs of a campaign by connecting the campaign to a project. On the **Action Pane**, on the **General** tab, in the **Set up** group, click **Project** \> **Connect to existing project** or **New project**.

  - Add documents to the campaign. On the **Action Pane**, on the **Campaign** tab, in the **Attachments** group, click **Attachments**.

  - Assign responsibilities, add media information, and conduct a strength, weakness, opportunity, threat (SWOT) analysis. On the **Action Pane**, on the **General** tab, in the **Set up** group, click the relevant buttons.

  - Broadcast web responses for the campaign and set up e-mail templates. Select options on the **E-mail broadcast** FastTab.
    
    You can also change e-mail templates and save your changes for the selected campaign only.

  - Enter notes for the new campaign on the **Notes** FastTab.

## See also

[Add campaign targets](add-campaign-targets.md)

[Combine queries for campaign targets](combine-queries-for-campaign-targets.md)

[Define processes and stages for campaigns, leads, and opportunities](define-processes-and-stages-for-campaigns-leads-and-opportunities.md)

[Set up catalog source codes](set-up-catalog-source-codes.md)

  


