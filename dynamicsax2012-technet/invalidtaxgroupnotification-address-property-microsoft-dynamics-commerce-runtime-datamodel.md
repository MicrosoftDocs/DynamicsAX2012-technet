---
title: InvalidTaxGroupNotification.Address Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Address Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.InvalidTaxGroupNotification.Address
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.invalidtaxgroupnotification.address(v=AX.60)
ms:contentKeyID: 65316263
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.InvalidTaxGroupNotification.Address
dev_langs:
- CSharp
- C++
- VB
---

# Address Property

Gets the unmatched address with sales tax group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Address As Address
    Get
    Private Set
'Usage
Dim instance As InvalidTaxGroupNotification
Dim value As Address

value = instance.Address
```

``` csharp
[DataMemberAttribute]
public Address Address { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ Address {
    Address^ get ();
    private: void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[InvalidTaxGroupNotification Class](invalidtaxgroupnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

