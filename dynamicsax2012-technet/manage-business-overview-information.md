---
title: Manage business overview information
TOCTitle: Manage business overview information
ms:assetid: 3ca6940a-eacd-4da0-840d-a816e562fc61
ms:mtpsurl: https://technet.microsoft.com/library/Hh242231(v=AX.60)
ms:contentKeyID: 36056664
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Manage business overview information 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Business Overview web parts can display indicators or key performance indicators (KPIs).

  - An indicator is a data calculation across various time periods. An indicator represents a measure in an online analytical processing (OLAP) cube.

  - A KPI is a business metric, such as total revenue, gross profit margin, or current ratio. A KPI can help you track your organization’s progress toward a performance goal.

This topic explains how to add the Business Overview web part to a page, and how to configure the web part to display indicators or KPIs. The procedures for completing these tasks differ based on the version of Microsoft Dynamics AX that you are using.

## Procedures for Microsoft Dynamics AX 2012 R2 or later

If you are using Microsoft Dynamics AX 2012 R2 or later, use the following procedures to add the Business Overview web part to a page and configure it to display indicators or KPIs.

## Add the Business Overview web part to a page

To add the Business Overview web part to a page, follow the steps in [How to: Add Web Parts](https://technet.microsoft.com/library/cc604931\(v=ax.60\)).

## Configure the Business Overview web part to display indicators

To configure the Business Overview web part to display indicators, follow these steps.

1.  To specify that the web part displays indicators instead of KPIs, follow these steps:
    
    1.  From the web part’s drop-down menu, click **Edit My Web Part**. The web part’s properties pane is displayed.
    
    2.  From the **Select mode** list, select **Business Overview**.
        

        > [!NOTE]
        > <P>If the <STRONG>Select mode</STRONG> list is unavailable, KPIs most likely have already been added to the web part. The Business Overview web part cannot display both indicators and KPIs at the same time. To display indicators, you must either delete the KPIs or add another Business Overview web part to the page.</P>

    
    3.  Click **OK**.

2.  In the web part, click **Add Indicators**. The **Business Overview – Add Indicator** form is displayed.

3.  From the **Cube** list, select the cube that contains the indicator, or measure, that you want to display.
    
    For more information about the measures that are contained in each cube, see the [Cube and KPI reference for Microsoft Dynamics AX 2012 R2](https://go.microsoft.com/fwlink/?linkid=268892).

4.  From the **Indicator** list, select the indicator to display.

5.  From the **Display value as** list, select whether to display the indicator value as a monetary amount or a number. Then specify which colors represent positive and negative values.

6.  In the **Display name** field, enter a name for the indicator. This name is displayed to users. If you do not enter a name in this field, the name in the **Indicator** field is displayed to users.

7.  Select the **Visible** check box to display the indicator in the web part.

8.  Select the **Apply filters** check box to enter filters, if you require them. You can filter indicators by relative dates or actual values. You can also apply multiple filters.
    
      - **Filtering by relative dates or actual values** – Suppose that you have selected to display your organization’s operating expense. If you want to filter this indicator by a relative date, you could choose to display the operating expense for last year, last month, or last quarter. If you want to filter this indicator by an actual value, you could choose to display the operating expense for a specific time period such as Year = 2013.
    
      - **Applying multiple filters** – Suppose that you have selected to display your organization’s operating expense. You can apply multiple filters to this indicator so that the operating expense total meets the following criteria:
        
          - Company Name = Fabrikam, Inc.
        
          - Year = 2013

9.  Select the **Split** check box to display the individual elements that make up the whole indicator.
    
    For example, suppose that you have selected to display your organization’s operating expense. To split the operating expense by company, follow these steps:
    
    1.  Select the **Split** check box.
    
    2.  From the **Split by** list, select the company dimension.
    
    3.  From the **Attribute** list, select an attribute, such as company name.
    
    4.  From the **Show** list, select whether to display all companies, the companies that have the highest operating expense, or the companies that have the lowest operating expense.
    
    5.  Select the **Hide values of zero** check box to hide the names of companies that have no operating expense.

10. You can format the name of the indicator as a hyperlink. The hyperlink can open Microsoft Dynamics AX menu items or a URL. To format the name of the indicator as a hyperlink, select one of the following options:
    
      - **Link to Microsoft Dynamics AX** – Select this option if you want the hyperlink to open Microsoft Dynamics AX menu items. Then select the menu items in the **Desktop Link** and **Enterprise Portal Link** lists.
        
        When you view the indicator in the Microsoft Dynamics AX client, the hyperlink will open the menu item that is specified in the **Desktop Link** field. When you view the indicator in Enterprise Portal for Microsoft Dynamics AX, the hyperlink will open the menu item that is specified in the **Enterprise Portal Link** field.
    
      - **Link to URL** – Select this option if you want the hyperlink to open a URL. Then enter the URL.

11. Click **OK** to close the form and save your changes.

12. To add another indicator to the web part, repeat steps 2 through 11.

13. To rename the web part, follow these steps:
    
    1.  From the web part’s drop-down menu, click **Edit My Web Part**. The web part’s properties pane is displayed.
    
    2.  Expand the **Business Overview Setup** section.
    
    3.  In the **Title** field, enter a new name for the web part.
    
    4.  Click **OK** to save your changes.

## Modify an indicator

To modify an indicator that is displayed in a Business Overview web part, follow these steps.

1.  In the web part, click **Manage Indicators**. The **Business Overview – Manage Indicators** form is displayed.

2.  Click the **Edit Indicator** icon for the indicator that you want to modify. The **Business Overview – Edit Indicator** form is displayed.

3.  To modify the indicator, follow steps 3 through 11 of the previous procedure.

## Configure the Business Overview web part to display KPIs

To configure the Business Overview web part to display KPIs, follow these steps.

1.  To specify that the web part displays KPIs instead of indicators, follow these steps:
    
    1.  From the web part’s drop-down menu, click **Edit My Web Part**. The web part’s properties pane is displayed.
    
    2.  From the **Select mode** list, select **KPI List**.
        

        > [!NOTE]
        > <P>If the <STRONG>Select mode</STRONG> list is unavailable, indicators most likely have already been added to the web part. The Business Overview web part cannot display both KPIs and indicators at the same time. To display KPIs, you must either delete the indicators or add another Business Overview web part to the page.</P>

    
    3.  Click **OK**.

2.  In the web part, click **Add KPIs**. The **Business Overview – Add KPI** form is displayed.

3.  From the **Cube** list, select the cube that contains the KPI that you want to display.
    
    For more information about the KPIs that are contained in each cube, see the [Cube and KPI reference for Microsoft Dynamics AX 2012 R2](https://go.microsoft.com/fwlink/?linkid=268892).

4.  From the **KPI** list, select the KPI to display.

5.  From the **Display value as** list, select whether to display the KPI value as a monetary amount or a number. Then specify which colors represent positive and negative values.

6.  In the **Display name** field, enter a name for the KPI. This name is displayed to users. If you do not enter a name in this field, the name in the **KPI** field is displayed to users.

7.  Select the **Visible** check box to display the KPI in the web part.

8.  Select the **Apply filters** check box to enter filters, if you require them. You can filter KPIs by relative dates or actual values. You can also apply multiple filters.
    
      - **Filtering by relative dates or actual values** – Suppose that you have selected to display your organization’s sales total. If you want to filter this KPI by a relative date, you could choose to display the sales total for last year, last month, or last quarter. If you want to filter this KPI by an actual value, you could choose to display the sales total for a specific time period such as Month = June.
    
      - **Applying multiple filters** – Suppose that you have selected to display your organization’s sales total. You can apply multiple filters to this KPI so that the sales that meet the following criteria are displayed:
        
          - Salesperson Name = Kim Ackers
        
          - Month = June

9.  Select the **Split** check box to display the individual elements that make up the whole KPI.
    
    For example, suppose that you have selected to display your organization’s sales total. To split the sales total by salesperson, follow these steps:
    
    1.  Select the **Split** check box.
    
    2.  From the **Split by** list, select the salesperson, or worker dimension.
    
    3.  From the **Attribute** list, select an attribute, such as salesperson name.
    
    4.  From the **Show** list, select whether to display all salespeople, the salespeople who have the highest sales totals, or the salespeople who have the lowest sales totals.
    
    5.  Select the **Hide values of zero** check box to hide the names of salespeople who made no sales.

10. You can format the name of the KPI as a hyperlink. The hyperlink can open Microsoft Dynamics AX menu items or a URL. To format the name of the KPI as a hyperlink, select one of the following options:
    
      - **Link to Microsoft Dynamics AX** – Select this option if you want the hyperlink to open Microsoft Dynamics AX menu items. Then select the menu items in the **Desktop Link** and **Enterprise Portal Link** lists.
        
        When you view the KPI in the Microsoft Dynamics AX client, the hyperlink will open the menu item that is specified in the **Desktop Link** field. When you view the KPI in Enterprise Portal for Microsoft Dynamics AX, the hyperlink will open the menu item that is specified in the **Enterprise Portal Link** field.
    
      - **Link to URL** – Select this option if you want the hyperlink to open a URL. Then enter the URL.

11. Click **OK** to close the form and save your changes.

12. To add another KPI to the web part, repeat steps 2 through 11.

13. To rename the web part, follow these steps:
    
    1.  From the web part’s drop-down menu, click **Edit My Web Part**. The web part’s properties pane is displayed.
    
    2.  Expand the **Business Overview Setup** section.
    
    3.  In the **Title** field, enter a new name for the web part.
    
    4.  Click **OK** to save your changes.

## Modify a KPI

To modify a KPI that is displayed in a Business Overview web part, follow these steps.

1.  In the web part, click **Manage KPIs**. The **Business Overview – Manage KPIs** form is displayed.

2.  Click the **Edit KPI** icon for the KPI that you want to modify. The **Business Overview – Edit KPI** form is displayed.

3.  To modify the KPI, follow steps 3 through 11 of the previous procedure.

## Procedures for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack

If you are using the initial version of Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack, use the following procedures to add the Business Overview web part to a page and configure it to display indicators or KPIs.

## Add the Business Overview web part to a page

To add the Business Overview web part to a page, follow the steps in [How to: Add Web Parts](https://technet.microsoft.com/library/cc604931\(v=ax.60\)).

## Configure the Business Overview web part to display indicators

To configure the Business Overview web part to display indicators, follow these steps.

1.  To specify that the web part displays indicators instead of KPIs, follow these steps:
    
    1.  From the web part’s drop-down menu, click **Edit My Web Part**. The web part’s properties pane is displayed.
    
    2.  From the **Select mode** list, select **Business Overview**.
        

        > [!NOTE]
        > <P>If the <STRONG>Select mode</STRONG> list is unavailable, KPIs most likely have already been added to the web part. The Business Overview web part cannot display both indicators and KPIs at the same time. To display indicators, you must either delete the KPIs or add another Business Overview web part to the page.</P>

    
    3.  Click **OK**.

2.  In the web part, click **Add Indicators**. The **Business Overview – Add Indicator** form is displayed.

3.  From the **Cube** list, select the cube that contains the indicator, or measure, that you want to display.
    
    For more information about the measures that are contained in each cube, see the [Cube and KPI reference for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack](cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-and-microsoft-dynamics-ax-2012-feature-pack.md).

4.  From the **Indicator** list, select the indicator to display.

5.  To filter the indicator to display data from a specific time period, select a date dimension and a period in the **Date dimension** and **Period** lists.

6.  Select the **Display split by** check box to display the individual elements that make up the whole indicator.
    
    For example, suppose that you have selected to display your organization’s operating expense. To split the operating expense by company, follow these steps:
    
    1.  Select the **Display split by** check box.
    
    2.  From the **Dimension** list, select the company dimension.
    
    3.  From the **Attribute** list, select an attribute, such as company name.

7.  From the **Display value as** list, select whether to display the indicator value as a monetary amount or a number. Then specify which colors positive and negative values.

8.  You can format the name of the indicator as a hyperlink. To do so, enter the target URL in the **Report link** field. For example, you may want the hyperlink to open a report.

9.  In the **Display name** field, enter a name for the indicator. This name is displayed to users. If you do not enter a name in this field, the name in the **Indicator** field is displayed to users.

10. Select the **Visible** check box to display the indicator in the web part.

11. Click **OK** to close the form and save your changes.

12. To add another indicator to the web part, repeat steps 2 through 11.

13. To rename the web part, follow these steps:
    
    1.  From the web part’s drop-down menu, click **Edit My Web Part**. The web part’s properties pane is displayed.
    
    2.  Expand the **Business Overview Setup** section.
    
    3.  In the **Title** field, enter a new name for the web part.
    
    4.  Click **OK** to save your changes.

## Modify an indicator

To modify an indicator that is displayed in a Business Overview web part, follow these steps.

1.  In the web part, click **Manage Indicators**. The **Business Overview – Manage Indicators** form is displayed.

2.  Click the **Edit Indicator** icon for the indicator that you want to modify. The **Business Overview – Edit Indicator** form is displayed.

3.  To modify the indicator, follow steps 3 through 11 of the previous procedure.

## Configure the Business Overview web part to display KPIs

To configure the Business Overview web part to display KPIs, follow these steps.

1.  To specify that the web part displays KPIs instead of indicators, follow these steps:
    
    1.  From the web part’s drop-down menu, click **Edit My Web Part**. The web part’s properties pane is displayed.
    
    2.  From the **Select mode** list, select **KPI List**.
        

        > [!NOTE]
        > <P>If the <STRONG>Select mode</STRONG> list is unavailable, indicators most likely have already been added to the web part. The Business Overview web part cannot display both KPIs and indicators at the same time. To display KPIs, you must either delete the indicators or add another Business Overview web part to the page.</P>

    
    3.  Click **OK**.

2.  In the web part, click **Add KPIs**. The **Business Overview – Add KPI** form is displayed.

3.  From the **Cube** list, select the cube that contains the KPI that you want to display.
    
    For more information about the KPIs that are contained in each cube, see the [Cube and KPI reference for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack](cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-and-microsoft-dynamics-ax-2012-feature-pack.md).

4.  From the **KPI** list, select the KPI to display.

5.  To filter the KPI to display data from a specific time period, select a date dimension and a period in the **Date dimension** and **Period** lists.

6.  Select the **Display split by** check box to display the individual elements that make up the whole KPI.
    
    For example, suppose that you have selected to display your organization’s sales total. To split the sales total by salesperson, follow these steps:
    
    1.  Select the **Display split by** check box.
    
    2.  From the **Dimension** list, select the salesperson, or worker dimension.
    
    3.  From the **Attribute** list, select an attribute, such as salesperson name.

7.  From the **Display value as** list, select whether to display the KPI value as a monetary amount or a number. Then specify which colors represent positive and negative values.

8.  You can format the name of the KPI as a hyperlink. To do so, enter the target URL in the **Report link** field. For example, you may want the hyperlink to open a report.

9.  In the **Display name** field, enter a name for the KPI. This name is displayed to users. If you do not enter a name in this field, the name in the **KPI** field is displayed to users.

10. Select the **Visible** check box to display the KPI in the web part.

11. Click **OK** to close the form and save your changes.

12. To add another KPI to the web part, repeat steps 2 through 11.

13. To rename the web part, follow these steps:
    
    1.  From the web part’s drop-down menu, click **Edit My Web Part**. The web part’s properties pane is displayed.
    
    2.  Expand the **Business Overview Setup** section.
    
    3.  In the **Title** field, enter a new name for the web part.
    
    4.  Click **OK** to save your changes.

## Modify a KPI

To modify a KPI that is displayed in a Business Overview web part, follow these steps.

1.  In the web part, click **Manage KPIs**. The **Business Overview – Manage KPIs** form is displayed.

2.  Click the **Edit KPI** icon for the KPI that you want to modify. The **Business Overview – Edit KPI** form is displayed.

3.  To modify the KPI, follow steps 3 through 11 of the previous procedure.

  


