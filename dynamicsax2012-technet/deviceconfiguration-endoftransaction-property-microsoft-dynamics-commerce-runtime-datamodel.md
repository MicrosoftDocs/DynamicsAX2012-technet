---
title: DeviceConfiguration.EndOfTransaction Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EndOfTransaction Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.EndOfTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.endoftransaction(v=AX.60)
ms:contentKeyID: 62207733
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.EndOfTransaction
dev_langs:
- CSharp
- C++
- VB
---

# EndOfTransaction Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the end of transaction infocode value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ENDOFTRANSACTION")> _
<DataMemberAttribute> _
Public Property EndOfTransaction As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.EndOfTransaction

instance.EndOfTransaction = value
```

``` csharp
[ColumnAttribute("ENDOFTRANSACTION")]
[DataMemberAttribute]
public string EndOfTransaction { get; set; }
```

``` c++
[ColumnAttribute(L"ENDOFTRANSACTION")]
[DataMemberAttribute]
public:
property String^ EndOfTransaction {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing end of transaction infocode.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

