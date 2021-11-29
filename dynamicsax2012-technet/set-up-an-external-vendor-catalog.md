---
title: Set up an external vendor catalog
TOCTitle: Set up an external vendor catalog
ms:assetid: d27577ea-e1c5-4990-b279-86fd440d0a9a
ms:mtpsurl: https://technet.microsoft.com/library/Hh242924(v=AX.60)
ms:contentKeyID: 36059505
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up an external vendor catalog 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If your vendors host the data for procurement catalogs for you, you can configure access to the vendor’s external catalog site so that users can access the catalog directly. Your vendor provides the settings for remote access to the catalog, and then you set up the required configurations in Microsoft Dynamics AX.

After you set up the configurations for the vendor's external catalog, you must validate the settings and activate the catalog before you can make the catalog available to users. For more information about how to validate and activate the configuration for an external vendor's catalog, see [Key tasks: Maintain external vendor catalogs](key-tasks-maintain-external-vendor-catalogs.md).

Before you can set up access to the vendor’s external catalog site, you must set up the vendor and vendor contacts in Microsoft Dynamics AX. You must also assign the vendor to a procurement category. For more information about how to register vendors in Microsoft Dynamics AX, see [Manage vendor requests overview](manage-vendor-requests-overview.md).


> [!NOTE]
> <P>The following procedures are completed in the <STRONG>Maintain details for an external catalog</STRONG> form. The first procedure describes how to open the form. Each of the remaining procedures is completed on a separate FastTab in the form.</P>



### Open the Maintain details for an external catalog form

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **External catalogs**.

2.  On the **External catalogs** list page, on the **Action Pane**, in the **New** group, click **External catalog**.

### The General FastTab

1.  Enter a name and description for the vendor's external catalog. The name that you enter appears as a link on the procurement site. The link opens the catalog on the vendor's external catalog site.

2.  In the **Type** field, select the type of catalog that you are configuring.
    
      - If users must return to Microsoft Dynamics AX to check out and create a purchase requisition, select **External with shopping cart**.
    
      - If users can check out on the vendor’s external catalog site, select **External without shopping cart**.

3.  Under **Contacts**, select the catalog owner and the external vendor's contact person for the catalog.

4.  Under **Vendor**, select the vendor for the catalog. Then, in the **Legal entities:** list, select the check box for each legal entity in which you want the catalog to be available.
    

    > [!NOTE]
    > <P>Only the legal entities in which the vendor is approved to supply products appear in the <STRONG>Legal entities:</STRONG> list.</P>



5.  In the **Default expiration (Days)** field, enter the number of days that a quotation is valid and can be used to purchase from the external vendor. When a quotation is created and retrieved from the vendor’s external catalog site, the quotation is valid as of the current system date, and remains valid for the number of days that you enter in this field.
    

    > [!NOTE]
    > <P>This option applies only if the <STRONG>Type</STRONG> field is set to <STRONG>External with shopping cart</STRONG>.</P>



6.  If the external vendor allows the quantity on a purchase order to differ from the quantity that was quoted on the vendor's external catalog site, select the **Supports quantity changes** check box.
    

    > [!NOTE]
    > <P>This option applies only if the <STRONG>Type</STRONG> field is set to <STRONG>External with shopping cart</STRONG>.</P>



7.  If the external vendor allows users to delete a single line item from a purchase order, select the **Supports individual item deletion** check box. If this check box is cleared, users must delete all line items that were included in the original quotation, and then add back any items that they want to purchase.
    

    > [!NOTE]
    > <P>This option applies only if the <STRONG>Type</STRONG> field is set to <STRONG>External with shopping cart</STRONG>.</P>



### The Remote production site settings FastTab

1.  In the **Call method** field, select the call method that the system uses to access the vendor's external catalog site.

2.  In the **Content type** field, select the content format that is used on the external vendor's catalog site.

3.  In the **Return URL key** field, enter the return URL key that is used to return a user from the external vendor's catalog site to the user's procurement site.
    

    > [!NOTE]
    > <P>This field applies only if the <STRONG>Type</STRONG> field on the <STRONG>General</STRONG> FastTab is set to <STRONG>External with shopping cart</STRONG>.</P>



4.  In the **Destination URL** field, enter the Internet address that the vendor provided for its external catalog site.

5.  In the **Order status check URL** field, enter the Internet address of the vendor's external catalog site, if the vendor provided a catalog site where users can check the status of their orders.

6.  In the **Name of protocol** field, select the message format that the system uses to connect to the vendor's external catalog site.

7.  In the **Session properties:** pane, click **Add**, and then select any additional data that must be included in the initial session request to connect to the vendor's external catalog site. For example, a password or user name may be required.

### Optional: The Remote staging site settings FastTab

1.  In the **Call method** field, select the call method that the system uses to access the vendor's staging site.

2.  In the **Content type** field, select the content format that is used on the vendor's external catalog site.

3.  In the **Return URL key** field, enter the return URL key that is used to return a user from the vendor's external catalog site to the user's procurement site.
    

    > [!NOTE]
    > <P>This field applies only if the <STRONG>Type</STRONG> field on the <STRONG>General</STRONG> FastTab is set to <STRONG>External with shopping cart</STRONG>.</P>



4.  In the **Destination URL** field, enter the Internet address that the vendor provided for its external catalog site.

5.  In the **Order status check URL** field, enter the Internet address of the external vendor's catalog site, if the vendor provided a catalog site where users can check the status of their orders.

6.  In the **Name of protocol** field, select the message format that the system uses to connect to the external vendor's catalog site.

7.  In the **Session properties:** pane, click **Add**, and then select any additional data that must be included in the initial session request to connect to the external vendor's catalog site. For example, a password or user name may be required.

### The Procurement category mapping FastTab

1.  Click the **Add** button. Then, in the **Category name** list, select a category.

2.  In the **Search text** field, enter any keywords that users may enter to search for the catalog on the procurement site.

3.  To remove a category that is associated with the vendor’s external catalog, select the category, and then click **Remove**.


> [!NOTE]
> <P>Before you can add procurement categories to a vendor's external catalog, the procurement category hierarchy must be defined for your organization. Additionally, the vendor's external catalog must be added to the procurement category. For more information about how to set up a procurement category hierarchy, see <A href="key-tasks-set-up-a-category-hierarchy.md">Key tasks: Set up a category hierarchy</A>.</P>



## See also

[External vendor catalogs overview](external-vendor-catalogs-overview.md)

[Key tasks: Maintain external vendor catalogs](key-tasks-maintain-external-vendor-catalogs.md)

[Key tasks: Create procurement catalogs](key-tasks-create-procurement-catalogs.md)

[Maintain details for an external catalog (form)](https://technet.microsoft.com/library/hh242254\(v=ax.60\))

[External catalogs (list page)](https://technet.microsoft.com/library/hh208570\(v=ax.60\))

  


