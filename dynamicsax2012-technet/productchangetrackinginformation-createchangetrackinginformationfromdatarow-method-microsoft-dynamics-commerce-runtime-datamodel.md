---
title: ProductChangeTrackingInformation.CreateChangeTrackingInformationFromDataRow Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CreateChangeTrackingInformationFromDataRow Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingInformation.CreateChangeTrackingInformationFromDataRow(Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRow)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinginformation.createchangetrackinginformationfromdatarow(v=AX.60)
ms:contentKeyID: 65319154
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingInformation.CreateChangeTrackingInformationFromDataRow
dev_langs:
- CSharp
- C++
- VB
---

# CreateChangeTrackingInformationFromDataRow Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateChangeTrackingInformationFromDataRow ( _
    row As DataRow _
) As ProductChangeTrackingInformation
'Usage
Dim row As DataRow
Dim returnValue As ProductChangeTrackingInformation

returnValue = ProductChangeTrackingInformation.CreateChangeTrackingInformationFromDataRow(row)
```

``` csharp
public static ProductChangeTrackingInformation CreateChangeTrackingInformationFromDataRow(
    DataRow row
)
```

``` c++
public:
static ProductChangeTrackingInformation^ CreateChangeTrackingInformationFromDataRow(
    DataRow^ row
)
```

#### Parameters

  - row  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRow](datarow-class-microsoft-dynamics-commerce-runtime-data-types.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingInformation](productchangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductChangeTrackingInformation Class](productchangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

