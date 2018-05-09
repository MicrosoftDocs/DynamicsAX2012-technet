---
title: SalesTransaction.DiscountCodes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountCodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.DiscountCodes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.discountcodes(v=AX.60)
ms:contentKeyID: 49850215
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.DiscountCodes
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCodes Property

Gets or sets all the discount/promo codes active on this sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DiscountCodes As Collection(Of String)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Collection(Of String)

value = instance.DiscountCodes

instance.DiscountCodes = value
```

``` csharp
[DataMemberAttribute]
public Collection<string> DiscountCodes { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<String^>^ DiscountCodes {
    Collection<String^>^ get ();
    void set (Collection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
Returns [Collection\<T\>](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

