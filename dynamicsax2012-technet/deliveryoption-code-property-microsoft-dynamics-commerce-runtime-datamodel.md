---
title: DeliveryOption.Code Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Code Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption.Code
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deliveryoption.code(v=AX.60)
ms:contentKeyID: 49853276
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption.Code
dev_langs:
- CSharp
- C++
- VB
---

# Code Property

Gets the delivery code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CODE")> _
Public Property Code As String
    Get
    Friend Set
'Usage
Dim instance As DeliveryOption
Dim value As String

value = instance.Code
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CODE")]
public string Code { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CODE")]
public:
property String^ Code {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DeliveryOption Class](deliveryoption-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

