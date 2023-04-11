---
title: CommerceListManager.GetCommerceList Method (String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCommerceList Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.GetCommerceList(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.commercelistmanager.getcommercelist(v=AX.60)
ms:contentKeyID: 65319617
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCommerceList Method (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCommerceList ( _
    commerceListId As String _
) As CommerceList
'Usage
Dim instance As CommerceListManager
Dim commerceListId As String
Dim returnValue As CommerceList

returnValue = instance.GetCommerceList(commerceListId)
```

``` csharp
public CommerceList GetCommerceList(
    string commerceListId
)
```

``` c++
public:
CommerceList^ GetCommerceList(
    String^ commerceListId
)
```

#### Parameters

  - commerceListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CommerceListManager Class](commercelistmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetCommerceList Overload](commercelistmanager-getcommercelist-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

