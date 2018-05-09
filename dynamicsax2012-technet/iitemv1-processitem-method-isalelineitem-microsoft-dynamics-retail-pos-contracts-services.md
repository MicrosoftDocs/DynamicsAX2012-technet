---
title: IItemV1.ProcessItem Method (ISaleLineItem) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ProcessItem Method (ISaleLineItem)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IItemV1.ProcessItem(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iitemv1.processitem(v=AX.60)
ms:contentKeyID: 47344108
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProcessItem Method (ISaleLineItem)

This function is implemented by the item service. There are multiple functions called within The ProcessItem method.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ProcessItem ( _
    saleLineItem As ISaleLineItem _
)
'Usage
Dim instance As IItemV1
Dim saleLineItem As ISaleLineItem

instance.ProcessItem(saleLineItem)
```

``` csharp
void ProcessItem(
    ISaleLineItem saleLineItem
)
```

``` c++
void ProcessItem(
    ISaleLineItem^ saleLineItem
)
```

#### Parameters

  - saleLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[ProcessItem Overload](iitemv1-processitem-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

