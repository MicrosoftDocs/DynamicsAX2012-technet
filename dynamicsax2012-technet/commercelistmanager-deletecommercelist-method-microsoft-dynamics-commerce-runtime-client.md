---
title: CommerceListManager.DeleteCommerceList Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: DeleteCommerceList Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.DeleteCommerceList(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.commercelistmanager.deletecommercelist(v=AX.60)
ms:contentKeyID: 62212286
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.DeleteCommerceList
dev_langs:
- CSharp
- C++
- VB
---

# DeleteCommerceList Method

Delete the commerce list.

This method deletes an entire commerce list entity. This capability currently only applies to the online channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub DeleteCommerceList ( _
    commerceListId As String _
)
'Usage
Dim instance As CommerceListManager
Dim commerceListId As String

instance.DeleteCommerceList(commerceListId)
```

``` csharp
public void DeleteCommerceList(
    string commerceListId
)
```

``` c++
public:
void DeleteCommerceList(
    String^ commerceListId
)
```

#### Parameters

  - commerceListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CommerceListManager Class](commercelistmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

