---
title: 'Key tasks: Release products'
TOCTitle: 'Key tasks: Release products'
ms:assetid: 2f55f42e-1c5a-4bfe-b7f0-288ff18cca6e
ms:mtpsurl: https://technet.microsoft.com/library/Hh208544(v=AX.60)
ms:contentKeyID: 36056298
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- products
- product
- release product
- create item
- create items
- release item
- released
- release products
- release items
audience: Application User
ms.search.region: Global
---

# Key tasks: Release products 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you release a product or a product master, you associate it with a company and authorize the product definition for use in the company.

You can use two methods to make product definitions available to companies:

  - Create a shared product definition, and release the product definition to one or more companies. The product definitions are available to the companies as soon as they are released.

  - Create a product definition in the context of a company. The product definitions are available to the company as soon as they are created.

Product variants require a product master to be released. Product variants can be released together with the product master. Product variants can also be released without the product master, provided that the product master already exists in the companies that the variants are released to.

If products, product masters, or product variants that are included in a release session cannot be released, the release is stored as an open release session. You can use the open release session to troubleshoot the reason why the release was not completed.

## What do you want to do?

Learn more about...

Release a product

Release a product upon creation

Release product variants

Add products to a release session

View open releases

Find form help

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Key tasks: Define products](key-tasks-define-products.md)

## Release a product

You can release a product or a product master to several companies at the same time.

1.  Click **Product information management** \> **Common** \> **Products** \> **All products and product masters**.
    

    > [!TIP]
    > <P>If you want to view and release only products or product masters, you can use the <STRONG>Products</STRONG> form or the <STRONG>Product masters</STRONG> form:</P>
    > <UL>
    > <LI>
    > <P>Click <STRONG>Product information management</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Products</STRONG> &gt; <STRONG>Products</STRONG>.</P>
    > <LI>
    > <P>Click <STRONG>Product information management</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Products</STRONG> &gt; <STRONG>Product masters</STRONG>.</P></LI></UL>



2.  Select a product or a product master, and then click **Release products** in the **Product authorization** group on the **Action Pane**.

3.  Click the **Select companies** link, and then select one or more companies.

4.  Click **OK** to open the **Product release session batch** dialog box.

5.  Select the **Show Infolog upon failure** check box to be notified if the release is not completed.
    

    > [!NOTE]
    > <P>Even if the check box is cleared, you can manually retrieve information about a release that is not completed, and troubleshoot the reason why it was not completed, by using the <STRONG>Open product releases</STRONG> form.</P>
    > <UL>
    > <LI>
    > <P>Click <STRONG>Product information management</STRONG> &gt; <STRONG>Periodic</STRONG> &gt; <STRONG>Open product releases</STRONG>.</P></LI></UL>
    > <P>However, you are notified about releases that are not completed only if the check box is selected.</P>

    

    > [!TIP]
    > <P>After you release a product to a company, the product is available in the context of the company. You can then view the product by using the <STRONG>Released products</STRONG> form.</P>
    > <UL>
    > <LI>
    > <P>Click <STRONG>Product information management</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Released products</STRONG>.</P></LI></UL>
    > <P>In this form, you can also set up company-specific product details, such as coverage plans and commission groups.</P>



Back to top

## Release a product upon creation

When you create a product by using the **Released products** form, you release the product to the current company as soon as it is created. The product definition also becomes available as a shared product definition that can be released to other companies. You can view the shared product definition from all companies by using the following forms:

  - **All products and product masters**

  - **Products**

  - **Product masters**

<!-- end list -->

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  On the **Action Pane**, in the **New** group, click **Product**.

3.  Follow the steps to define a product. For more information, see [Key tasks: Define products](key-tasks-define-products.md).

Back to top

## Release product variants

You can release product variants when you release the product master. You can also release the variants or any new variants at any time.


> [!NOTE]
> <P>If you release product variants for a product master that already exists in the company, you must clear the <STRONG>Include product master</STRONG> check box. A product master cannot be released to the same company two times.</P>



1.  Click **Product information management** \> **Common** \> **Products** \> **Product masters**.

2.  Select a product master, and then click **Release products** in the **Product authorization** group on the **Action Pane**.

3.  Select product variants in the **Product variants** group, or click **Select all**.

4.  Click the **Select companies** link, and then select the companies that you want to release the variants to.

5.  Click **OK** to open the **Product release session batch** dialog box.

6.  Select the **Show Infolog upon failure** check box to be notified if the release is not completed.

7.  If the product master of the variants has not already been released to the company, select the **Include product master** check box.
    

    > [!NOTE]
    > <P>Product variants cannot be released to a company unless the product master is also released, or unless the product master was previously released.</P>



Back to top

## Add products to a release session

Products and product variants that are released at the same time are released in one release session. To start a release session, you select the product or product master in one of the following forms:

  - **All products and product masters**

  - **Products**

  - **Product masters**

You can also add products or product masters to a release session. The following procedure describes how to add products to a release session by using the **All products and product masters** form. The steps also apply to the other two forms.

1.  Click **Product information management** \> **Common** \> **Products** \> **All products and product masters**.

2.  Select the product that you want to release, and then click **Release products** in the **Product authorization** group on the **Action Pane**.

3.  Click **Add**, and then select products or product masters in the **Add products to release** form.

4.  Click **Add selection now**, and then click **OK** to close the **Add products to release** form.
    

    > [!TIP]
    > <P>You can view, add, or remove product variants for a product master before you release the variants:</P>
    > <UL>
    > <LI>
    > <P>In the <STRONG>Release products</STRONG> form, select the product master. The associated product variants are displayed in the <STRONG>Product variants</STRONG> group.</P></LI></UL>



Back to top

## View open releases

If problems occur during a release session, the release is stored as an open release session. You can use the open release session to troubleshoot the causes of the following issues:

  - A product or a product master is not released to all or some of the selected companies.

  - All or some of the variants for a product master are not released to all or some of the selected companies.

<!-- end list -->

1.  Click **Product information management** \> **Periodic** \> **Open product releases**.

2.  In the **Release session** field, select a release session.

3.  Click **View infolog** to view information about the release session and the reason why the session was stored as an open release session.
    

    > [!TIP]
    > <P>There are separate buttons of the type <STRONG>View infolog</STRONG> for products and product variants. The messages that are displayed for products and product variants depend on the problem that occurred during the release session.</P>
    > <P>If you include a product master in a release to a company where the product master already exists, the release is not completed. A message is displayed for the product master. If a similar problem occurs for product variants, a message becomes available for the variants.</P>



Back to top

## Find form help

[Release products (form)](https://technet.microsoft.com/library/hh227553\(v=ax.60\))

[Open product releases (form)](https://technet.microsoft.com/library/hh209696\(v=ax.60\))

[Add products to release (form)](https://technet.microsoft.com/library/hh242469\(v=ax.60\))

  


