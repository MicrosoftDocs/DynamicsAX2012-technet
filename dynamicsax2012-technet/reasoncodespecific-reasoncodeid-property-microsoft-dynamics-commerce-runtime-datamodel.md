---
title: ReasonCodeSpecific.ReasonCodeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReasonCodeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.ReasonCodeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodespecific.reasoncodeid(v=AX.60)
ms:contentKeyID: 62210522
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSpecific.ReasonCodeId
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the reason code id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INFOCODEID")> _
<DataMemberAttribute> _
Public Property ReasonCodeId As String
    Get
    Set
'Usage
Dim instance As ReasonCodeSpecific
Dim value As String

value = instance.ReasonCodeId

instance.ReasonCodeId = value
```

``` csharp
[ColumnAttribute("INFOCODEID")]
[DataMemberAttribute]
public string ReasonCodeId { get; set; }
```

``` c++
[ColumnAttribute(L"INFOCODEID")]
[DataMemberAttribute]
public:
property String^ ReasonCodeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The reason code id.  

## See Also

#### Reference

[ReasonCodeSpecific Class](reasoncodespecific-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

