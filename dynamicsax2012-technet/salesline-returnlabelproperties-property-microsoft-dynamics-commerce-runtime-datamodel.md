---
title: SalesLine.ReturnLabelProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnLabelProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ReturnLabelProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.returnlabelproperties(v=AX.60)
ms:contentKeyID: 65320376
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.ReturnLabelProperties
dev_langs:
- CSharp
- C++
- VB
---

# ReturnLabelProperties Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<IgnoreDataMemberAttribute> _
Public Property ReturnLabelProperties As ReturnLabelContent
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As ReturnLabelContent

value = instance.ReturnLabelProperties

instance.ReturnLabelProperties = value
```

``` csharp
[DataMemberAttribute]
[IgnoreDataMemberAttribute]
public ReturnLabelContent ReturnLabelProperties { get; set; }
```

``` c++
[DataMemberAttribute]
[IgnoreDataMemberAttribute]
public:
property ReturnLabelContent^ ReturnLabelProperties {
    ReturnLabelContent^ get ();
    void set (ReturnLabelContent^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReturnLabelContent](returnlabelcontent-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

