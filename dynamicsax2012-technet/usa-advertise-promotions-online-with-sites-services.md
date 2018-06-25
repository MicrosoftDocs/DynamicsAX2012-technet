---
title: (USA) Advertise promotions online with Sites Services
TOCTitle: (USA) Advertise promotions online with Sites Services
ms:assetid: 823703e2-1d0e-42b1-a399-3b4a1f8d7028
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh696877(v=AX.60)
ms:contentKeyID: 42517329
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (USA) Advertise promotions online with Sites Services [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Microsoft Dynamics AX includes a Sites Services for Microsoft Dynamics ERP solution called Advertise promotions online.

After a Sites Services account has been set up, you can add discounts to a sales campaign, and then publish the promotion on several advertising media, such as Facebook and Bing. Customers can view the promotions online, print or note the discount codes or coupons, and then bring the discount codes to your store to take advantage of the promotions.

You can also track the return on investment (ROI) associated with the advertising campaign.


> [!NOTE]
> <P>This feature is not available if Microsoft Dynamics AX 2012 R3 is installed.</P>



## Activate the solution

Typically, the system administrator or the merchandising manager activates the Advertise promotions online solution.


> [!NOTE]
> <P>The system administrator must sign up for a Sites Services account before you can activate the Advertise promotions online solution.</P>
> <P>For more information about Sites Services, see <A href="usa-about-sites-services.md">(USA) About Sites Services</A>.</P>



1.  Click **Human resources** \> **Setup** \> **Sites Services** \> **Available solutions**.

2.  In the list of solutions on the left, select the Advertise promotions online solution, and then click **Activate**.

## Specify the bar code to use for discount codes

When you set up a discount that you want to advertise online, you generate a discount code that is included with the online advertisement. The customer brings this discount code to your store to take advantage of the promotion. You must first specify a bar code that will be used to generate the discount codes.

1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail shared parameters**.

2.  On the **Bar code** page, in the **Bar code setup** field, select **DiscCode**.

## Create discounts and generate discount codes

You can create new discounts or use existing ones that you want to advertise online. Either way, you must generate the discount codes that will be published online and that customers will use to take advantage of the discounts.

For information about discounts, see [Set up a price adjustment](set-up-a-price-adjustment.md).

1.  Click **Retail** \> **Common** \> **Pricing and discounts** \> **Discounts**.

2.  Select a discount in the list, and then on the **General** tab, select the **Discount code required** check box.

## Specify advertising media for the campaign

For more information about campaigns, see [Conduct campaign overview](conduct-campaign-overview.md).

1.  Click **Sales and marketing** \> **Common** \> **Campaigns** \> **All campaigns**.

2.  On the **Campaign** tab, in the **New** group, click **Campaign**, or select a campaign in the list, and then in the **Maintain** group, click **Edit**.

3.  On the **General** tab, in the **Set up** group, click **Media**.

4.  In the **Campaign media setup** form, click **New**, and then in the **Media type** field, select the media that you want.

## Specify discounts for the campaign

For more information about campaigns, see [Conduct campaign overview](conduct-campaign-overview.md).

1.  Click **Sales and marketing** \> **Common** \> **Campaigns** \> **All campaigns**.

2.  On the **Campaign** tab, in the **New** group, click **Campaign**, or select a campaign in the list, and then in the **Maintain** group, click **Edit**.

3.  On the **General** tab, in the **Promotions** group, click **Discounts**.

4.  In the **Discounts** form, click **New**, and then in the **Discount number** field, select the discount that you want.

5.  Add any other discounts that you want to the campaign.

6.  On the **Discount codes** tab, you can view the discount codes for the selected discount.

## Publish the promotion

1.  Click **Sales and marketing** \> **Common** \> **Campaigns** \> **All campaigns**.

2.  On the **Campaign** tab, in the **New** group, click **Campaign**, or select a campaign in the list, and then in the **Maintain** group, click **Edit**.

3.  On the **General** tab, in the **Promotions** group, click **Publish**.

4.  In the **Publish promotions** form, select a media type in the list, and then select the **Publish promotion** check box.

5.  In the **Publish message** box, type a message that you want to publish to advertise the promotion.

## See also

[(USA) About Sites Services](usa-about-sites-services.md)

[(USA) Set up and maintain a Sites Services account](usa-set-up-and-maintain-a-sites-services-account.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

