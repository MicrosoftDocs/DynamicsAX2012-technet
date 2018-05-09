---
title: ReasonCode.ReasonSubCodes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReasonSubCodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.ReasonSubCodes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.reasonsubcodes(v=AX.60)
ms:contentKeyID: 62210163
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.ReasonSubCodes
dev_langs:
- CSharp
- C++
- VB
---

# ReasonSubCodes Property

Gets the reason sub codes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReasonSubCodes As ICollection(Of ReasonSubCode)
    Get
    Private Set
'Usage
Dim instance As ReasonCode
Dim value As ICollection(Of ReasonSubCode)

value = instance.ReasonSubCodes
```

``` csharp
[DataMemberAttribute]
public ICollection<ReasonSubCode> ReasonSubCodes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ReasonSubCode^>^ ReasonSubCodes {
    ICollection<ReasonSubCode^>^ get ();
    private: void set (ICollection<ReasonSubCode^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[ReasonSubCode](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The reason sub codes.  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

