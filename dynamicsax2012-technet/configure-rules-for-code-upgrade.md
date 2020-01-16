---
title: Configure rules for code upgrade
TOCTitle: Configure rules for code upgrade
ms:assetid: 6bfc6138-20a0-4c58-b47d-5e235203f03f
ms:mtpsurl: https://technet.microsoft.com/library/JJ677305(v=AX.60)
ms:contentKeyID: 49384076
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure rules for code upgrade 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In the **Configure rules for code upgrade** task, you can configure rules for code conflicts. Code conflict rules can reduce the time that is required to upgrade customized application code. The rules that are provided by Microsoft alert you about changes to X++ classes, tables, and form methods that you may have customized. In the **Detect code upgrade conflicts** step, the rules are used to create a development project that contains any issues that are discovered, and organizes the issues for easy review and resolution.

## Configure rules

To import the set of code upgrade rules that is provided by Microsoft, complete the following procedure. The procedure is the same for upgrades that use the **AOD code upgrade checklist** and upgrades that use the **Model code upgrade checklist**.

1.  Click the task name. A message window prompts you to import a DLL,Microsoft.Dynamics.AX.Framework.Tools.CodeUpgradeTool.Rules.dll. This file contains the default code conflict rules. Click **OK**.

2.  In the **Manage code upgrade rules** form, click **Configure code upgrade rules**.

3.  In the **Code upgrade rules** form, click **Browse...**, and then navigate to the location of the Microsoft.Dynamics.AX.Framework.Tools.CodeUpgradeTool.Rules.dll file. This file is located in the Client\\Bin directory of the computer where you installed Microsoft Dynamics AX 2012 R2 or R3, typically at C:\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Client\\Bin. Select the file, and then click **Open**.

4.  In the **Code upgrade rules** form, click **Import rules**. The grid is populated with a list of rules that provides the following information:
    
      - **Rule author** – The source of the rule. For the default rules, the author is Microsoft.
    
      - **Rule description** – A verbose description of what the rule does.
    
      - **Rule name** – The short name of the rule.
    
      - **Target version** – The version of Microsoft Dynamics AX on the target system.
    
      - **Rule category** – The rule’s membership in a top-level category in the **Manage code upgrade rules** form.
    
    For more information about the **Code upgrade rules** form, see [Code upgrade rules (form)](https://technet.microsoft.com/library/jj677374\(v=ax.60\)).

If you now open the **Manage code upgrade rules** form, you can view a hierarchy of rule categories under the **Configure code upgrade rules** node. The default categories include the following categories:

  - **AddressBook**

  - **FormLetter**

  - **Installation specific Ids**

  - **Inventory**

  - **Number sequence framework**

  - **XppCompiler**

A similar procedure can be used to import other rule sets that you create yourself and organize into your own categories. For developer documentation about code upgrade, see the [code upgrade white papers](https://go.microsoft.com/fwlink/?linkid=215083%26clcid=0x409).

  


