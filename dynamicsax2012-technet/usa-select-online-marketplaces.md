---
title: (USA) Select online marketplaces
TOCTitle: (USA) Select online marketplaces
ms:assetid: 174297af-4435-4dfa-a922-7fa18861f8b6
ms:mtpsurl: https://technet.microsoft.com/library/Hh242150(v=AX.60)
ms:contentKeyID: 36056081
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: USA
---

# (USA) Select online marketplaces 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you sign up for Commerce Services for Microsoft Dynamics ERP and activate your account, you can select the online marketplaces, such as eBay, where you want to list your products for sale. You can also create your own online store. For more information, see [Set up an online store](set-up-an-online-store.md).


> [!NOTE]
> <P>The procedure for completing this task was changed for Microsoft Dynamics AX 2012 R2. The updated procedure also applies to AX 2012 R3. For more information, see the section later in this topic.</P>




> [!NOTE]
> <P>This feature is not available if Microsoft Dynamics AX 2012 R3 is installed.</P>



### Select online marketplaces

1.  Click **Organization administration** \> **Setup** \> **Commerce Services** \> **Configuration checklist**.

2.  Click **Select marketplaces online** to open the Commerce Services website.

3.  Enter your Microsoft account and password.

4.  Review the available marketplaces, click **Sign up now** for the marketplace that you want, and then follow the instructions for the marketplace.

5.  When you are finished, click **Sign out**.

### Select online marketplaces in Microsoft Dynamics AX 2012 R2

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online marketplaces**.

2.  On the **Action Pane**, on the **Channel** tab, in the **New** group, click **Online marketplace**.

3.  In the **Online marketplace** form, on the **General** FastTab, enter a name and a search name for the marketplace.

4.  In the **Customer template** field, select a default customer for the store. This customer is used if a specific customer is not added to a transaction. The settings of this template are also used as default settings when you create a new customer.

5.  In the **Sales origin** field, select **INET** (Internet).

6.  In the **Online catalog** field, enter a name for the catalog of products to sell online.

7.  In the **Retail stores** field, select the profile that contains the e-mail messages to send to customers at different points in the sales process for this online marketplace.

8.  On the **Action Pane**, on the **Set up** tab, click **Link**.

9.  Follow the instruction on the Commerce Services website to select an online marketplace.

10. In Microsoft Dynamics AX, assign one or more modes of delivery to the online marketplace. The modes of delivery that you select must be supported by the marketplace. For more information, see [Set up modes of delivery](set-up-modes-of-delivery.md).


> [!IMPORTANT]
> <P>After you set up a new online marketplace, you must add the marketplace to an organization hierarchy that is assigned to a purpose. For example, the organization hierarchy can be used for assortments, replenishment, or reporting. For more information, see <A href="about-retail-hierarchies.md">About retail hierarchies</A>.</P>



## See also

[(USA) Set up synchronization](usa-set-up-synchronization.md)

[(USA) Organize and edit products in Commerce Services](usa-organize-and-edit-products-in-commerce-services.md)

[Set up an online store](set-up-an-online-store.md)

  


