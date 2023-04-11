---
title: ContactInfo.AddressType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddressType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.AddressType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.contactinfo.addresstype(v=AX.60)
ms:contentKeyID: 62204354
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfo.AddressType
dev_langs:
- CSharp
- C++
- VB
---

# AddressType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("METHODYTPE")> _
Public Property AddressType As ContactInfoType
    Get
    Set
'Usage
Dim instance As ContactInfo
Dim value As ContactInfoType

value = instance.AddressType

instance.AddressType = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("METHODYTPE")]
public ContactInfoType AddressType { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"METHODYTPE")]
public:
property ContactInfoType AddressType {
    ContactInfoType get ();
    void set (ContactInfoType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ContactInfoType](contactinfotype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of the address.  

## See Also

#### Reference

[ContactInfo Class](contactinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

