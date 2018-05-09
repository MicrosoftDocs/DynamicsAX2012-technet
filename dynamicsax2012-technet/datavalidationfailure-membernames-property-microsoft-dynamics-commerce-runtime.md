---
title: DataValidationFailure.MemberNames Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: MemberNames Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure.MemberNames
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datavalidationfailure.membernames(v=AX.60)
ms:contentKeyID: 49838603
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataValidationFailure.MemberNames
dev_langs:
- CSharp
- C++
- VB
---

# MemberNames Property

Gets the member name which caused the validation error.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property MemberNames As ICollection(Of String)
    Get
    Private Set
'Usage
Dim instance As DataValidationFailure
Dim value As ICollection(Of String)

value = instance.MemberNames
```

``` csharp
public ICollection<string> MemberNames { get; private set; }
```

``` c++
public:
property ICollection<String^>^ MemberNames {
    ICollection<String^>^ get ();
    private: void set (ICollection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
Returns [Collection\<T\>](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[DataValidationFailure Class](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

