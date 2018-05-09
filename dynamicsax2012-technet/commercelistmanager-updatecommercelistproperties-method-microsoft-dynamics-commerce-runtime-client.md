---
title: CommerceListManager.UpdateCommerceListProperties Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UpdateCommerceListProperties Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.UpdateCommerceListProperties(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.commercelistmanager.updatecommercelistproperties(v=AX.60)
ms:contentKeyID: 62211123
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.UpdateCommerceListProperties
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCommerceListProperties Method

Update the commerce list.

This currently applies to the update of a commerce list entity on the online channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function UpdateCommerceListProperties ( _
    commerceList As CommerceList _
) As CommerceList
'Usage
Dim instance As CommerceListManager
Dim commerceList As CommerceList
Dim returnValue As CommerceList

returnValue = instance.UpdateCommerceListProperties(commerceList)
```

``` csharp
public CommerceList UpdateCommerceListProperties(
    CommerceList commerceList
)
```

``` c++
public:
CommerceList^ UpdateCommerceListProperties(
    CommerceList^ commerceList
)
```

#### Parameters

  - commerceList  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The updated commerce list.  

## See Also

#### Reference

[CommerceListManager Class](commercelistmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

