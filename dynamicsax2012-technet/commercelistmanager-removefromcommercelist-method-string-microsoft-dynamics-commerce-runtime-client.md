---
title: CommerceListManager.RemoveFromCommerceList Method (String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: RemoveFromCommerceList Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.RemoveFromCommerceList(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.commercelistmanager.removefromcommercelist(v=AX.60)
ms:contentKeyID: 62211456
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RemoveFromCommerceList Method (String)

Delete the commerce list line.

This currently only applies to the online channel. It is used to delete a specific item from a commerce list.

This could be used on other channels if we want to enable deletion in other contexts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub RemoveFromCommerceList ( _
    lineId As String _
)
'Usage
Dim instance As CommerceListManager
Dim lineId As String

instance.RemoveFromCommerceList(lineId)
```

``` csharp
public void RemoveFromCommerceList(
    string lineId
)
```

``` c++
public:
void RemoveFromCommerceList(
    String^ lineId
)
```

#### Parameters

  - lineId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CommerceListManager Class](commercelistmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[RemoveFromCommerceList Overload](commercelistmanager-removefromcommercelist-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

