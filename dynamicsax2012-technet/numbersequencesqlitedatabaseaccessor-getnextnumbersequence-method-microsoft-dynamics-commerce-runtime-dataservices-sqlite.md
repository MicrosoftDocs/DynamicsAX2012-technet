---
title: NumberSequenceSqliteDatabaseAccessor.GetNextNumberSequence Method  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite)
TOCTitle: GetNextNumberSequence Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.NumberSequenceSqliteDatabaseAccessor.GetNextNumberSequence(System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.sqlite.numbersequencesqlitedatabaseaccessor.getnextnumbersequence(v=AX.60)
ms:contentKeyID: 65323031
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.NumberSequenceSqliteDatabaseAccessor.GetNextNumberSequence
dev_langs:
- CSharp
- C++
- VB
---

# GetNextNumberSequence Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function GetNextNumberSequence ( _
    sequenceTypeId As Integer _
) As Long
'Usage
Dim instance As NumberSequenceSqliteDatabaseAccessor
Dim sequenceTypeId As Integer
Dim returnValue As Long

returnValue = instance.GetNextNumberSequence(sequenceTypeId)
```

``` csharp
public long GetNextNumberSequence(
    int sequenceTypeId
)
```

``` c++
public:
long long GetNextNumberSequence(
    int sequenceTypeId
)
```

#### Parameters

  - sequenceTypeId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[NumberSequenceSqliteDatabaseAccessor Class](numbersequencesqlitedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-dataservices-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Sqlite Namespace](microsoft-dynamics-commerce-runtime-dataservices-sqlite-namespace.md)

