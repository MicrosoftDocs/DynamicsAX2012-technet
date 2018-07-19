---
title: Configure project budget control
TOCTitle: Configure project budget control
ms:assetid: 17d8d1f8-f5e5-4ea8-a4d5-9999eeaaa96a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208441(v=AX.60)
ms:contentKeyID: 36056091
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- project
- budget
- project budget
- budget control
- project budget control
audience: Application User
ms.search.region: Global
---

# Configure project budget control 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Project budget control is the practice of authorizing expenditure only when budget funds can be reserved to meet future payment commitments. Budget control is usually configured for each project. However, several settings for budget control apply to all projects. Before you configure individual project budgets, ask several questions about your organization, and then use the answers to configure the settings that apply to all project budgets.


> [!NOTE]
> <P>For information about how to configure individual project budgets, see <A href="create-and-submit-an-original-project-budget.md">Create and submit an original project budget</A>.</P>



## Project budget considerations

  - When do you want to perform budget control? You receive fewer messages that you are over budget if you perform budget control when the actual costs from vendor invoices and journals are posted to the project. You can also improve system performance by performing budget checks less often.

  - Do you want to use projects that are outside the project hierarchy for budget control?

  - What do you want to use as the default range of periods when you set up budget control for new projects?

  - Do you have multiyear projects? If you have multiyear projects, do you want budget amounts that have not been spent by the end of a year to be carried forward to a future year? If a budget is negative at the end of the year, do you want the budget amounts that are available in the next year to be reduced?

## Configure settings for a project budget

When you change settings in the **Project management and accounting parameters** form, the settings for existing projects are not changed. Only projects that are created after you change a setting are affected. You can also select different settings when you set up individual projects.

1.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**. Click **Cost control**.

2.  In the **Cost commitments** group, complete one of the following steps, depending on when you want to check the budget and reduce the remaining budget amounts:
    
      - To perform budget control when the actual costs are posted to the project, clear all check boxes.
    
      - To perform budget control before the actual costs are posted to the project, select the transaction types for which you want to enable committed costs. For each transaction type that you select, the project budget is checked and the available budget amounts are reduced when the transactions are submitted to the workflow.
        
        To perform budget control when each line of the transaction is saved, instead of when the transaction is submitted to the workflow, select the **Check budget on document line save** check box in the **Budget control** group.

3.  In the **Budget control** group, select whether budget control applies to projects that are outside the project hierarchy.
    
      - If the default settings for the budget group apply to projects that are outside the project hierarchy, select the **Allow budget control outside the project hierarchy** check box.
    
      - If the default settings for the budget group apply only to projects that are inside the project hierarchy, clear the **Allow budget control outside the project hierarchy** check box.
        

        > [!NOTE]
        > <P>To use budget control for a project, budget control must be enabled in the <STRONG>Projects</STRONG> form.</P>



4.  In the **Budget control** group, in the **Budget control interval** field, select the interval that you want to use as the default range of periods for your projects.
    

    > [!NOTE]
    > <P>If you change the default setting, only projects that are created after you change the setting are affected. The range of periods for existing projects is not changed. You can always select a different range of periods when you set up individual projects.</P>



5.  In the **Budget control** group, select whether you want amounts that remain in the project budget to be carried forward at the end of the year.
    
      - If you want remaining budget amounts to be carried forward, select the **Carry forward remaining budgets** check box.
        
        If you want negative budget amounts to be carried forward, you must also select the **Allow negative budgets to be carried forward** check box.
    
      - If you do not want remaining budget amounts to be carried forward, clear the **Carry forward remaining budgets** check box.

## See also

[About setting up a project budget](about-setting-up-a-project-budget.md)

[Create forecast models for project budgets](create-forecast-models-for-project-budgets.md)

[Configure project budget overrun settings](configure-project-budget-overrun-settings.md)

[Create and submit an original project budget](create-and-submit-an-original-project-budget.md)

[Carry forward project budgets at year-end](carry-forward-project-budgets-at-year-end.md)

[Project management and accounting parameters (form)](https://technet.microsoft.com/en-us/library/aa599440\(v=ax.60\))

  


