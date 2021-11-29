---
title: ProductIdentity.OfflineImage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OfflineImage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.OfflineImage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productidentity.offlineimage(v=AX.60)
ms:contentKeyID: 65320154
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductIdentity.OfflineImage
dev_langs:
- CSharp
- C++
- VB
---

# OfflineImage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OFFLINEIMAGE")> _
Public Property OfflineImage As String
    Get
    Friend Set
'Usage
Dim instance As ProductIdentity
Dim value As String

value = instance.OfflineImage
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OFFLINEIMAGE")]
public string OfflineImage { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OFFLINEIMAGE")]
public:
property String^ OfflineImage {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ProductIdentity Class](productidentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

