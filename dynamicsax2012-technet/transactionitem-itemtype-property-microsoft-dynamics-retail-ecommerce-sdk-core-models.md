---
title: TransactionItem.ItemType Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: ItemType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem.ItemType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.transactionitem.itemtype(v=AX.60)
ms:contentKeyID: 65316595
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem.ItemType
dev_langs:
- CSharp
- C++
- VB
---

# ItemType Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemType As TransactionItemType
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As TransactionItemType

value = instance.ItemType

instance.ItemType = value
```

``` csharp
[DataMemberAttribute]
public TransactionItemType ItemType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property TransactionItemType ItemType {
    TransactionItemType get ();
    void set (TransactionItemType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItemType](transactionitemtype-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

