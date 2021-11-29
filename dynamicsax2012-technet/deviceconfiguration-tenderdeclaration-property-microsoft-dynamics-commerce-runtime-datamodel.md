---
title: DeviceConfiguration.TenderDeclaration Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderDeclaration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.TenderDeclaration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.tenderdeclaration(v=AX.60)
ms:contentKeyID: 62214199
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.TenderDeclaration
dev_langs:
- CSharp
- C++
- VB
---

# TenderDeclaration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tender declaration reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TENDERDECLARATION")> _
Public Property TenderDeclaration As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.TenderDeclaration

instance.TenderDeclaration = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TENDERDECLARATION")]
public string TenderDeclaration { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TENDERDECLARATION")]
public:
property String^ TenderDeclaration {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string containing the tender declaration reason code.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

