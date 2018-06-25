---
title: Set up a retail store
TOCTitle: Set up a retail store
ms:assetid: e0748d3a-08a2-41e3-91e0-be1e1935f112
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597262(v=AX.60)
ms:contentKeyID: 39519342
ms.date: 09/05/2014
mtps_version: v=AX.60
f1_keywords:
- stores
- store
- retail
---

# Set up a retail store [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic explains how to set up a retail (brick-and-mortar) store in Retail. A retail store is considered a type of warehouse. In the following procedures, you first create a warehouse and define it as a store. You then create a new store and assign the warehouse to it.

## Set up a warehouse to represent a retail store

Use this procedure to set up a warehouse and define it as a retail store warehouse.

When you set up a warehouse as a retail store, it is recommended that you select the **Financial negative inventory** and the **Physical negative inventory** check boxes in the **Warehouses** form, on the **Retail** FastTab. Selecting these check boxes allows posting to occur for retail transactions even if there are insufficient product quantities available. If these check boxes are cleared, posting can be blocked for valid, completed transactions.

Selecting these settings overrides the settings for the same check boxes in the **Item model groups** form on the **Setup** FastTab, but only for a warehouse that is designated as a retail store, and only for retail transactions. The **Item model group** is referenced in the **Released product details** form.

If you want to block negative inventory for your store products you can use the negative inventory settings in the **Item model groups** and **Warehouses** forms. For warehouses that are not designated as retail stores, the item model group settings for the product are applied.

When you set up your retail store, you select the warehouse that corresponds to the retail store warehouse and the shipping warehouse that is used to ship customer products. You can control negative inventory settings based on the shipping warehouse that you select.


> [!NOTE]
> <P>In AX 2012 R3, you can only configure a Retail store to use a warehouse that is managed in <STRONG>Inventory management</STRONG>. You can’t configure a Retail store to use a warehouse that is managed in <STRONG>Warehouse management</STRONG>.</P>



1.  Depending on your version of the program, do one of the following:
    
      - In AX 2012 R3: Click **Warehouse management** \> **Setup** \> **Warehouse setup** \> **Warehouses**.
    
      - In earlier versions: Click **Inventory management** \> **Setup** \> **Inventory breakdown** \> **Warehouses**.

2.  Select an existing warehouse, or click **New** to create a new warehouse.

3.  On the **Retail** FastTab, select the **Store** check box.

