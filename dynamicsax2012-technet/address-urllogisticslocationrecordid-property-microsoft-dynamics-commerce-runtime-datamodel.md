---
title: Address.UrlLogisticsLocationRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UrlLogisticsLocationRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.UrlLogisticsLocationRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.urllogisticslocationrecordid(v=AX.60)
ms:contentKeyID: 62212426
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.UrlLogisticsLocationRecordId
dev_langs:
- CSharp
- C++
- VB
---

# UrlLogisticsLocationRecordId Property

Gets or sets the URL logistics location record id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("URLLOCATIONRECORDID")> _
<ColumnAttribute("URLLOCATIONRECORDID")> _
<DataMemberAttribute> _
Public Property UrlLogisticsLocationRecordId As Long
    Get
    Set
'Usage
Dim instance As Address
Dim value As Long

value = instance.UrlLogisticsLocationRecordId

instance.UrlLogisticsLocationRecordId = value
```

``` csharp
[ReadOnlyAttribute("URLLOCATIONRECORDID")]
[ColumnAttribute("URLLOCATIONRECORDID")]
[DataMemberAttribute]
public long UrlLogisticsLocationRecordId { get; set; }
```

``` c++
[ReadOnlyAttribute(L"URLLOCATIONRECORDID")]
[ColumnAttribute(L"URLLOCATIONRECORDID")]
[DataMemberAttribute]
public:
property long long UrlLogisticsLocationRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The URL logistics location record id.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

