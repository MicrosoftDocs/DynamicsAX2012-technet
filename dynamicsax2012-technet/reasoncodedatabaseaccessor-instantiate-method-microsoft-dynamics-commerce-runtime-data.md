---
title: ReasonCodeDatabaseAccessor.Instantiate Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Instantiate Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDatabaseAccessor.Instantiate(Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore,Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.reasoncodedatabaseaccessor.instantiate(v=AX.60)
ms:contentKeyID: 65320048
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDatabaseAccessor.Instantiate
dev_langs:
- CSharp
- C++
- VB
---

# Instantiate Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Instantiate ( _
    dataStore As IDataStore, _
    context As RequestContext _
) As ReasonCodeDatabaseAccessor
'Usage
Dim dataStore As IDataStore
Dim context As RequestContext
Dim returnValue As ReasonCodeDatabaseAccessor

returnValue = ReasonCodeDatabaseAccessor.Instantiate(dataStore, _
    context)
```

``` csharp
public static ReasonCodeDatabaseAccessor Instantiate(
    IDataStore dataStore,
    RequestContext context
)
```

``` c++
public:
static ReasonCodeDatabaseAccessor^ Instantiate(
    IDataStore^ dataStore, 
    RequestContext^ context
)
```

#### Parameters

  - dataStore  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDataStore](idatastore-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.ReasonCodeDatabaseAccessor](reasoncodedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ReasonCodeDatabaseAccessor Class](reasoncodedatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

