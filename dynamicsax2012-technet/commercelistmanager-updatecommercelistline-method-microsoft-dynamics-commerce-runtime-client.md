---
title: CommerceListManager.UpdateCommerceListLine Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UpdateCommerceListLine Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.UpdateCommerceListLine(Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.commercelistmanager.updatecommercelistline(v=AX.60)
ms:contentKeyID: 62214627
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.UpdateCommerceListLine
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCommerceListLine Method

Update the commerce list line.

This currently applies to the update of a commerce list line entity on the online channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function UpdateCommerceListLine ( _
    commerceListLine As CommerceListLine _
) As CommerceListLine
'Usage
Dim instance As CommerceListManager
Dim commerceListLine As CommerceListLine
Dim returnValue As CommerceListLine

returnValue = instance.UpdateCommerceListLine(commerceListLine)
```

``` csharp
public CommerceListLine UpdateCommerceListLine(
    CommerceListLine commerceListLine
)
```

``` c++
public:
CommerceListLine^ UpdateCommerceListLine(
    CommerceListLine^ commerceListLine
)
```

#### Parameters

  - commerceListLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine](commercelistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine](commercelistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The updated commerce list line.  

## See Also

#### Reference

[CommerceListManager Class](commercelistmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

