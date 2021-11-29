---
title: Manage KPIs
TOCTitle: Manage KPIs
ms:assetid: 9a0eb18c-9639-4b5a-ab91-deac75a283ce
ms:mtpsurl: https://technet.microsoft.com/library/JJ677301(v=AX.60)
ms:contentKeyID: 49384072
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Manage KPIs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

KPI List web parts display key performance indicators (KPIs). KPIs are business metrics, such as total revenue, gross profit margin, and current ratio. KPIs help you track your organization’s progress toward performance goals. This topic explains how to add the KPI List web part to a page, and how to configure the web part to display KPIs.


> [!NOTE]
> <P>KPI List web parts are available with Enterprise Portal for Microsoft Dynamics AX 2012 R2 or later. If you are using Enterprise Portal for Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack, you can display KPIs in Business Overview web parts. For more information, see <A href="manage-business-overview-information.md">Manage business overview information</A>.</P>



## Add the KPI List web part to a page

To add the KPI List web part to a page, follow the steps in [How to: Add Web Parts](https://technet.microsoft.com/library/cc604931\(v=ax.60\)).

After you add the KPI List web part to a page, the name of the web part is **Business overview**. The KPI List web part is a version of the Business Overview web part that is preconfigured to display KPIs. You can change the name of the web part when you configure it by using the following procedure.

## Configure the KPI List web part

To configure the KPI List web part to display KPIs, follow these steps.

1.  In the web part, click **Add KPIs**. The **Business Overview – Add KPI** form is displayed.

2.  From the **Cube** list, select the cube that contains the KPI that you want to display.
    
    For more information about the KPIs that are contained in each cube, see [Cube and KPI reference for Microsoft Dynamics AX 2012 R2](https://go.microsoft.com/fwlink/?linkid=268892).

3.  From the **KPI** list, select the KPI to display.

4.  From the **Display value as** list, select whether to display the KPI value as a monetary amount or a number. Then specify which colors represent positive and negative values.

5.  In the **Display name** field, enter a name for the KPI. This name is displayed to users. If you do not enter a name in this field, the name in the **KPI** field is displayed to users.

6.  Select the **Visible** check box to display the KPI in the web part.

7.  Select the **Apply filters** check box to enter filters, if you require them. You can filter KPIs by relative dates or actual values. You can also apply multiple filters.
    
      - **Filtering by relative dates or actual values** – Suppose that you have selected to display your organization’s sales total. If you want to filter this KPI by a relative date, you could choose to display the sales total for last year, last month, or last quarter. If you want to filter this KPI by an actual value, you could choose to display the sales total for a specific time period such as Month = June.
    
      - **Applying multiple filters** – Suppose that you have selected to display your organization’s sales total. You can apply multiple filters to this KPI so that the sales that meet the following criteria are displayed:
        
          - Salesperson Name = Kim Ackers
        
          - Month = June

8.  Select the **Split** check box to display the individual elements that make up the whole KPI.
    
    For example, suppose that you have selected to display your organization’s sales total. To split the sales total by salesperson, follow these steps:
    
    1.  Select the **Split** check box.
    
    2.  From the **Split by** list, select the salesperson, or worker dimension.
    
    3.  From the **Attribute** list, select an attribute, such as salesperson name.
    
    4.  From the **Show** list, select whether to display all salespeople, the salespeople who have the highest sales totals, or the salespeople who have the lowest sales totals.
    
    5.  Select the **Hide values of zero** check box to hide the names of salespeople who made no sales.

9.  You can format the name of the KPI as a hyperlink. The hyperlink can open Microsoft Dynamics AX menu items or a URL. To format the name of the KPI as a hyperlink, select one of the following options:
    
      - **Link to Microsoft Dynamics AX** – Select this option if you want the hyperlink to open Microsoft Dynamics AX menu items. Then select the menu items in the **Desktop Link** and **Enterprise Portal Link** lists.
        
        When you view the KPI in the Microsoft Dynamics AX client, the hyperlink will open the menu item that is specified in the **Desktop Link** field. When you view the KPI in Enterprise Portal, the hyperlink will open the menu item that is specified in the **Enterprise Portal Link** field.
    
      - **Link to URL** – Select this option if you want the hyperlink to open a URL. Then enter the URL.

10. Click **OK** to close the form and save your changes.

11. To add another KPI to the web part, repeat steps 1 through 10.

12. To rename the web part, follow these steps:
    
    1.  From the web part’s drop-down menu, click **Edit My Web Part**. The web part’s properties pane is displayed.
    
    2.  Expand the **Business Overview Setup** section.
    
    3.  In the **Title** field, enter a new name for the web part.
    
    4.  Click **OK** to save your changes.

## Modify a KPI

To modify a KPI that is displayed in a KPI List web part, follow these steps.

1.  In the web part, click **Manage KPIs**. The **Business Overview – Manage KPIs** form is displayed.

2.  Click the **Edit KPI** icon for the KPI that you want to modify. The **Business Overview – Edit KPI** form is displayed.

3.  To modify the KPI, follow steps 2 through 10 of the previous procedure.

  


