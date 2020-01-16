---
title: DeviceConfiguration.OfflineTransactionUploadInterval Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OfflineTransactionUploadInterval Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.OfflineTransactionUploadInterval
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.offlinetransactionuploadinterval(v=AX.60)
ms:contentKeyID: 65321634
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.OfflineTransactionUploadInterval
dev_langs:
- CSharp
- C++
- VB
---

# OfflineTransactionUploadInterval Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TRXUPLOADINTERVAL")> _
Public Property OfflineTransactionUploadInterval As Integer
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Integer

value = instance.OfflineTransactionUploadInterval

instance.OfflineTransactionUploadInterval = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TRXUPLOADINTERVAL")]
public int OfflineTransactionUploadInterval { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TRXUPLOADINTERVAL")]
public:
property int OfflineTransactionUploadInterval {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

