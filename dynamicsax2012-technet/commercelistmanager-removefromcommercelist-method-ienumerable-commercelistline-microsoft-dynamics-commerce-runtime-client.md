---
title: CommerceListManager.RemoveFromCommerceList Method (IEnumerable(CommerceListLine)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: RemoveFromCommerceList Method (IEnumerable(CommerceListLine))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.RemoveFromCommerceList(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.commercelistmanager.removefromcommercelist(v=AX.60)
ms:contentKeyID: 65321041
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RemoveFromCommerceList Method (IEnumerable(CommerceListLine))

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub RemoveFromCommerceList ( _
    lines As IEnumerable(Of CommerceListLine) _
)
'Usage
Dim instance As CommerceListManager
Dim lines As IEnumerable(Of CommerceListLine)

instance.RemoveFromCommerceList(lines)
```

``` csharp
public void RemoveFromCommerceList(
    IEnumerable<CommerceListLine> lines
)
```

``` c++
public:
void RemoveFromCommerceList(
    IEnumerable<CommerceListLine^>^ lines
)
```

#### Parameters

  - lines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CommerceListLine](commercelistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CommerceListManager Class](commercelistmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[RemoveFromCommerceList Overload](commercelistmanager-removefromcommercelist-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

