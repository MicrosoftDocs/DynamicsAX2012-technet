---
title: ChargeConfiguration.ChargeCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ChargeCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfiguration.chargecode(v=AX.60)
ms:contentKeyID: 49837481
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ChargeCode
dev_langs:
- CSharp
- C++
- VB
---

# ChargeCode Property

Gets or sets the charge code identifier on the configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MARKUPCODE")> _
<DataMemberAttribute> _
Public Property ChargeCode As String
    Get
    Set
'Usage
Dim instance As ChargeConfiguration
Dim value As String

value = instance.ChargeCode

instance.ChargeCode = value
```

``` csharp
[ColumnAttribute("MARKUPCODE")]
[DataMemberAttribute]
public string ChargeCode { get; set; }
```

``` c++
[ColumnAttribute(L"MARKUPCODE")]
[DataMemberAttribute]
public:
property String^ ChargeCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChargeConfiguration Class](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

