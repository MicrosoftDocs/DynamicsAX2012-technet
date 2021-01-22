---
title: Configure parameters (Retail essentials)
TOCTitle: Configure parameters (Retail essentials)
ms:assetid: 68753c90-16ce-422d-862b-c62577d1aa08
ms:mtpsurl: https://technet.microsoft.com/library/Dn736889(v=AX.60)
ms:contentKeyID: 62200366
author: Khairunj
ms.author: daxcpft
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Configure parameters (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to specify default settings for Retail essentials. You use two forms to specify these settings: **Retail parameters** and **Retail scheduler parameters**. Specify the appropriate settings for your business in each form. You can change many of these settings later.

## Set up retail parameters

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **Retail parameters**.

2.  Click **General**, and then specify the following:
    
      - **EAN license number** – Enter the license number to use to create bar codes that are based on the EAN standard.
    
      - **Default inventory journal** – Select the type of inventory journal to use by default when an inventory journal is created in the point of sale (POS) system.
    
      - **Email notification profile** – Select the email notification profile to use to automatically generate email messages. The email notification profile generates email messages based on a specific event by using an email template that you define.
    
      - **Kit journal name** – Specify the name of the journal to use to generate trade agreements for product variants that are included in a product kit.
    
      - **Category journal name** – Specify the name of the journal to use to generate trade agreements for products that are included in a retail category.

3.  Click **General**, and then, on the **Gift card** FastTab, specify the following:
    
      - **Gift card product** – Select the product that is added to a transaction when a cashier issues a gift card at the point of sale (POS).
    
      - **Gift card company** – Select the legal entity that issues gift cards.
    
      - **Journal** – Select the journal that is used for issuing gift cards.
    
      - **Void journal name** – Select the journal that is used for voiding gift cards.
    
      - **Serial number templates** – Create a template for each series of gift cards that your stores issue. Click **New**, specify a start date and end date, and specify the number of characters in the gift card number. For example, you might create a different template for each store. Or you might have one template for general gift cards and other templates for seasonal promotions.
        

        > [!TIP]
        > <P>If a series of gift cards has no end date, leave the <STRONG>End date</STRONG> field blank.</P>
        > <P>Gift card numbers are generated automatically.</P>



4.  On the **Email receipt** FastTab, specify the following:
    
      - **Gift card product** – Select whether receipts at the POS are printed, emailed, or both.
    
      - **Subject** – Enter the subject line to use on emailed receipts.
    
      - **Journal** – Enter the file name of the email receipt.

5.  Click **Accounting export**, and then specify the settings for exporting accounting information, such as the accounting export profile and the path for the exported file.

6.  Click **Product creation**, and then specify the default warehouses for purchase orders, inventory, and sales orders.

7.  Click **Customer orders**, and then specify the default settings for customer orders, such as the order type, deposit, cancellation charge, and shipping charge.

8.  Click **Replenishment**, and then specify whether to respect assortments when inventory is replenished by using cross docking and buyer’s push.

9.  Click **Number sequences** to view the number sequences that are automatically generated for retail operations, such as creating discounts, loyalty customer accounts, and issuing gift cards.

10. Click **Password strength**, and then select requirements for the passwords that cashiers use at the POS, such as the minimum password length and character requirements.

## Set up retail scheduler parameters

1.  Click **Retail essentials** \> **Data synchronization** \> **Setup** \> **Retail scheduler parameters**.

2.  Click **General**, and then specify or view the following:
    
      - **Server name** – Enter the name of the computer that hosts the message database for Commerce Data Exchange: Async Server.
    
      - **Database server instance** – Enter the name of the Microsoft SQL Server instance that hosts the message database for Async Server.
    
      - **Database name** – Enter the name of the message database for Async Server.
    
      - **Try count** – Enter the number of times that a failed stage of the data transfer will be retried. If you enter 0 (zero), the number of retries is unlimited.
    
      - **SQL Change tracking** – Indicates whether SQL Server change tracking is enabled on the Retail essentials database. Change tracking must be enabled to use data distribution features. Contact the database administrator if change tracking is not enabled.

3.  Click **Monitoring**, and then, in the **Retention period in days** field, enter the number of days to retain upload session history, download session history, and data packages in the working folders.

  


