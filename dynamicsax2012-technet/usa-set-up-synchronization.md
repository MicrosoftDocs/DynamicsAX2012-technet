---
title: (USA) Set up synchronization
TOCTitle: (USA) Set up synchronization
ms:assetid: 6c6c548b-8ca0-428f-8a96-9b625774e34d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242617(v=AX.60)
ms:contentKeyID: 36058001
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: USA
---

# (USA) Set up synchronization 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can start selling online and receiving sales orders, you must set up synchronization schedules for several types of information, so that the information can be synchronized automatically between Commerce Services and Microsoft Dynamics AX.

1.  Click **Organization administration** \> **Setup** \> **Commerce Services** \> **Configuration checklist**.

2.  Click **Set up data synchronization**.

3.  In the **Batch job** form, select one of the following Commerce Services jobs:
    
      - **Commerce Services inventory synchronization** - Synchronizes inventory, dimensions, dimension groups, and item tax groups. The recommended synchronization frequency is every 15 minutes.
        

        > [!IMPORTANT]
        > <P>Before performing an inventory synchronization, ensure that you select the products that you want to sell online. Otherwise, your entire inventory will be synchronized with Commerce Services. For more information, see <A href="usa-select-products-to-sell-online.md">(USA) Select products to sell online</A>.</P>

    
      - **Commerce Services trade agreements synchronization** - Synchronizes trade agreements. The recommended synchronization frequency is once a day.
    
      - **Commerce Services online orders upload and download** - Downloads orders, uploads shipment information, and updates order status. The recommended synchronization frequency is every 15 minutes.
    
      - **Commerce Services delivery mode and online store synchronization** - Uploads delivery modes, such as FedEx or USPS, and downloads online stores from Commerce Services. The recommended synchronization frequency is as required.
    
      - **Commerce Services complete data synchronization** - Synchronizes all Commerce Services data with Microsoft Dynamics AX. In Microsoft Dynamics AX, whenever you select products to sell online, you must then run the Commerce Services complete data synchronization job. You should also run this synchronization if you experience data loss in Microsoft Dynamics AX. The recommended synchronization frequency is as required.
        

        > [!NOTE]
        > <P>Depending on the amount of data, this synchronization might take considerable time. If you have large amount of data, consider performing this synchronization during off hours.</P>



4.  Click **Recurrence**, and then set up a synchronization schedule.

5.  Repeat steps 2 and 3 for each of the jobs whose synchronization you want to set up.


> [!NOTE]
> <P>This feature is not available if Microsoft Dynamics AX 2012 R3 is installed.</P>



## See also

[(USA) Select online marketplaces](usa-select-online-marketplaces.md)

[(USA) Organize and edit products in Commerce Services](usa-organize-and-edit-products-in-commerce-services.md)

  


