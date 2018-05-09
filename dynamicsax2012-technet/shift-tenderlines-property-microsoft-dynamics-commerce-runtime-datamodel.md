---
title: Shift.TenderLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.TenderLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shift.tenderlines(v=AX.60)
ms:contentKeyID: 62210092
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.TenderLines
dev_langs:
- CSharp
- C++
- VB
---

# TenderLines Property

Gets list of shift tender lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderLines As IList(Of ShiftTenderLine)
    Get
    Set
'Usage
Dim instance As Shift
Dim value As IList(Of ShiftTenderLine)

value = instance.TenderLines

instance.TenderLines = value
```

``` csharp
[DataMemberAttribute]
public IList<ShiftTenderLine> TenderLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<ShiftTenderLine^>^ TenderLines {
    IList<ShiftTenderLine^>^ get ();
    void set (IList<ShiftTenderLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[ShiftTenderLine](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

