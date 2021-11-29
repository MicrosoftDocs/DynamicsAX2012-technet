---
title: Address.LogisticsLocationRoleRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LogisticsLocationRoleRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.LogisticsLocationRoleRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.logisticslocationrolerecordid(v=AX.60)
ms:contentKeyID: 62207978
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.LogisticsLocationRoleRecordId
dev_langs:
- CSharp
- C++
- VB
---

# LogisticsLocationRoleRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the logistics location role record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ReadOnlyAttribute("LOGISTICSLOCATIONROLERECID")> _
<ColumnAttribute("LOGISTICSLOCATIONROLERECID")> _
Public Property LogisticsLocationRoleRecordId As Long
    Get
    Set
'Usage
Dim instance As Address
Dim value As Long

value = instance.LogisticsLocationRoleRecordId

instance.LogisticsLocationRoleRecordId = value
```

``` csharp
[DataMemberAttribute]
[ReadOnlyAttribute("LOGISTICSLOCATIONROLERECID")]
[ColumnAttribute("LOGISTICSLOCATIONROLERECID")]
public long LogisticsLocationRoleRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
[ReadOnlyAttribute(L"LOGISTICSLOCATIONROLERECID")]
[ColumnAttribute(L"LOGISTICSLOCATIONROLERECID")]
public:
property long long LogisticsLocationRoleRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The logistics location role record identifier.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

