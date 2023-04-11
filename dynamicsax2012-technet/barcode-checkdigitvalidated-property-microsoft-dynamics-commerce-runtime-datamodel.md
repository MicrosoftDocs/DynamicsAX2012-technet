---
title: Barcode.CheckDigitValidated Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CheckDigitValidated Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.CheckDigitValidated
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.checkdigitvalidated(v=AX.60)
ms:contentKeyID: 62209533
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.CheckDigitValidated
dev_langs:
- CSharp
- C++
- VB
---

# CheckDigitValidated Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CheckDigitValidated As Boolean
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As Boolean

value = instance.CheckDigitValidated

instance.CheckDigitValidated = value
```

``` csharp
[DataMemberAttribute]
public bool CheckDigitValidated { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool CheckDigitValidated {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

