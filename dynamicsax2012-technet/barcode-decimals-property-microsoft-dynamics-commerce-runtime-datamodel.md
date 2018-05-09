---
title: Barcode.Decimals Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Decimals Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.Decimals
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.decimals(v=AX.60)
ms:contentKeyID: 62211744
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.Decimals
dev_langs:
- CSharp
- C++
- VB
---

# Decimals Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Decimals As Integer
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As Integer

value = instance.Decimals

instance.Decimals = value
```

``` csharp
[DataMemberAttribute]
public int Decimals { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int Decimals {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

