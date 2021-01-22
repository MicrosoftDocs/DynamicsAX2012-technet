---
title: Create distribution locations for retail databases
TOCTitle: Create distribution locations for retail databases
ms:assetid: dc601bbe-d24d-4dc3-aea0-3b9859ebfb1f
ms:mtpsurl: https://technet.microsoft.com/library/JJ677451(v=AX.60)
ms:contentKeyID: 49384235
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailConnDistributionLocation
- MsDynAx060.Forms.RetailConnDistributionLocation
---

# Create distribution locations for retail databases 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

A distribution location is a record that links Microsoft Dynamics AX to a store database. Distribution locations represent the destinations for distributed data.


> [!NOTE]
> <P>The information in this topic applies only to Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack.</P>



In general, you must have a distribution location for each store location that has its own database. When you create a store, a corresponding distribution location is automatically created. The distribution locations that are created automatically when you create stores are usually sufficient. However, you can also create new distribution locations.

1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Distribution locations**.

2.  Click **New**.

3.  Complete the following information for each distribution location.
    
      - **Location number** – If you are creating a new distribution location, enter a unique ID for the distribution location.
        
        When a distribution location is automatically created for a retail store, the location number is the same as the store number. When a distribution location is automatically created for an online store, the location number is an automatically generated number.
    
      - **Description** – Enter a description of the distribution location.
    
      - **Channel** – Select a channel.

4.  On the **General** FastTab, select the communication profiles for the selected distribution location:
    
      - **Database profiles** – Select the database connection profile for this location. When you select a database profile, related information is automatically displayed in other fields in the form.
    
      - **Channel profile** – Select the channel profile for this location. When you select a channel profile, related information is automatically displayed in other fields in the form.

5.  On the **Data exchange** FastTab, enter information about how data is exchanged between Microsoft Dynamics AX and the distribution location:
    
      - **Retail channel schema** – Select a schema, based on the version of Microsoft Dynamics AX that you are using and the type of channel that you are setting up.
    
      - **Send data** – Select this check box if data is sent from Microsoft Dynamics AX to the distribution location.
    
      - **Receive data** – Select this check box if data is sent from the distribution location to Microsoft Dynamics AX.
    
      - **Continuous data transfer schedule** – Select a schedule. Jobs in the selected schedule run regardless of the selections for **Send data** and **Receive data**.

6.  Click **Functions** to open a menu where you can select from the following options:
    
      - **Test connection** – Test the connection to Commerce Data Exchange: Synch Service.
    
      - **Read schema** – Read the database schema for the selected location, and create the list of location tables.
        

        > [!IMPORTANT]
        > <P>For store locations, use this function only to read third-party tables from the store database. You might prefer to manually set up the function to read third-party point of sale (POS) databases instead of location tables.</P>

    
      - **Send configuration** – The database profile that you selected for this distribution location specifies a profile for Commerce Data Exchange: Real-time Service and an instance of Synch Service. Select this option to send the Real-time Service profile to the Synch Service instance. The Real-time Service profile facilitates the upload of Synch Service status messages from the store to Microsoft Dynamics AX.
    
      - **Deploy initial dataset** – If the distribution location is for an online store, select this option to run jobs that synchronize initial data from Microsoft Dynamics AX to the distribution location. You should run this task any time that you create a new distribution location for an online store.

## See also

[Configure and schedule retail data distribution](configure-and-schedule-retail-data-distribution.md)

  


