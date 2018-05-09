---
title: Accounts payable setup overview
TOCTitle: Accounts payable setup overview
ms:assetid: 6a9bdc61-b19e-4cea-8890-805a4ccba8b2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231776(v=AX.60)
ms:contentKeyID: 36057980
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Accounts payable setup overview 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this topic as your guide to setting up Accounts payable.

## Prerequisites

Set up the following modules:

  - **System administration**

  - **Organization administration**

  - **General ledger**
    
      - If you plan to use payment journals, you must first set up payment journals. (Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.)
    
      - If you plan to run exchange rate adjustments, you must set up currency codes in the **Currencies** form, exchange rate types in the **Exchange rate types** form, and currency exchange rates in the **Currency exchange rates** form.

  - In **Cash and bank management**, set up bank accounts to use with methods of payment.

## Main setup forms for Accounts payable

Use the following forms to set up the basic functionality of Accounts payable for each legal entity. The forms are listed in the recommended order of setup.

To make the setup process simpler, you can create templates from the first records that are created. A template typically includes entries in many fields that reflect the features that the organization wants to implement for a particular type of vendor.

1.  Define the terms of payment that you assign to sales orders, purchase orders, customers, and vendors, and that determine invoice due dates, in the **Terms of payment** form.
    
    For complete guidelines, see [Terms of payment (form)](https://technet.microsoft.com/en-us/library/aa588427\(v=ax.60\)).

2.  Create and maintain information about how the organization pays its vendors in the **Methods of payment - vendors** form.
    
    For complete guidelines, see [Methods of payment - vendors (form)](https://technet.microsoft.com/en-us/library/aa618565\(v=ax.60\)).

3.  Create and maintain groups of vendors that share key parameters for posting, settlement and payment, reporting, and forecasting in the **Vendor groups** form.
    
    For complete guidelines, see [Vendor groups (form)](https://technet.microsoft.com/en-us/library/aa550420\(v=ax.60\)).

4.  Set up the way in which vendor transactions are posted to the general ledger in the **Vendor posting profiles** form.
    
    For complete guidelines, see [Vendor posting profiles (form)](https://technet.microsoft.com/en-us/library/aa551972\(v=ax.60\)).

5.  Set up default settings that are applied if a more specific setting is not specified, parameters for various kinds of functionality, and various number sequences for Accounts payable in the **Accounts payable parameters** form.
    
    For complete guidelines, see [Accounts payable parameters (form)](https://technet.microsoft.com/en-us/library/aa596348\(v=ax.60\)).

6.  Define the format of various documents that are related to vendors, and that are used in the organization to keep track of receipts from vendors and to enter reasons for the flow of payments to vendors, in the **Form setup** form.

7.  Create and maintain vendor accounts, including the tax authorities to whom your organization reports sales taxes, in the **Vendors** form.
    
    For complete guidelines, see [Vendors (form)](https://technet.microsoft.com/en-us/library/aa592162\(v=ax.60\)).

## Optional setup forms for Accounts payable

The setup of Accounts payable includes several other steps beyond the basic functionality.

The additional setup forms are organized by functionality.

## Policies

  - Set up vendor invoice policies in the **Vendor invoice policy** form.
    
    For complete guidelines, see [Vendor invoice policy (form)](https://technet.microsoft.com/en-us/library/hh209409\(v=ax.60\)).

## Invoice matching

  - Set up invoice totals tolerances in the **Invoice totals tolerances** form.
    
    For complete guidelines, see [Invoice totals tolerances (form)](https://technet.microsoft.com/en-us/library/hh209369\(v=ax.60\)) and [Set up Accounts payable invoice matching](set-up-accounts-payable-invoice-matching.md).

  - Set up two-way and three-way matching policies in the **Matching policy** form.
    
    For complete guidelines, see [Matching policy (form)](https://technet.microsoft.com/en-us/library/hh209508\(v=ax.60\)), [Set up Accounts payable invoice matching](set-up-accounts-payable-invoice-matching.md), and [Examples: Three-way matching policies](examples-three-way-matching-policies.md).

  - Set up unit price tolerances in the **Price tolerances** form.
    
    For complete guidelines, see [Price tolerances (form)](https://technet.microsoft.com/en-us/library/hh209247\(v=ax.60\)) and [Set up Accounts payable invoice matching](set-up-accounts-payable-invoice-matching.md).

  - Set up item price tolerances in the **Item price tolerance groups** form.
    
    For complete guidelines, see [Item price tolerance groups (form)](https://technet.microsoft.com/en-us/library/hh209702\(v=ax.60\)) and [Set up Accounts payable invoice matching](set-up-accounts-payable-invoice-matching.md).

  - Set up vendor price tolerance groups in the **Vendor price tolerance groups** form.
    
    For complete guidelines, see [Vendor price tolerance groups (form)](https://technet.microsoft.com/en-us/library/hh242256\(v=ax.60\)) and [Set up Accounts payable invoice matching](set-up-accounts-payable-invoice-matching.md).

  - Set up charges tolerances in the **Charges tolerances** form.
    
    For complete guidelines, see [Charges tolerances (form)](https://technet.microsoft.com/en-us/library/hh227600\(v=ax.60\)) and [Set up Accounts payable invoice matching](set-up-accounts-payable-invoice-matching.md).

## Workflow

  - Set up workflow configurations for journal approvals and purchase requisitions in the **Accounts payable workflows** form.
    
    For complete guidelines, see [Workflows (list page)](https://technet.microsoft.com/en-us/library/hh209721\(v=ax.60\)).

## Reasons

  - Set up reason codes in the **Vendor reasons** form to manage vendor reason codes.
    
    For complete guidelines, see [Reasons (form)](https://technet.microsoft.com/en-us/library/hh209362\(v=ax.60\)).

## Charges

  - Set up codes for the charges to use in purchase orders in the **Charges code** form.
    
    For complete guidelines, see [Charges code (form)](https://technet.microsoft.com/en-us/library/aa598932\(v=ax.60\)).

  - Create and maintain charges groups for vendors in the **Vendor charges group** form.
    
    For complete guidelines, see [Charges groups (form)](https://technet.microsoft.com/en-us/library/aa617452\(v=ax.60\)).

  - Create and maintain charges groups for items in the **Item charge groups** form.
    
    For complete guidelines, see [Charges groups (form)](https://technet.microsoft.com/en-us/library/aa617452\(v=ax.60\)).

  - Define the charges to automatically assign to orders in the **Auto charges** form.
    
    For complete guidelines, see [Auto charges (form)](https://technet.microsoft.com/en-us/library/aa582856\(v=ax.60\)).

## Supplementary items

  - Create and maintain supplementary item groups for vendors in the **Supplementary item groups** **-** **Vendor** form.

  - Create and maintain supplementary item groups for items in the **Supplementary item groups** **-** **Inventory** form.

## Distribution

  - Create and maintain the conditions for an item's transfer from seller to buyer in the **Terms of delivery** form.
    
    For complete guidelines, see [Terms of delivery (form)](https://technet.microsoft.com/en-us/library/aa575567\(v=ax.60\)).

  - Create and maintain the means of transport used when delivering an order from the seller to the buyer in the **Modes of delivery** form.
    
    For complete guidelines, see [Modes of delivery (form)](https://technet.microsoft.com/en-us/library/aa619881\(v=ax.60\)).

  - Create and maintain identifiers and descriptions for delivery destinations in the **Destination codes** form.
    
    For complete guidelines, see [Destination codes (form)](https://technet.microsoft.com/en-us/library/aa574145\(v=ax.60\)).

## Forms

  - Create the standard text that appears in various forms in the **Form notes** form.

  - Set up the sorting orders for requisitions, receipt lists, packing slips, and invoices in the **Form sorting parameters** form.

  - Set up print management information for originals and copies of forms in the **Print management setup** form.
    
    For complete guidelines, see [Print management setup (form)](https://technet.microsoft.com/en-us/library/hh209383\(v=ax.60\)).

## Payments

  - Set up and manage the terms for obtaining cash discounts in the **Cash discounts** form. The cash discount codes are linked to vendors and are applied to purchase orders.
    
    For complete guidelines, see [Cash discounts (form)](https://technet.microsoft.com/en-us/library/aa590275\(v=ax.60\)).

  - Set up payment schedules to manage installment payments to vendors in the **Payment schedules** form.
    
    For complete guidelines, see [Payment schedules (form)](https://technet.microsoft.com/en-us/library/aa572068\(v=ax.60\)).

  - Define the payment days that are used for the calculation of due dates, and specify payment days for a specific day of the week or month, in the **Payment days** form.
    
    For complete guidelines, see [Payment days (form)](https://technet.microsoft.com/en-us/library/aa553269\(v=ax.60\)).

  - Create and maintain payment fees that are associated with vendors in the **Payment fee** form.
    
    For complete guidelines, see [Vendor payment fee (form)](https://technet.microsoft.com/en-us/library/aa573151\(v=ax.60\)).

  - Create and maintain payment instructions in the **Payment instruction** form.
    
    For complete guidelines, see [Payment instruction (form)](https://technet.microsoft.com/en-us/library/aa615922\(v=ax.60\)).

## Statistics

  - Set up user-defined intervals to analyze the maturity distribution of vendor accounts in the **Aging period definitions** form.
    
    For complete guidelines, see [Aging period definitions (form)](https://technet.microsoft.com/en-us/library/aa634713\(v=ax.60\)).

  - Create line of business codes that you assign to vendors in the **Line of business** form.
    
    For complete guidelines, see [Line of business (form)](https://technet.microsoft.com/en-us/library/aa619191\(v=ax.60\)).

## (USA) Tax 1099

  - Verify and update, according to the latest IRS requirements, the minimum amounts that must be reported to the IRS in the **1099 fields** form.
    
    For complete guidelines, see [(USA) 1099 fields (form)](https://technet.microsoft.com/en-us/library/aa599780\(v=ax.60\)).

## Optional setup

## Organization administration

  - Set up invoice number sequence groups in the **Number sequences** form. (Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**. On the **Action Pane**, click **Number sequence**.)
    
    For complete guidelines, see [Number sequences (list page)](https://technet.microsoft.com/en-us/library/aa600321\(v=ax.60\)).

  - Set up address setup forms (**Organization administration** \> **Setup** \> **Addresses**):
    
      - **Address setup**
        
        For complete guidelines, see [Address setup (form)](https://technet.microsoft.com/en-us/library/hh209301\(v=ax.60\)).
    
      - **NAF codes**
    
      - **Import ZIP/postal codes**

## General ledger

  - Set up financial dimensions in the **Financial dimensions** form. (Click **General ledger** \> **Setup** \> **Financial dimensions** \> **Financial dimensions**.)
    
    For complete guidelines, see [Financial dimensions (form)](https://technet.microsoft.com/en-us/library/hh209534\(v=ax.60\)).

  - Set up tax information in the following forms (**General ledger** \> **Setup** \> **Sales tax**):
    
      - **Sales tax codes**
        
        For complete guidelines, see [Sales tax codes (form)](https://technet.microsoft.com/en-us/library/aa553257\(v=ax.60\)).
    
      - **Sales tax groups**
        
        For complete guidelines, see [Sales tax groups (form)](https://technet.microsoft.com/en-us/library/aa498345\(v=ax.60\)).
    
      - **Item sales tax groups**
        
        For complete guidelines, see [Item sales tax groups (form)](https://technet.microsoft.com/en-us/library/aa615960\(v=ax.60\)).
    
      - **Account group**
        
        For complete guidelines, see [Ledger posting groups (form)](https://technet.microsoft.com/en-us/library/aa598801\(v=ax.60\)).
    
      - **Sales tax exempt codes**
        
        For complete guidelines, see [Sales tax exempt codes (form)](https://technet.microsoft.com/en-us/library/aa634356\(v=ax.60\)).
    
      - **Sales tax jurisdictions**
        
        For complete guidelines, see [Sales tax jurisdictions (form)](https://technet.microsoft.com/en-us/library/aa582278\(v=ax.60\)).
    
      - **Sales tax authorities**
        
        For complete guidelines, see [Sales tax authorities (form)](https://technet.microsoft.com/en-us/library/aa552841\(v=ax.60\)).
    
      - **Sales tax settlement periods**
        
        For complete guidelines, see [Sales tax settlement periods (form)](https://technet.microsoft.com/en-us/library/aa633944\(v=ax.60\)).

## Cash and bank management

  - Set up the Central Bank purpose code in the **Payment purpose codes** form. (Click **Cash and bank management** \> **Setup** \> **Payment purpose codes**.)
    
    For complete guidelines, see [Payment purpose codes (form)](https://technet.microsoft.com/en-us/library/aa587506\(v=ax.60\)).

## See also

[Manage vendor requests overview](manage-vendor-requests-overview.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

