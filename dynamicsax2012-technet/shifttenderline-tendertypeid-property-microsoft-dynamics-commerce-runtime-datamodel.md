---
title: ShiftTenderLine.TenderTypeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderTypeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.TenderTypeId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.tendertypeid(v=AX.60)
ms:contentKeyID: 62213582
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.TenderTypeId
dev_langs:
- CSharp
- C++
- VB
---

# TenderTypeId Property

Gets or sets tender type identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TENDERTYPEID")> _
Public Property TenderTypeId As String
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As String

value = instance.TenderTypeId

instance.TenderTypeId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TENDERTYPEID")]
public string TenderTypeId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TENDERTYPEID")]
public:
property String^ TenderTypeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

