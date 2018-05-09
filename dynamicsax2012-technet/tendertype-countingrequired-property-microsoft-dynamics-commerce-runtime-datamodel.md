---
title: TenderType.CountingRequired Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CountingRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.CountingRequired
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.countingrequired(v=AX.60)
ms:contentKeyID: 62202480
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.CountingRequired
dev_langs:
- CSharp
- C++
- VB
---

# CountingRequired Property

Gets or sets the counting required value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("COUNTINGREQUIRED")> _
Public Property CountingRequired As Integer
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Integer

value = instance.CountingRequired

instance.CountingRequired = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("COUNTINGREQUIRED")]
public int CountingRequired { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"COUNTINGREQUIRED")]
public:
property int CountingRequired {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

