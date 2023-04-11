---
title: ReasonCode.InputRequiredType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InputRequiredType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.InputRequiredType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncode.inputrequiredtype(v=AX.60)
ms:contentKeyID: 65316972
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode.InputRequiredType
dev_langs:
- CSharp
- C++
- VB
---

# InputRequiredType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property InputRequiredType As ReasonCodeInputRequiredType
    Get
    Set
'Usage
Dim instance As ReasonCode
Dim value As ReasonCodeInputRequiredType

value = instance.InputRequiredType

instance.InputRequiredType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public ReasonCodeInputRequiredType InputRequiredType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ReasonCodeInputRequiredType InputRequiredType {
    ReasonCodeInputRequiredType get ();
    void set (ReasonCodeInputRequiredType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeInputRequiredType](reasoncodeinputrequiredtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ReasonCode Class](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

