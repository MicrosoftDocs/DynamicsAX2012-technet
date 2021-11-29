---
title: GetButtonGridsByIdsCriteria.ButtonGridIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ButtonGridIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.GetButtonGridsByIdsCriteria.ButtonGridIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.getbuttongridsbyidscriteria.buttongridids(v=AX.60)
ms:contentKeyID: 62209844
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.GetButtonGridsByIdsCriteria.ButtonGridIds
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGridIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a collection button grid identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ButtonGridIds As IEnumerable(Of String)
    Get
    Set
'Usage
Dim instance As GetButtonGridsByIdsCriteria
Dim value As IEnumerable(Of String)

value = instance.ButtonGridIds

instance.ButtonGridIds = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> ButtonGridIds { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ ButtonGridIds {
    IEnumerable<String^>^ get ();
    void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetButtonGridsByIdsCriteria Class](getbuttongridsbyidscriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

