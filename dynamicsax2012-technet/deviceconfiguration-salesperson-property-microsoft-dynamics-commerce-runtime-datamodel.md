---
title: DeviceConfiguration.SalesPerson Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesPerson Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.SalesPerson
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.salesperson(v=AX.60)
ms:contentKeyID: 62202057
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.SalesPerson
dev_langs:
- CSharp
- C++
- VB
---

# SalesPerson Property

Gets or sets the add sales person reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESPERSON")> _
Public Property SalesPerson As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.SalesPerson

instance.SalesPerson = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESPERSON")]
public string SalesPerson { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESPERSON")]
public:
property String^ SalesPerson {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The string containing the add sales person reason code.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

