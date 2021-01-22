---
title: Address.PhoneRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PhoneRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.PhoneRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.phonerecordid(v=AX.60)
ms:contentKeyID: 62210912
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.PhoneRecordId
dev_langs:
- CSharp
- C++
- VB
---

# PhoneRecordId Property

Gets or sets the phone record id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PHONERECORDID")> _
Public Property PhoneRecordId As Long
    Get
    Set
'Usage
Dim instance As Address
Dim value As Long

value = instance.PhoneRecordId

instance.PhoneRecordId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PHONERECORDID")]
public long PhoneRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PHONERECORDID")]
public:
property long long PhoneRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The phone record id.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

