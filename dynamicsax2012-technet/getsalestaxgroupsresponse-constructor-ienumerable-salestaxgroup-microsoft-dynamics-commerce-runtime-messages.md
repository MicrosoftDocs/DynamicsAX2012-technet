---
title: GetSalesTaxGroupsResponse Constructor (IEnumerable(SalesTaxGroup)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetSalesTaxGroupsResponse Constructor (IEnumerable(SalesTaxGroup))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetSalesTaxGroupsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTaxGroup})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getsalestaxgroupsresponse.getsalestaxgroupsresponse(v=AX.60)
ms:contentKeyID: 62214533
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetSalesTaxGroupsResponse Constructor (IEnumerable(SalesTaxGroup))

Initializes a new instance of the [GetSalesTaxGroupsResponse](getsalestaxgroupsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesTaxGroups As IEnumerable(Of SalesTaxGroup) _
)
'Usage
Dim salesTaxGroups As IEnumerable(Of SalesTaxGroup)

Dim instance As New GetSalesTaxGroupsResponse(salesTaxGroups)
```

``` csharp
public GetSalesTaxGroupsResponse(
    IEnumerable<SalesTaxGroup> salesTaxGroups
)
```

``` c++
public:
GetSalesTaxGroupsResponse(
    IEnumerable<SalesTaxGroup^>^ salesTaxGroups
)
```

#### Parameters

  - salesTaxGroups  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[SalesTaxGroup](salestaxgroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetSalesTaxGroupsResponse Class](getsalestaxgroupsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetSalesTaxGroupsResponse Overload](getsalestaxgroupsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

