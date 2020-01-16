---
title: HardwareProfile.LineDisplayBalanceText Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDisplayBalanceText Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayBalanceText
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.linedisplaybalancetext(v=AX.60)
ms:contentKeyID: 62209614
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.LineDisplayBalanceText
dev_langs:
- CSharp
- C++
- VB
---

# LineDisplayBalanceText Property

Gets or sets the balance text for display.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISPLAYBALANCETEXT")> _
Public Property LineDisplayBalanceText As String
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As String

value = instance.LineDisplayBalanceText

instance.LineDisplayBalanceText = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISPLAYBALANCETEXT")]
public string LineDisplayBalanceText { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISPLAYBALANCETEXT")]
public:
property String^ LineDisplayBalanceText {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The text value.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

