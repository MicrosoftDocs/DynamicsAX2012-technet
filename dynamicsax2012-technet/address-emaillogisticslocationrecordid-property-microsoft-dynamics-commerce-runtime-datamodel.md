---
title: Address.EmailLogisticsLocationRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmailLogisticsLocationRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.EmailLogisticsLocationRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.emaillogisticslocationrecordid(v=AX.60)
ms:contentKeyID: 62208336
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.EmailLogisticsLocationRecordId
dev_langs:
- CSharp
- C++
- VB
---

# EmailLogisticsLocationRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the email logistics location record id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EMAILLOCATIONRECORDID")> _
<ReadOnlyAttribute("EMAILLOCATIONRECORDID")> _
Public Property EmailLogisticsLocationRecordId As Long
    Get
    Set
'Usage
Dim instance As Address
Dim value As Long

value = instance.EmailLogisticsLocationRecordId

instance.EmailLogisticsLocationRecordId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EMAILLOCATIONRECORDID")]
[ReadOnlyAttribute("EMAILLOCATIONRECORDID")]
public long EmailLogisticsLocationRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EMAILLOCATIONRECORDID")]
[ReadOnlyAttribute(L"EMAILLOCATIONRECORDID")]
public:
property long long EmailLogisticsLocationRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The email logistics location record id.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

