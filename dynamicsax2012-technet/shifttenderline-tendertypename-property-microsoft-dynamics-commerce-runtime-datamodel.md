---
title: ShiftTenderLine.TenderTypeName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderTypeName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.TenderTypeName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.tendertypename(v=AX.60)
ms:contentKeyID: 62210265
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.TenderTypeName
dev_langs:
- CSharp
- C++
- VB
---

# TenderTypeName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tender type name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TENDERTYPENAME")> _
Public Property TenderTypeName As String
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As String

value = instance.TenderTypeName

instance.TenderTypeName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TENDERTYPENAME")]
public string TenderTypeName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TENDERTYPENAME")]
public:
property String^ TenderTypeName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

