---
title: NewDataSet.Items Property  ()
TOCTitle: Items Property
ms:assetid: P:NewDataSet.Items
ms:mtpsurl: https://technet.microsoft.com/en-us/library/newdataset.items(v=AX.60)
ms:contentKeyID: 65316658
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- NewDataSet.Items
dev_langs:
- CSharp
- C++
- VB
---

# Items Property

**Namespace:**  [(Default Namespace)](default-namespace-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Property Items As ProductProperty()
    Get
    Set
'Usage
Dim instance As NewDataSet
Dim value As ProductProperty()

value = instance.Items

instance.Items = value
```

``` csharp
public ProductProperty[] Items { get; set; }
```

``` c++
public:
property array<ProductProperty^>^ Items {
    array<ProductProperty^>^ get ();
    void set (array<ProductProperty^>^ value);
}
```

#### Property Value

Type: [(Default Namespace).ProductProperty](productproperty-class.md)\[\]  

## See Also

#### Reference

[NewDataSet Class](newdataset-class.md)

[(Default Namespace) Namespace](default-namespace-namespace.md)

