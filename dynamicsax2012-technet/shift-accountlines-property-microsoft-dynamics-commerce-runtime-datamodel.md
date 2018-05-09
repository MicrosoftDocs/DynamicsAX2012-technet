---
title: Shift.AccountLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AccountLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.AccountLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shift.accountlines(v=AX.60)
ms:contentKeyID: 62205170
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.AccountLines
dev_langs:
- CSharp
- C++
- VB
---

# AccountLines Property

Gets list of shift account lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AccountLines As IList(Of ShiftAccountLine)
    Get
    Set
'Usage
Dim instance As Shift
Dim value As IList(Of ShiftAccountLine)

value = instance.AccountLines

instance.AccountLines = value
```

``` csharp
[DataMemberAttribute]
public IList<ShiftAccountLine> AccountLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<ShiftAccountLine^>^ AccountLines {
    IList<ShiftAccountLine^>^ get ();
    void set (IList<ShiftAccountLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\))\<[ShiftAccountLine](shiftaccountline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/en-us/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

