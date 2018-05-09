---
title: TradeAgreementPriceLine.CustPriceGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustPriceGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreementPriceLine.CustPriceGroup
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreementpriceline.custpricegroup(v=AX.60)
ms:contentKeyID: 65320543
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreementPriceLine.CustPriceGroup
dev_langs:
- CSharp
- C++
- VB
---

# CustPriceGroup Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property CustPriceGroup As String
    Get
    Set
'Usage
Dim instance As TradeAgreementPriceLine
Dim value As String

value = instance.CustPriceGroup

instance.CustPriceGroup = value
```

``` csharp
[IgnoreDataMemberAttribute]
public string CustPriceGroup { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property String^ CustPriceGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TradeAgreementPriceLine Class](tradeagreementpriceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

