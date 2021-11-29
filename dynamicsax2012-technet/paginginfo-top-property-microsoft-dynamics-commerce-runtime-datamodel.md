---
title: PagingInfo.Top Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Top Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.Top
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paginginfo.top(v=AX.60)
ms:contentKeyID: 65315762
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.Top
dev_langs:
- CSharp
- C++
- VB
---

# Top Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the top number of rows.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Top As Integer
    Get
    Set
'Usage
Dim instance As PagingInfo
Dim value As Integer

value = instance.Top

instance.Top = value
```

``` csharp
[DataMemberAttribute]
public int Top { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int Top {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The top number of rows.  

## See Also

#### Reference

[PagingInfo Class](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

