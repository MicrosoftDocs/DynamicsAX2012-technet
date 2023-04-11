---
title: ShiftDataManager.Update Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Update Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.Update(Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.shiftdatamanager.update(v=AX.60)
ms:contentKeyID: 62210983
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ShiftDataManager.Update
dev_langs:
- CSharp
- C++
- VB
---

# Update Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the Shift record in database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub Update ( _
    shift As Shift _
)
'Usage
Dim instance As ShiftDataManager
Dim shift As Shift

instance.Update(shift)
```

``` csharp
public void Update(
    Shift shift
)
```

``` c++
public:
void Update(
    Shift^ shift
)
```

#### Parameters

  - shift  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ShiftDataManager Class](shiftdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

