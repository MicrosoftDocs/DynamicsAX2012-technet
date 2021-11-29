---
title: IndiaTaxDatabaseAccessor.GetWarehouseAddressIndia Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetWarehouseAddressIndia Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDatabaseAccessor.GetWarehouseAddressIndia(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.indiataxdatabaseaccessor.getwarehouseaddressindia(v=AX.60)
ms:contentKeyID: 65316063
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IndiaTaxDatabaseAccessor.GetWarehouseAddressIndia
dev_langs:
- CSharp
- C++
- VB
---

# GetWarehouseAddressIndia Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetWarehouseAddressIndia ( _
    warehouseId As String _
) As Address
'Usage
Dim instance As IndiaTaxDatabaseAccessor
Dim warehouseId As String
Dim returnValue As Address

returnValue = instance.GetWarehouseAddressIndia(warehouseId)
```

``` csharp
public Address GetWarehouseAddressIndia(
    string warehouseId
)
```

``` c++
public:
Address^ GetWarehouseAddressIndia(
    String^ warehouseId
)
```

#### Parameters

  - warehouseId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[IndiaTaxDatabaseAccessor Class](indiataxdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

