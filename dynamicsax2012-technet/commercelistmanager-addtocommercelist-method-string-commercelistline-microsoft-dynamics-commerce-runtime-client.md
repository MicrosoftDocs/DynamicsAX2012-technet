---
title: CommerceListManager.AddToCommerceList Method (String, CommerceListLine) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: AddToCommerceList Method (String, CommerceListLine)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.AddToCommerceList(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.commercelistmanager.addtocommercelist(v=AX.60)
ms:contentKeyID: 62207718
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AddToCommerceList Method (String, CommerceListLine)

Create the commerce list line.

This currently applies to the addition of an item to the commerce list on the online channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function AddToCommerceList ( _
    commerceListId As String, _
    commerceListLine As CommerceListLine _
) As CommerceListLine
'Usage
Dim instance As CommerceListManager
Dim commerceListId As String
Dim commerceListLine As CommerceListLine
Dim returnValue As CommerceListLine

returnValue = instance.AddToCommerceList(commerceListId, _
    commerceListLine)
```

``` csharp
public CommerceListLine AddToCommerceList(
    string commerceListId,
    CommerceListLine commerceListLine
)
```

``` c++
public:
CommerceListLine^ AddToCommerceList(
    String^ commerceListId, 
    CommerceListLine^ commerceListLine
)
```

#### Parameters

  - commerceListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - commerceListLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine](commercelistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine](commercelistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The created commerce list.  

## See Also

#### Reference

[CommerceListManager Class](commercelistmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[AddToCommerceList Overload](commercelistmanager-addtocommercelist-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

