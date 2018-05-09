---
title: TransactionItem.KitComponents Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: KitComponents Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem.KitComponents
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.transactionitem.kitcomponents(v=AX.60)
ms:contentKeyID: 65315951
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem.KitComponents
dev_langs:
- CSharp
- C++
- VB
---

# KitComponents Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitComponents As Collection(Of TransactionItem)
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As Collection(Of TransactionItem)

value = instance.KitComponents

instance.KitComponents = value
```

``` csharp
[DataMemberAttribute]
public Collection<TransactionItem> KitComponents { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<TransactionItem^>^ KitComponents {
    Collection<TransactionItem^>^ get ();
    void set (Collection<TransactionItem^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[TransactionItem](transactionitem-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

