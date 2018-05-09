---
title: ReasonCodeSpecific.SequenceNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SequenceNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.SequenceNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodespecific.sequencenumber(v=AX.60)
ms:contentKeyID: 62204183
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.SequenceNumber
dev_langs:
- CSharp
- C++
- VB
---

# SequenceNumber Property

Gets or sets the value of the sequence number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SEQUENCE")> _
Public Property SequenceNumber As Integer
    Get
    Set
'Usage
Dim instance As ReasonCodeSpecific
Dim value As Integer

value = instance.SequenceNumber

instance.SequenceNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SEQUENCE")]
public int SequenceNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SEQUENCE")]
public:
property int SequenceNumber {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
The sequence number value.  

## See Also

#### Reference

[ReasonCodeSpecific Class](reasoncodespecific-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

