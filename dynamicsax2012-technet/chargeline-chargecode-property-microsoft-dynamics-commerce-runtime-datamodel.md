---
title: ChargeLine.ChargeCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.ChargeCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeline.chargecode(v=AX.60)
ms:contentKeyID: 49844592
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.ChargeCode
dev_langs:
- CSharp
- C++
- VB
---

# ChargeCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the charge code for this charge line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MARKUPCODE")> _
Public Property ChargeCode As String
    Get
    Set
'Usage
Dim instance As ChargeLine
Dim value As String

value = instance.ChargeCode

instance.ChargeCode = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MARKUPCODE")]
public string ChargeCode { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MARKUPCODE")]
public:
property String^ ChargeCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The charge code.  

## See Also

#### Reference

[ChargeLine Class](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

