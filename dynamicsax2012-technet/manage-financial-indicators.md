---
title: Manage financial indicators
TOCTitle: Manage financial indicators
ms:assetid: 36792bee-81bc-4a79-8d01-2929ded5edbd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677297(v=AX.60)
ms:contentKeyID: 49384068
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Manage financial indicators [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Financial Indicator List web parts display financial calculations and compare those calculations with budgeted values. A financial indicator represents a measure in an online analytical processing (OLAP) cube, such as the General ledger cube. This topic explains how to add the Financial Indicator List web part to a page, and how to configure the web part to display financial indicators and budgeted values.


> [!NOTE]
> <P>Financial Indicator List web parts are available with Enterprise Portal for Microsoft Dynamics AX 2012 R2 or later.</P>



## Add the Financial Indicator List web part to a page

To add the Financial Indicator List web part to a page, follow the steps in [How to: Add Web Parts](https://technet.microsoft.com/en-us/library/cc604931\(v=ax.60\)).

After you add the Financial Indicator List web part to a page, the name of the web part is **Business overview**. The Financial Indicator List web part is a version of the Business Overview web part that is preconfigured to display financial indicators and budgeted values. You can change the name of the web part when you configure it by using the following procedure.

## Configure the Financial Indicator List web part

To configure the Financial Indicator List web part to display financial indicators and budgeted values, follow these steps.

1.  In the web part, click **Add Indicators**. The **Business Overview – Add Indicator** form is displayed.

2.  From the **Cube** list, select a cube that contains budgeted values, such as the General ledger cube.
    
    For more information about the General ledger cube, see [General ledger cube (LedgerCube) for Microsoft Dynamics AX 2012 R2](http://go.microsoft.com/fwlink/?linkid=268893).

3.  From the **Indicator** list, select the indicator to display.

4.  From the **Budget indicator** list, select the budgeted value that corresponds with the indicator that you selected in the previous step.
    
    For example, suppose that you want to display your organization’s operating expense. Using the default General ledger cube, you would make the following selections:
    
      - **Indicator:** General ledger operating expense total – accounting currency
    
      - **Budget indicator:** General ledger operating expense total revised budget amount – accounting currency

5.  From the **Display value as** list, select whether to display the values as monetary amounts or numbers. Then specify which colors represent positive and negative values.

6.  In the **Display name** field, enter a name for the indicator. This name is displayed to users. If you do not enter a name in this field, the name in the **Indicator** field is displayed to users.

7.  Select the **Visible** check box to display the indicator (and its corresponding budgeted value) in the web part.

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
        
        When you view the indicator in the Microsoft Dynamics AX client, the hyperlink will open the menu item that is specified in the **Desktop Link** field. When you view the indicator in Enterprise Portal, the hyperlink will open the menu item that is specified in the **Enterprise Portal Link** field.
    
      - **Link to URL** – Select this option if you want the hyperlink to open a URL. Then enter the URL.

11. Click **OK** to close the form and save your changes.

12. To add another indicator to the web part, repeat steps 1 through 11.

13. To rename the web part, follow these steps:
    
    1.  From the web part’s drop-down menu, click **Edit My Web Part**. The web part’s properties pane is displayed.
    
    2.  Expand the **Business Overview Setup** section.
    
    3.  In the **Title** field, enter a new name for the web part.
    
    4.  Click **OK** to save your changes.

## Modify an indicator

To modify an indicator that is displayed in a Financial Indicator List web part, follow these steps.

1.  In the web part, click **Manage Indicators**. The **Business Overview – Manage Indicators** form is displayed.

2.  Click the **Edit Indicator** icon for the indicator that you want to modify. The **Business Overview – Edit Indicator** form is displayed.

3.  To modify the indicator, follow steps 2 through 11 of the previous procedure.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

