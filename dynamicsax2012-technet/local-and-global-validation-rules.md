---
title: Local and global validation rules
TOCTitle: Local and global validation rules
ms:assetid: 329f584b-a5b1-4d84-9891-33e97ba8e0bb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570065(v=AX.60)
ms:contentKeyID: 36056536
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Local and global validation rules [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Validation rules are used for validation of user input after a user has entered a value for a modeling variable. For example, if you are creating a product model for a lamp and want to restrict the user's choice of the lamp height to a certain range in case he or she had selected 3 or more bulbs for it, you would use validation rules to set this up.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



## Local and global validation rules

Validation rules can be global and local. Global rules can be applied to several models and local rules are set up for only one product model.

Click **Product information management** \> **Setup** \> **Product builder** \> **Global rules**. This location is only for modeling variables, not for calculation variables, because they are specific for each product model. The product models that the rule will apply to are selected in the lower pane of the form on the **Versions** tab. Before the rule can be active for the product model, it must be approved and activated. This procedure is standard and is the same as for BOM versions. The rule itself is created in the **Rules** form that opens when you click **Validation**.

You can create validation rules for both modeling and calculation variables in the **Rules** form that opens when you click **Validation** in the **Product model** form or the **Modeling variables** form.

## See also

[About version validity](about-version-validity.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

