---
title: SalesTransaction.AttributeValues Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AttributeValues Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.AttributeValues
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.attributevalues(v=AX.60)
ms:contentKeyID: 49843546
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.AttributeValues
dev_langs:
- CSharp
- C++
- VB
---

# AttributeValues Property

Gets or sets the sales attributes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AttributeValues As Collection(Of AttributeValueBase)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Collection(Of AttributeValueBase)

value = instance.AttributeValues

instance.AttributeValues = value
```

``` csharp
[DataMemberAttribute]
public Collection<AttributeValueBase> AttributeValues { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<AttributeValueBase^>^ AttributeValues {
    Collection<AttributeValueBase^>^ get ();
    void set (Collection<AttributeValueBase^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[AttributeValueBase](attributevaluebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

