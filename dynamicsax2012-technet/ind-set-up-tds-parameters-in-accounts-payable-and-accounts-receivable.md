---
title: (IND) Set up TDS parameters in Accounts payable and Accounts receivable
TOCTitle: (IND) Set up TDS parameters in Accounts payable and Accounts receivable
ms:assetid: cbe7edb8-f7ef-4f52-b9c0-6f66e00d88da
ms:mtpsurl: https://technet.microsoft.com/library/JJ664912(v=AX.60)
ms:contentKeyID: 49386241
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up TDS parameters in Accounts payable and Accounts receivable 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**. On the **Updates** tab, click **Update order lines**.
    
    –or–
    
    Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.On the **Updates** tab, click **Update order lines**.

2.  In the **TDS group** field, specify the method that is used to update the TDS group in the line level when the TDS group is updated in the header level in the **Updating TDS group** field. The options are as follows:
    
      - **Never** – The TDS group is not updated in the order lines when the TDS group is updated in the order header.
    
      - **Always** – The TDS group is updated automatically in the order lines when the TDS group is updated in the order header.
    
      - **Prompt** – A message is displayed that prompts you to update the TDS group in the order lines

3.  Click **OK** to save the settings.

## See also

[(IND) Accounts payable parameters (modified form)](https://technet.microsoft.com/library/jj664793\(v=ax.60\))

  


