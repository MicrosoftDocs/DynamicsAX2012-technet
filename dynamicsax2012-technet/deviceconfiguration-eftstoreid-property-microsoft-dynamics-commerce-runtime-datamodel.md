---
title: DeviceConfiguration.EFTStoreId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EFTStoreId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.EFTStoreId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.eftstoreid(v=AX.60)
ms:contentKeyID: 62211232
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.EFTStoreId
dev_langs:
- CSharp
- C++
- VB
---

# EFTStoreId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the EFT store id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EFTSTORERECID")> _
Public Property EFTStoreId As Long
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Long

value = instance.EFTStoreId

instance.EFTStoreId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EFTSTORERECID")]
public long EFTStoreId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EFTSTORERECID")]
public:
property long long EFTStoreId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The store id value.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

