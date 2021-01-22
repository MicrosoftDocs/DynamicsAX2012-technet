---
title: Create and submit an original project budget
TOCTitle: Create and submit an original project budget
ms:assetid: aab445d0-783a-497b-96ce-d0b8fc819e47
ms:mtpsurl: https://technet.microsoft.com/library/Hh242692(v=AX.60)
ms:contentKeyID: 36058903
author: Khairunj
ms.author: daxcpft
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project
- budget
- project budget
- original budget
- original project budget
audience: Application User
ms.search.region: Global
---

# Create and submit an original project budget 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you create a budget for a project in Microsoft Dynamics AX, you must select several settings in the program. These settings help you control the types of transactions, project categories, and budget overruns that apply to a project. You can select the starting and ending dates for the budget, and whether to allocate the budget amounts to multiple fiscal periods. You can also specify different settings for specific users and user groups.

After you select the settings for a project budget, create a budget for the estimated costs and related revenue amounts for the project. You can manually enter budget amounts or you can copy amounts from a forecast model or from another project. After you create a project budget, you can submit it to workflow for approval.

### Configure settings for a project budget

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Open a project. In the **Projects** form, on the **Budget and forecast** FastTab, enter settings. Alternatively, review the settings and make any necessary changes. To make the fields editable, on the **Action Pane**, on the **Project** tab, click **Edit**.
    
      - **Use budget control** – Select this check box to enable budget tracking.
        

        > [!NOTE]
        > <P>If you select this check box before a budget has been approved, all transactions are considered budget overruns.</P>

    
      - **Transaction types controlled** – Select the types of transactions that are controlled. You can enter budget amounts only for transactions types that are controlled. For example, if you select **Costs only**, you cannot enter revenue amounts in your budget.
    
      - **Budget overrun default** – Select the overrun option that you want to use for this project.
        
          - **Disallow overruns** – Users cannot enter a transaction.
        
          - **Warn of overruns** – Users receive a warning when they enter a transaction. The transaction is processed normally.
        
          - **Allow overruns** – Users do not receive a warning when they enter a transaction. The transaction is processed normally.
    
      - **User group override** – Click **Settings** to specify a different setting for budget overruns for specific user groups. For more information, see [Configure project budget overrun settings](configure-project-budget-overrun-settings.md).
    
      - **Use alternate project budget for budget verification** – Select this check box to use the budget from another project as the original budget for this project. The project that you want to use must already be set up for budget control. Otherwise, you cannot select the project here.
    
      - **Budget control interval** – Select the range of periods that you want to use for this project.
    
      - **Carry forward remaining budgets** – Select this check box if you want budget amounts that have not been spent at the end of the fiscal period to be carried forward to a future fiscal period.
    
      - **Allow negative budgets to be carried forward** – Select this check box if you want negative budget amounts to be carried forward to a future fiscal period. Negative amounts that are carried forward reduce the budgeted amounts that are available in the future fiscal period.
        

        > [!NOTE]
        > <P>Negative budgets can occur only if <STRONG>Allow overruns</STRONG> is selected in the <STRONG>Budget overrun default</STRONG> field.</P>



### Create an original project budget

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Select or open a project. To make the fields editable, on the **Action Pane**, on the **Project** tab, click **Edit**. On the **Action Pane**, on the **Plan** tab, in the **Budget** group, click **Project budget**.

3.  In the **Project budget** form, on the **General** FastTab, under **Forecast models**, select the forecast models that you want to use for the original budget and remaining budget. These forecast models are used by project control and project reports when you compare actual amounts to budgeted amounts.

4.  In the **Budget source** field, select the source that you want to use for the amounts in the original budget.
    
      - **Entry** – The original budget amounts are manually entered into the form.
    
      - **Forecast** – The original budget amounts are loaded from a forecast model.
        

        > [!NOTE]
        > <P>The <STRONG>Forecast model</STRONG> field becomes available when this option is selected.</P>

    
      - **Project transactions** – The original budget amounts are loaded from an existing project budget.
        

        > [!NOTE]
        > <P>The <STRONG>Project</STRONG> field becomes available when this option is selected.</P>



5.  Depending on the budget source that you selected, complete one of the following steps:
    
      - If you selected **Entry** as the budget source:
        
        1.  On the **Costs** FastTab, click **New**, and then enter the category and original budget amount for hours, expenses, and items. Use total amounts, not the number of hours or items.
            

            > [!NOTE]
            > <P>If category validation is enabled for the project, only the project categories that are assigned to the project are available for selection in a budget line.</P>

        
        2.  Depending on your version of the program, do one of the following:
            
              - In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: On the **Revenues** FastTab, click **Generate from cost budget lines**. A line with a revenue amount is automatically added for each project category that you enter on the **Costs** FastTab. The revenue amount is copied from the sales value for the selected project category. If a sales value was not specified for the project category, the revenue amount is 0 for the line. You can modify the revenue amount.
            
              - Otherwise, on the **Revenues** FastTab, click **New**, and then enter the category and budget revenue amount for hours, expenses, items, and fees. Use total amounts, not the number of hours or items.
    
      - If you selected **Forecast** as the budget source:
        
        1.  In the **Forecast model** field, select the forecast model that you want to use as the source of the original budget, and then click **Load values**.
        
        2.  Review the amounts that are loaded into the budget, and make any changes that you have to make for this project.
    
      - If you selected **Project transactions** as the budget source:
        
        1.  In the **Project** field, select the project that you want to use as the source of the original budget, and then click **Load values**.
        
        2.  Review the amounts that are loaded into the budget, and then make any necessary changes to the budget.

6.  Optional: To allocate the budget, on the **Action Pane**, on the **Budget** tab, click **Allocate budget**. For more information, see [Allocate a project budget or budget revision across periods](allocate-a-project-budget-or-budget-revision-across-periods.md).

7.  To send the budget to workflow, click the **Submit** button.

## See also

[About setting up a project budget](about-setting-up-a-project-budget.md)

[Configure project budget control](configure-project-budget-control.md)

[Create forecast models for project budgets](create-forecast-models-for-project-budgets.md)

[Configure project budget overrun settings](configure-project-budget-overrun-settings.md)

[Revise and submit a project budget](revise-and-submit-a-project-budget.md)

[Allocate a project budget or budget revision across periods](allocate-a-project-budget-or-budget-revision-across-periods.md)

[Carry forward project budgets at year-end](carry-forward-project-budgets-at-year-end.md)

[Project budget (form)](https://technet.microsoft.com/library/hh227438\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/library/aa585245\(v=ax.60\))

[Project budget settings for user groups (form)](https://technet.microsoft.com/library/hh242598\(v=ax.60\))

[Project budget allocation (form)](https://technet.microsoft.com/library/hh242461\(v=ax.60\))

  


