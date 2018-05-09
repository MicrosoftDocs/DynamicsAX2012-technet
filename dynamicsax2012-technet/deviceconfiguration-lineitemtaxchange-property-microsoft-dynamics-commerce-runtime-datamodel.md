---
title: DeviceConfiguration.LineItemTaxChange Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineItemTaxChange Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.LineItemTaxChange
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.lineitemtaxchange(v=AX.60)
ms:contentKeyID: 62212921
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.LineItemTaxChange
dev_langs:
- CSharp
- C++
- VB
---

# LineItemTaxChange Property

Gets or sets the line item tax change infocode value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LINEITEMTAXCHANGE")> _
Public Property LineItemTaxChange As String
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As String

value = instance.LineItemTaxChange

instance.LineItemTaxChange = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LINEITEMTAXCHANGE")]
public string LineItemTaxChange { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LINEITEMTAXCHANGE")]
public:
property String^ LineItemTaxChange {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The string containing line item tax change infocode.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

