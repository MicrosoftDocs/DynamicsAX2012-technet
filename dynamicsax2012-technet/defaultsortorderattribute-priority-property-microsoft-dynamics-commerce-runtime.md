---
title: DefaultSortOrderAttribute.Priority Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Priority Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DefaultSortOrderAttribute.Priority
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.defaultsortorderattribute.priority(v=AX.60)
ms:contentKeyID: 62208720
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DefaultSortOrderAttribute.Priority
dev_langs:
- CSharp
- C++
- VB
---

# Priority Property

Gets or sets the sort priority used by multi-column sorting.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Priority As Integer
    Get
    Set
'Usage
Dim instance As DefaultSortOrderAttribute
Dim value As Integer

value = instance.Priority

instance.Priority = value
```

``` csharp
public int Priority { get; set; }
```

``` c++
public:
property int Priority {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[DefaultSortOrderAttribute Class](defaultsortorderattribute-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

