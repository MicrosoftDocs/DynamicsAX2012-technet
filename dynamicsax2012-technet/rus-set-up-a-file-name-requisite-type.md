---
title: (RUS) Set up a file name requisite type
TOCTitle: (RUS) Set up a file name requisite type
ms:assetid: e0392116-ad0a-4d90-8d0e-b167ad66af58
ms:mtpsurl: https://technet.microsoft.com/library/JJ710631(v=AX.60)
ms:contentKeyID: 49385028
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- requisite
- file name
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a file name requisite type 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Fixed requisites** form to set up a file name requisite type for reports that are exported in an XML format.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Fixed requisites**.

2.  Click **New** to create a line.

3.  In the **Requisite** field, select a fixed requisite code.

4.  In the **Name** field, enter a name for the requisite.

5.  In the **Type** field, select **File name**.

6.  In the **Value** field, enter %??????%\_%%????????%%%\_%gggg%%mm%%dd%\_%guid%.xml, replacing the variables as follows:
    
      - %??????% – A built-in macro that is replaced with the values from the **File name** and **File name prefix** fields in the **Periods of formats application** form.
    
      - %%????????%% – The name of the employee.
    
      - %gggg% – The current year.
    
      - %mm% – The current month.
    
      - %dd% – The current date.
    
      - %guid% – A globally unique identifier.

## See also

[(RUS) Fixed requisites (form)](https://technet.microsoft.com/library/jj710680\(v=ax.60\))

[(RUS) Set up a fixed requisite](rus-set-up-a-fixed-requisite.md)

  


