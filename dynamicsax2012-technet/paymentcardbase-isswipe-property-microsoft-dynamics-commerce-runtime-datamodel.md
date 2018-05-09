---
title: PaymentCardBase.IsSwipe Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsSwipe Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.IsSwipe
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcardbase.isswipe(v=AX.60)
ms:contentKeyID: 65318491
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.IsSwipe
dev_langs:
- CSharp
- C++
- VB
---

# IsSwipe Property

Gets or sets a value indicating whether IsSwipe is true or false.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Overridable Property IsSwipe As Boolean
    Get
    Set
'Usage
Dim instance As PaymentCardBase
Dim value As Boolean

value = instance.IsSwipe

instance.IsSwipe = value
```

``` csharp
[DataMemberAttribute]
public virtual bool IsSwipe { get; set; }
```

``` c++
[DataMemberAttribute]
public:
virtual property bool IsSwipe {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if this instance is swipe; otherwise, false.  

## See Also

#### Reference

[PaymentCardBase Class](paymentcardbase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

