---
title: DeviceConfiguration.EFTTerminalId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EFTTerminalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.EFTTerminalId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.eftterminalid(v=AX.60)
ms:contentKeyID: 62211894
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.EFTTerminalId
dev_langs:
- CSharp
- C++
- VB
---

# EFTTerminalId Property

Gets or sets the EFT terminal id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EFTTERMINALID")> _
Public Property EFTTerminalId As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.EFTTerminalId

instance.EFTTerminalId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EFTTERMINALID")]
public string EFTTerminalId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EFTTERMINALID")]
public:
property String^ EFTTerminalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The string containing the EFT terminal id.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

