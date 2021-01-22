---
title: CommerceListManager.UpdateCommerceListLines Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UpdateCommerceListLines Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.UpdateCommerceListLines(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.commercelistmanager.updatecommercelistlines(v=AX.60)
ms:contentKeyID: 65319679
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.UpdateCommerceListLines
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCommerceListLines Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function UpdateCommerceListLines ( _
    commerceListLines As IEnumerable(Of CommerceListLine) _
) As CommerceList
'Usage
Dim instance As CommerceListManager
Dim commerceListLines As IEnumerable(Of CommerceListLine)
Dim returnValue As CommerceList

returnValue = instance.UpdateCommerceListLines(commerceListLines)
```

``` csharp
public CommerceList UpdateCommerceListLines(
    IEnumerable<CommerceListLine> commerceListLines
)
```

``` c++
public:
CommerceList^ UpdateCommerceListLines(
    IEnumerable<CommerceListLine^>^ commerceListLines
)
```

#### Parameters

  - commerceListLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CommerceListLine](commercelistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CommerceListManager Class](commercelistmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

