---
title: DeliveryOption.Description Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Description Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption.Description
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deliveryoption.description(v=AX.60)
ms:contentKeyID: 49855538
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryOption.Description
dev_langs:
- CSharp
- C++
- VB
---

# Description Property

Gets the description.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TXT")> _
Public Property Description As String
    Get
    Friend Set
'Usage
Dim instance As DeliveryOption
Dim value As String

value = instance.Description
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TXT")]
public string Description { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TXT")]
public:
property String^ Description {
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

