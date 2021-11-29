---
title: ProductProperty.FriendlyName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FriendlyName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.FriendlyName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.friendlyname(v=AX.60)
ms:contentKeyID: 65315969
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.FriendlyName
dev_langs:
- CSharp
- C++
- VB
---

# FriendlyName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FriendlyName As String
    Get
    Set
'Usage
Dim instance As ProductProperty
Dim value As String

value = instance.FriendlyName

instance.FriendlyName = value
```

``` csharp
[DataMemberAttribute]
public string FriendlyName { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ FriendlyName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

