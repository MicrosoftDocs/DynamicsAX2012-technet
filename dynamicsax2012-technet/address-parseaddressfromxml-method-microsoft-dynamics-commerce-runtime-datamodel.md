---
title: Address.ParseAddressFromXml Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ParseAddressFromXml Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.ParseAddressFromXml(System.Xml.Linq.XElement)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.parseaddressfromxml(v=AX.60)
ms:contentKeyID: 62202030
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.ParseAddressFromXml
dev_langs:
- CSharp
- C++
- VB
---

# ParseAddressFromXml Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Parse address from a SalesOrder or SaleLine XML node.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ParseAddressFromXml ( _
    address As XElement _
) As Address
'Usage
Dim address As XElement
Dim returnValue As Address

returnValue = Address.ParseAddressFromXml(address)
```

``` csharp
public static Address ParseAddressFromXml(
    XElement address
)
```

``` c++
public:
static Address^ ParseAddressFromXml(
    XElement^ address
)
```

#### Parameters

  - address  
    Type: [System.Xml.Linq.XElement](https://technet.microsoft.com/library/bb340098\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The customer address.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

