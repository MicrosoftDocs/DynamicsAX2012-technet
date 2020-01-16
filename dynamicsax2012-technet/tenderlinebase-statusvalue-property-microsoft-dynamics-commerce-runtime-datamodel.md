---
title: TenderLineBase.StatusValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StatusValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.StatusValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.statusvalue(v=AX.60)
ms:contentKeyID: 62204251
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.StatusValue
dev_langs:
- CSharp
- C++
- VB
---

# StatusValue Property

Gets or sets the value of the Status enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StatusValue As Integer
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As Integer

value = instance.StatusValue

instance.StatusValue = value
```

``` csharp
[DataMemberAttribute]
public int StatusValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int StatusValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

