---
title: IItemV1.ProcessItem Method (ISaleLineItem, Boolean) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ProcessItem Method (ISaleLineItem, Boolean)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IItemV1.ProcessItem(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iitemv1.processitem(v=AX.60)
ms:contentKeyID: 47343956
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProcessItem Method (ISaleLineItem, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Invoked by item sale operation.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ProcessItem ( _
    saleLineItem As ISaleLineItem, _
    bypassSerialNumberEntry As Boolean _
)
'Usage
Dim instance As IItemV1
Dim saleLineItem As ISaleLineItem
Dim bypassSerialNumberEntry As Boolean

instance.ProcessItem(saleLineItem, bypassSerialNumberEntry)
```

``` csharp
void ProcessItem(
    ISaleLineItem saleLineItem,
    bool bypassSerialNumberEntry
)
```

``` c++
void ProcessItem(
    ISaleLineItem^ saleLineItem, 
    bool bypassSerialNumberEntry
)
```

#### Parameters

  - saleLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - bypassSerialNumberEntry  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[ProcessItem Overload](iitemv1-processitem-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