4.  Enter other information that is required for the warehouse.
    
    For more information about the fields in the **Warehouses** form, see [Warehouses (form)](https://technet.microsoft.com/en-us/library/aa620570\(v=ax.60\)).

## Set up a retail store

Use this procedure to set up a retail store.

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

2.  On the **Retail stores** page, on the **Action Pane**, on the **Store** tab, in the **New** group, click **Retail store**.

3.  In the **Stores** form, on the **General** FastTab, in the **Identification** section, enter the following information. All of this information is required.
    
      - In the **Name** field, type a name for the new store.
    
      - In the **Store number** field, type an ID number for the store.
    
      - In the **Company** field, select the legal entity that the store belongs to.
        
        In AX 2012 R3, the name of this field is **Legal entity**.
    
      - In the **Warehouse** field, select the warehouse that you selected or created in the previous procedure.

4.  In the **Sales tax group** field, select the sales tax group that is used at the store.

5.  In the **Default customer** field, select the default customer that is used at the store. Transactions that do not have a specific customer use this customer.

6.  In the **POS register** section, enter the following information:
    
      - In the **Functionality profile** field, select the profile to use to configure the point-of-sale (POS) functionality for all registers in the store.
    
      - In the **Offline profile** field, select the profile to use to define which data is synchronized between the store database and the offline databases at the registers.
    
      - Select the **Inventory lookup** check box to allow POS registers to look up inventory.

7.  In the **Profiles** section, enter the following information:
    
      - In the **Real-time Service profile** field, select the profile that the store uses to connect to Microsoft Dynamics AX Application Object Server (AOS) to retrieve or update information.
    
      - In the **Channel profile** field, select the channel that the store uses to connect to Retail Server, printers, and hardware stations.
        

        > [!NOTE]
        > <P>This step applies only if AX 2012 R3 is installed.</P>

    
      - In the **Live channel database** field, select a database for the store. Retail Server uses this setting to find the database that is currently active for that channel.
        

        > [!NOTE]
        > <P>This step applies only if AX 2012 R3 is installed.</P>



8.  In the **Regional settings** section, select the language and currency that is used at the store.

9.  In the **Sales tax** section, set any additional tax requirements for the store.

10. In the **Address book** section, select the customer address book and the employee address book for the store. Customers who are assigned to the customer address book are downloaded to the Retail POS registers in the store. Employees who are assigned to the employee address book can log on to Retail POS registers in the store.

11. In the **Email notification** section, select an email notification profile to automatically generate emails to recipients based on user configured parameters. The email notification profile uses an email template that you provide to generate emails based on a specific event.

12. On the **Statement/closing** FastTab, select options for statements and closing operations. Enter the following information:
    
      - In the **Statement** section, set the statement options that are used when the statement is calculated, generated, and posted.
    
      - In the **Rounding** section, select the general leger account to use when posting rounding differences. Also, set the maximum rounding amount that can be posted.
    
      - In the **Maximum difference** section, set the maximum difference that is allowed when statements and shifts are posted or when transactions are posted..
    
      - Select the closing method that is used for the store.
    
      - In the **Batch options** section, select the options that are used when the statements are generated. For more information about each option, see [Stores (form)](https://technet.microsoft.com/en-us/library/hh580646\(v=ax.60\)).

13. On the **Miscellaneous** FastTab, select options for the store such as store hours, label printing options, and training mode settings.

14. On the **Financial dimensions** FastTab, set the financial dimensions for the store.

15. On the **Screen layout** FastTab, assign a screen layout to the store. The screen layout specifies how the screen is displayed on the point-of sale (POS) register. For example, the screen layout specifies the position and appearance of total amounts, the product grid, the customer layout, and the payment layout.

## Next steps

After you set up a new store, you must complete additional tasks to complete the full setup of the store and then send the store data to the POS registers. These tasks include the following:

  - Add the retail store to an organization hierarchy that is assigned a purpose of assortments, replenishment, or reporting. For information about how to set up an organization hierarchy, see [Create or modify an organization hierarchy](create-or-modify-an-organization-hierarchy.md).

  - Assign the accepted payment methods to the store. For more information, see [Set up store payment methods](set-up-store-payment-methods.md).

  - Assign product assortments to the store. For more information, see [Set up an assortment](set-up-an-assortment.md).

  - Send the store data from Microsoft Dynamics AX to the retail stores. Follow these steps:
    
    1.  If AX 2012 R3 is installed, click **Publish** to publish data for the retail store so that any new, updated, or deleted information can be sent from Microsoft Dynamics AX to the point-of-sale stores.
    
    2.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.
    
    3.  In the **Distribution schedule** form, run the following scheduler jobs:
        
          - **1070** (Channel configuration)
        
          - **1150** (Catalog), if AX 2012 R3 is installed and a retail product catalog is assigned to the retail store.
    
    4.  In the left pane, in the **Name** column, select the job that you want to run. Then, to run the job manually or in batch mode, do one of the following:
        
          - To manually run the scheduler job, on the menu bar at the top of the form, click **Run now**.
        
          - To run the scheduler job in batch mode, on the **Scheduler jobs** FastTab, verify that the **Enabled** check box is selected for the job, and then click **Create batch job**. In the form that is displayed, enter information about the batch job. For more information about the options in the form, see [Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md).

For a complete list of the tasks that must be completed to set up a retail store, see [About retail stores](about-retail-stores.md).

## See also

[Create or modify an organization hierarchy](create-or-modify-an-organization-hierarchy.md)

[About retail stores](about-retail-stores.md)

[Point of Sale](point-of-sale.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

