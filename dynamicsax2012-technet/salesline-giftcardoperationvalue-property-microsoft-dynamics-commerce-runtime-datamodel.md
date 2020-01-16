---
title: SalesLine.GiftCardOperationValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GiftCardOperationValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.GiftCardOperationValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.giftcardoperationvalue(v=AX.60)
ms:contentKeyID: 65317936
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.GiftCardOperationValue
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardOperationValue Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("GIFTCARDOPERATION")> _
<DataMemberAttribute> _
Public Property GiftCardOperationValue As Integer
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Integer

value = instance.GiftCardOperationValue

instance.GiftCardOperationValue = value
```

``` csharp
[ReadOnlyAttribute("GIFTCARDOPERATION")]
[DataMemberAttribute]
public int GiftCardOperationValue { get; set; }
```

``` c++
[ReadOnlyAttribute(L"GIFTCARDOPERATION")]
[DataMemberAttribute]
public:
property int GiftCardOperationValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

