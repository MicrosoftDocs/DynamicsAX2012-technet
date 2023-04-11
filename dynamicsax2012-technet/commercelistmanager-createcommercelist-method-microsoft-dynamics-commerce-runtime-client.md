---
title: CommerceListManager.CreateCommerceList Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: CreateCommerceList Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.CreateCommerceList(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.commercelistmanager.createcommercelist(v=AX.60)
ms:contentKeyID: 62211690
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.CreateCommerceList
dev_langs:
- CSharp
- C++
- VB
---

# CreateCommerceList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Create the commerce list.

This currently applies to the creation of a commerce list entity on the online channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function CreateCommerceList ( _
    commerceList As CommerceList _
) As CommerceList
'Usage
Dim instance As CommerceListManager
Dim commerceList As CommerceList
Dim returnValue As CommerceList

returnValue = instance.CreateCommerceList(commerceList)
```

``` csharp
public CommerceList CreateCommerceList(
    CommerceList commerceList
)
```

``` c++
public:
CommerceList^ CreateCommerceList(
    CommerceList^ commerceList
)
```

#### Parameters

  - commerceList  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The created commerce list.  

## See Also

#### Reference

[CommerceListManager Class](commercelistmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

