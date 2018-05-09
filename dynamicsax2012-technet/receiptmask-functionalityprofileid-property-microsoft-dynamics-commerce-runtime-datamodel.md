---
title: ReceiptMask.FunctionalityProfileId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FunctionalityProfileId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptMask.FunctionalityProfileId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.receiptmask.functionalityprofileid(v=AX.60)
ms:contentKeyID: 62214766
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptMask.FunctionalityProfileId
dev_langs:
- CSharp
- C++
- VB
---

# FunctionalityProfileId Property

Gets the identifier of the functionality profile.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FUNCPROFILEID")> _
<DataMemberAttribute> _
Public Property FunctionalityProfileId As String
    Get
    Friend Set
'Usage
Dim instance As ReceiptMask
Dim value As String

value = instance.FunctionalityProfileId
```

``` csharp
[ColumnAttribute("FUNCPROFILEID")]
[DataMemberAttribute]
public string FunctionalityProfileId { get; internal set; }
```

``` c++
[ColumnAttribute(L"FUNCPROFILEID")]
[DataMemberAttribute]
public:
property String^ FunctionalityProfileId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ReceiptMask Class](receiptmask-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

