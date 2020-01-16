---
title: ProductManager.GetUnitOfMeasure Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetUnitOfMeasure Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetUnitOfMeasure(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getunitofmeasure(v=AX.60)
ms:contentKeyID: 65321333
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetUnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# GetUnitOfMeasure Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetUnitOfMeasure ( _
    unitId As String, _
    settings As QueryResultSettings _
) As UnitOfMeasure
'Usage
Dim instance As ProductManager
Dim unitId As String
Dim settings As QueryResultSettings
Dim returnValue As UnitOfMeasure

returnValue = instance.GetUnitOfMeasure(unitId, _
    settings)
```

``` csharp
public UnitOfMeasure GetUnitOfMeasure(
    string unitId,
    QueryResultSettings settings
)
```

``` c++
public:
UnitOfMeasure^ GetUnitOfMeasure(
    String^ unitId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - unitId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasure](unitofmeasure-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

