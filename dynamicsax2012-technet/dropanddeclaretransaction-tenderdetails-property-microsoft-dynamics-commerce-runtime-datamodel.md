---
title: DropAndDeclareTransaction.TenderDetails Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderDetails Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction.TenderDetails
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.dropanddeclaretransaction.tenderdetails(v=AX.60)
ms:contentKeyID: 62209565
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DropAndDeclareTransaction.TenderDetails
dev_langs:
- CSharp
- C++
- VB
---

# TenderDetails Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tender lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TenderDetails As ICollection(Of TenderDetail)
    Get
    Set
'Usage
Dim instance As DropAndDeclareTransaction
Dim value As ICollection(Of TenderDetail)

value = instance.TenderDetails

instance.TenderDetails = value
```

``` csharp
[DataMemberAttribute]
public ICollection<TenderDetail> TenderDetails { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<TenderDetail^>^ TenderDetails {
    ICollection<TenderDetail^>^ get ();
    void set (ICollection<TenderDetail^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[TenderDetail](tenderdetail-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[DropAndDeclareTransaction Class](dropanddeclaretransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

