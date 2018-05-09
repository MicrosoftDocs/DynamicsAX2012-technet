---
title: IDimensionV1.GetDimensions Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetDimensions Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDimensionV1.GetDimensions(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.idimensionv1.getdimensions(v=AX.60)
ms:contentKeyID: 47344171
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDimensionV1.GetDimensions
dev_langs:
- CSharp
- C++
- VB
---

# GetDimensions Method

Gets all the variants and their dimensions for a given item ID.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetDimensions ( _
    itemId As String _
) As DataTable
'Usage
Dim instance As IDimensionV1
Dim itemId As String
Dim returnValue As DataTable

returnValue = instance.GetDimensions(itemId)
```

``` csharp
DataTable GetDimensions(
    string itemId
)
```

``` c++
DataTable^ GetDimensions(
    String^ itemId
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Data.DataTable](https://technet.microsoft.com/en-us/library/9186hy08\(v=ax.60\))  
A DataTable table that contains the following columns: "VariantId", "ColorId", "Color", "SizeId", "Size", "StyleId", "Style".  

## See Also

#### Reference

[IDimensionV1 Interface](idimensionv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

