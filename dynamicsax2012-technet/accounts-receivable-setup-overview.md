---
title: Accounts receivable setup overview
TOCTitle: Accounts receivable setup overview
ms:assetid: 5d303bb8-606c-4a7a-a1be-fae498734b13
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242517(v=AX.60)
ms:contentKeyID: 36057576
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- setup
- AR
- receivable
---

# Accounts receivable setup overview [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this topic as your guide to setting up Accounts receivable.

## Prerequisites

Set up the following modules:

  - **System administration**

  - **Organization administration**

  - **General ledger**
    
      - If you plan to use payment journals, you must first set up payment journals in the **Journal names** form.
    
      - If you plan to run exchange rate adjustments, you must set up currency codes in the **Currencies** form, exchange rate types in the **Exchange rate types** form, and currency exchange rates in the **Currency exchange rates** form.

  - In **Cash and bank management**, set up bank accounts to use with methods of payment.

## Main setup forms for Accounts receivable

Use the following forms to set up the basic functionality of Accounts receivable for each legal entity. The forms are listed in the recommended order of setup.

To make the setup process simpler, you can create templates from the first records that are created. A template typically includes entries in many fields that reflect the features that the organization wants to implement for a particular type of customer.

1.  Define the terms of payment that you assign to sales orders and customers, and that determine invoice due dates, in the **Terms of payment** form.
    
    For complete guidelines, see [Terms of payment (form)](https://technet.microsoft.com/en-us/library/aa588427\(v=ax.60\)).

2.  Create and maintain information about how the organization receives payments from customers in the **Methods of payment - customers** form.
    
    For complete guidelines, see [Methods of payment - customers (form)](https://technet.microsoft.com/en-us/library/aa499398\(v=ax.60\)).

3.  Create and maintain groups of customers who share key parameters for posting, settlement and payment, reporting, and forecasting in the **Customer groups** form.
    
    For complete guidelines, see [Customer groups (form)](https://technet.microsoft.com/en-us/library/aa550231\(v=ax.60\)).

4.  Set up the way in which customer transactions are posted to the general ledger in the **Customer posting profiles** form.
    
    For complete guidelines, see [Customer posting profiles (form)](https://technet.microsoft.com/en-us/library/aa600572\(v=ax.60\)).

5.  Set up default entries, various types of functionality, and number sequences for Accounts receivable in the **Accounts receivable parameters** form.
    
    For complete guidelines, see [Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\)).

6.  Define the format of various documents related to customers in the **Form setup** form.

7.  Create and maintain the customer accounts that the organization does business with in the **Customers** form.
    
    For complete guidelines, see [Customers (form)](https://technet.microsoft.com/en-us/library/aa590606\(v=ax.60\)).

## Optional setup forms for Accounts receivable

The setup of Accounts receivable includes several other steps beyond the basic functionality.

The additional setup forms are organized by functionality.

## Customer classification groups

  - Create and maintain customer classification groups to prioritize customers in the **Customer classification groups** form.
    
    For complete guidelines, see [Customer classification groups (form)](https://technet.microsoft.com/en-us/library/aa586936\(v=ax.60\)).

## Workflow

  - Set up workflow configurations for journal approvals in the **Accounts receivable workflows** form.
    
    For complete guidelines, see [Workflows (list page)](https://technet.microsoft.com/en-us/library/hh209721\(v=ax.60\)).

## Reasons

  - Set up reason codes in the **Customer reasons** form to manage customer reason codes.
    
    For complete guidelines, see [Reasons (form)](https://technet.microsoft.com/en-us/library/hh209362\(v=ax.60\)).

  - Set up free text invoice templates in the **Free text invoice templates** form.
    
    For complete guidelines, see [Free text invoice templates (form)](https://technet.microsoft.com/en-us/library/hh209275\(v=ax.60\)).

## Charges

  - Set up codes for the charges to use in sales orders in the **Charges code** form.
    
    For complete guidelines, see [Charges code (form)](https://technet.microsoft.com/en-us/library/aa598932\(v=ax.60\)).

  - Create and maintain charges groups for customers in the **Customer charge groups** form.
    
    For complete guidelines, see [Charges groups (form)](https://technet.microsoft.com/en-us/library/aa617452\(v=ax.60\)).

  - Create and maintain groups of charges for items in the **Item charge groups** form.
    
    For complete guidelines, see [Charges groups (form)](https://technet.microsoft.com/en-us/library/aa617452\(v=ax.60\)).

  - Define the charges to automatically assign to orders in the **Auto charges** form.
    
    For complete guidelines, see [Auto charges (form)](https://technet.microsoft.com/en-us/library/aa582856\(v=ax.60\)).

## Supplementary items

  - Create and maintain supplementary item groups for customers in the **Supplementary item groups** **-** **Customer** form.

  - Create and maintain supplementary item groups for items in the **Supplementary item groups** **-** **Inventory** form.

## Distribution

  - Create and maintain the conditions for an item's transfer from seller to buyer in the **Terms of delivery** form.
    
    For complete guidelines, see [Terms of delivery (form)](https://technet.microsoft.com/en-us/library/aa575567\(v=ax.60\)).

  - Create and maintain the means of transport used when delivering an order from the seller to the buyer in the **Modes of delivery** form.
    
    For complete guidelines, see [Modes of delivery (form)](https://technet.microsoft.com/en-us/library/aa619881\(v=ax.60\)).

  - Create and maintain reasons for the deliveries in the **Reasons for delivery** form.
    
    For complete guidelines, see [Reasons for delivery (form)](https://technet.microsoft.com/en-us/library/aa598006\(v=ax.60\)).

  - Create and maintain identifier codes and descriptions for delivery destinations in the **Destination codes** form.
    
    For complete guidelines, see [Destination codes (form)](https://technet.microsoft.com/en-us/library/aa574145\(v=ax.60\)).

  - Create and maintain descriptions for the various package types in the **Package appearance** form.
    
    For complete guidelines, see [Package appearance (form)](https://technet.microsoft.com/en-us/library/aa596443\(v=ax.60\)).

  - Create and maintain a list of carrier names and addresses in the **Carrier** form.
    
    For complete guidelines, see [Carrier (form)](https://technet.microsoft.com/en-us/library/aa587948\(v=ax.60\)).

## Forms

  - Create the standard text that appears on various forms in the **Form notes** form.

  - Set up the sorting orders for sales orders, picking lists, packing slips, and invoices in the **Form sorting parameters** form.
    
    For complete guidelines, see [Sales form sorting parameters (form)](https://technet.microsoft.com/en-us/library/aa556684\(v=ax.60\)).

  - Set up print management information for originals and copies of forms in the **Print management setup** form.
    
    For complete guidelines, see [Print management setup (form)](https://technet.microsoft.com/en-us/library/hh209383\(v=ax.60\)).

## Payment

  - Set up and manage the terms for obtaining cash discounts in the **Cash discounts** form. The cash discount codes are linked to customers and are applied to sales orders.
    
    For complete guidelines, see [Cash discounts (form)](https://technet.microsoft.com/en-us/library/aa590275\(v=ax.60\)).

  - Set up payment schedules to manage installment payments from customers in the **Payment schedules** form.
    
    For complete guidelines, see [Payment schedules (form)](https://technet.microsoft.com/en-us/library/aa572068\(v=ax.60\)).

  - Define the payment days that are used for the calculation of due dates, and specify payment days for a specific day of the week or month, in the **Payment days** form.
    
    For complete guidelines, see [Payment days (form)](https://technet.microsoft.com/en-us/library/aa553269\(v=ax.60\)).

  - Create and maintain payment fees that are associated with customers in the **Payment fee** form.
    
    For complete guidelines, see [Customer payment fee (form)](https://technet.microsoft.com/en-us/library/aa616532\(v=ax.60\)).

  - Create and maintain payment steps in the **Payment step** form.
    
    For complete guidelines, see [Payment step (form)](https://technet.microsoft.com/en-us/library/aa500133\(v=ax.60\)).

  - Create and maintain information about credit card processors in the **Payment services** form.
    
    For complete guidelines, see [Payment services (form)](https://technet.microsoft.com/en-us/library/hh227622\(v=ax.60\)).

## Collections

  - Set up and manage aging period definitions for use on the **Collections** list page in the **Aging period definitions** form.
    
    For complete guidelines, see [Aging period definitions (form)](https://technet.microsoft.com/en-us/library/aa634713\(v=ax.60\)) and [Set up collections](set-up-collections.md).

  - Set up and manage queries that define groups of customers in the **Customer pools** form.
    
    For complete guidelines, see [Customer pools (form)](https://technet.microsoft.com/en-us/library/hh227560\(v=ax.60\)) and [Set up collections](set-up-collections.md).

  - Set up and manage collections agents in the **Collections agent** form.
    
    For complete guidelines, see [Collections agents (form)](https://technet.microsoft.com/en-us/library/hh209479\(v=ax.60\)) and [Set up collections](set-up-collections.md).

  - Create and manage collection letter sequences and connect them with collection letter lines in the **Collection letter** form.
    
    For complete guidelines, see [Collection letter (form)](https://technet.microsoft.com/en-us/library/aa620428\(v=ax.60\)).

  - Set up and manage interest codes in the **Interest** form.
    
    For complete guidelines, see [Interest setup (form)](https://technet.microsoft.com/en-us/library/aa574050\(v=ax.60\)).

## Statistics

  - Create line of business codes that you assign to customers in the **Line of business** form.
    
    For complete guidelines, see [Line of business (form)](https://technet.microsoft.com/en-us/library/aa619191\(v=ax.60\)).

  - Create and manage customer statistics groups to use as criteria in inquiries and on reports in the **Statistics** form.
    
    For complete guidelines, see [Statistics group (form)](https://technet.microsoft.com/en-us/library/aa634321\(v=ax.60\)).

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

  - Set up tax information in the following tax setup forms (**General ledger** \> **Setup** \> **Sales tax**):
    
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

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

