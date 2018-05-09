---
title: TenderType.IsUndertenderAllowed Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsUndertenderAllowed Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.IsUndertenderAllowed
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.isundertenderallowed(v=AX.60)
ms:contentKeyID: 62213392
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.IsUndertenderAllowed
dev_langs:
- CSharp
- C++
- VB
---

# IsUndertenderAllowed Property

Gets or sets a value indicating whether undertendering is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ALLOWUNDERTENDER")> _
Public Property IsUndertenderAllowed As Boolean
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Boolean

value = instance.IsUndertenderAllowed

instance.IsUndertenderAllowed = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ALLOWUNDERTENDER")]
public bool IsUndertenderAllowed { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ALLOWUNDERTENDER")]
public:
property bool IsUndertenderAllowed {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
If true then undertender is allowed; otherwise, false.  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

