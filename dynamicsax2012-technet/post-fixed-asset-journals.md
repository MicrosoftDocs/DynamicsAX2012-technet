---
title: Post fixed asset journals
TOCTitle: Post fixed asset journals
ms:assetid: 900944e4-0335-4af6-97aa-a01b392002bc
ms:mtpsurl: https://technet.microsoft.com/library/Aa498367(v=AX.60)
ms:contentKeyID: 36058526
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- fixed assets
- asset
- fixed asset
- fixed asset journal
- fixed asset journals
- assets
- asset journal
- asset journals
audience: Application User
ms.search.region: Global
---

# Post fixed asset journals 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Each fixed asset transaction is posted to the general ledger. Typically, both a ledger account and a ledger offset account are affected. It is important to select the correct transaction type for fixed asset transactions because the transaction type connects the transaction to the posting profile. The posting profile determines which ledger accounts are used for posting in the general ledger.

1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**. Select a journal, and then click **Lines**.

2.  Enter the date of the transaction.

3.  Select the transaction type.

4.  In the **Account** field, select the fixed asset number.
    
    Based on the posting profile and the fixed asset transaction type, each fixed asset is posted to an account and an offset account in the general ledger.
    
      - The account is defined in the setup in the **Fixed asset posting profiles** form.
    
      - Only the offset account is displayed in the fixed assets journal and can be changed before posting. The default offset account is from the setup of the posting profile for each transaction type and value model. You can change the default value before posting.

5.  Select a value model.
    
    You can select from only the value models that are set up for the posting layer of the journal. For example, if the posting layer for the journal is **Tax**, only value models that have the **Tax** posting layer are available.

6.  Enter transaction text for manual transactions. For more information, see [Journal descriptions - General ledger (form)](https://technet.microsoft.com/library/aa500456\(v=ax.60\)).

7.  On the **General** tab, select a reason for the transaction. You can use codes that are set up in the **Asset reasons** form.
    

    > [!NOTE]
    > <P>Reason code requirements that are set up in the <STRONG>Fixed assets parameters</STRONG> form determine whether a reason code is required for the type of transaction that you are entering.</P>

    
    The voucher lines are allocated according to the information in the **Journal names** form.

8.  On the **Value models** tab, view, create, or adjust derived fixed asset transactions. See [About derived value models](about-derived-value-models.md) and [About posting with derived value models](about-posting-with-derived-value-models.md).

9.  Validate and post the journal.
    

    > [!NOTE]
    > <P>If you cannot post and you receive a message that mentions posting restrictions, you might be set up to post only journals that you created. For more information, see <A href="https://technet.microsoft.com/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



## Transaction proposals in the Fixed assets journal and General journal

The purpose of transaction proposals is to create suggested journal lines for fixed asset transactions to simplify transaction entry. These suggestions are based on the general setup of Fixed assets, and on the setup of each fixed asset. You can access the proposals by clicking the buttons in journal lines and by using queries for ranges and sorting of the fixed asset or value model, for which transactions have to be suggested. For all journal lines that are created by using proposals, transaction text is suggested. All information that is transferred to the journal lines from the proposals can be adjusted and posted as with other journal lines.

## Proposals

## Acquisition proposal

Create journal lines for fixed assets that have a **Not yet acquired** status, and where an acquisition date and an acquisition price have been set up for the fixed asset or value model. The suggested transaction type is **Acquisition**.

## Acquisition adjustment proposal

Create journal lines for fixed assets that have a status of **Open**. The suggested transaction type is **Acquisition adjustment**.

## Depreciation proposal

Create journal lines for the periodic depreciation calculation, based on the setup of the depreciation profile for each value model, and the date in the **To date** field.

Depreciation proposals are the most important proposals for periodic financial statements. They save time because depreciation for all fixed assets can be calculated and posted in a single operation.

Depreciation proposals consider only fixed assets that have an **Open** status and that are depreciable. As for time intervals, depreciation proposals calculate depreciation for depreciation periods in which the depreciation has not yet been posted.

Although only fixed assets with an **Open** status can be depreciated, you still can start the depreciation of an asset before the acquisition. A fixed asset that is acquired on May 15 can be depreciated from January 1 of the same year, but the depreciation is not calculated before an acquisition has been posted.

## Consumption depreciation

Create consumption depreciation proposal lines for value models that have depreciation profiles with **Consumption** as the depreciation method.

For more information, see [About consumption depreciation](about-consumption-depreciation.md) and [Create consumption proposal (form)](https://technet.microsoft.com/library/aa618495\(v=ax.60\)).

## Revaluation proposal

Create revaluation proposal lines through the date in the **To date** field for fixed assets that are set up for revaluation. These are assets that have a revaluation group assigned to the asset or value model.

Transactions that are suggested in the revaluation proposal are created according to the setup of each particular revaluation group. In the **Revaluation groups** form, specify the percentages for revaluation and the date when each percentage is valid.

## Revenue recognition of reserves

Create a proposal for revenue recognition of reserves. This is used for the dissolution of reserves that are created when assets are sold for a profit.

When the proposal is activated for the posting date for the fixed assets selected in the query, a reversal of the posted profit reserves is suggested. Two options for reserve reversal are available:

  - For reserves that have not expired, a transaction without an account is suggested. You should enter the account using the number of the new asset. The value of this asset, and the basis for future depreciation of this asset, is reduced by the amount of the reserve.

  - For reserves that have expired, according to the setup of the provision type, the account selected in the **Account for revenue recognition of untransferred reserves** field in the **Fixed assets parameters** form is suggested.

You can modify the default entries in the journal lines before posting.

## Extraordinary depreciation proposal

Create an extraordinary depreciation proposal through the date in the **To date** field. This proposal concerns only fixed assets that are attached to a value model that has been set up with a depreciation profile for extraordinary depreciation.

Extraordinary depreciation works just like a depreciation proposal, but the extraordinary depreciation profile of the fixed asset is used instead of the depreciation profile in the depreciation calculation.

Fixed assets that have an extraordinary depreciation profile set up usually have both a depreciation profile and an extraordinary depreciation profile. Both proposals are used for the same fixed asset.

## Disposal – scrap proposal

Create journal lines for the disposal of scrap assets (assets that are no longer considered usable) based on the setup of the disposal - scrap profile for each value model, and the filters applied. You can use **Disposal - scrap** proposals to dispose of multiple assets at the same time, based on filter criteria. The sales of the assets are entered individually as journals or free text invoices.

**Disposal - scrap** proposals consider only fixed assets that have a status of **Open**.


> [!NOTE]
> <P>Disposal – scrap proposals are available only if cumulative update 7 for Microsoft Dynamics AX 2012 R2 is installed, and only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>



## See also

[Fixed asset posting profiles (form)](https://technet.microsoft.com/library/aa571467\(v=ax.60\))

[Fixed asset depreciation profile schedules (form)](https://technet.microsoft.com/library/aa575368\(v=ax.60\))

[About fixed asset acquisitions](about-fixed-asset-acquisitions.md)

[About depreciation](about-depreciation.md)

[Create revaluation adjustments for fixed assets](create-revaluation-adjustments-for-fixed-assets.md)

[About fixed asset disposal](about-fixed-asset-disposal.md)

[About fixed asset reserves](about-fixed-asset-reserves.md)

[About financial reason codes](about-financial-reason-codes.md)

  


