---
title: About hour registration
TOCTitle: About hour registration
ms:assetid: 3183d12a-88a8-4e85-9da1-ff65e0ae4dbf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570050(v=AX.60)
ms:contentKeyID: 36056338
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- hour registration
- journal approval
- journal setup
- register hours
audience: Application User
ms.search.region: Global
---

# About hour registration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Workers can register hours in any of the project types that are available in the Project management and accounting.

Workers who will enter hour consumption must be registered in the **Worker** form in the **Human resources** resources module. Workers must be registered regardless of whether the hour registration is entered by the worker or by someone authorized to enter hours on his or her behalf.

Hour registrations are entered on journal lines. Journal lines can be posted as a batch from the **Journal** form.

## Journal setup

In the **Journal names** form, you must set up at least one journal that can be used for hour registrations. When you create new hour journals, they are identified by this name.

You can set up an optional approval procedure for hour journals. The approval procedure applies to the journals that are identified by the name that you specify in the **Journal names** form.

## Parameter setup

The following parameters must be defined in the **Journals** area in the **Project management and accounting parameters** form:

  - A default hour journal name in the **Hour** field.

  - A default Web journal name in the **Timesheet journal** field.

  - A default item journal name in the **Item** field.

  - A default fee journal name in the **Fee** field.

  - A default Beginning balance journal name in the **Beginning balances** field.

## See also

[Create a journal approval procedure](create-a-journal-approval-procedure.md)

[About journal names](about-journal-names.md)

[Journal names (form)](https://technet.microsoft.com/en-us/library/aa617509\(v=ax.60\))

[Journal names setup (form)](https://technet.microsoft.com/en-us/library/aa552517\(v=ax.60\))

[Set up project journal names](set-up-project-journal-options.md)

[Set up journal names](set-up-journal-names.md)

[Worker (form)](https://technet.microsoft.com/en-us/library/hh209054\(v=ax.60\))

[Project management and accounting parameters (form)](https://technet.microsoft.com/en-us/library/aa599440\(v=ax.60\))

  


