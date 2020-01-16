---
title: ProductList.RemovedColumns Property  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: RemovedColumns Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductList.RemovedColumns
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.productlist.removedcolumns(v=AX.60)
ms:contentKeyID: 65316017
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductList.RemovedColumns
dev_langs:
- CSharp
- C++
- VB
---

# RemovedColumns Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Property RemovedColumns As ISet(Of String)
    Get
    Private Set
'Usage
Dim instance As ProductList
Dim value As ISet(Of String)

value = instance.RemovedColumns
```

``` csharp
public ISet<string> RemovedColumns { get; private set; }
```

``` c++
public:
property ISet<String^>^ RemovedColumns {
    ISet<String^>^ get ();
    private: void set (ISet<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[ProductList Class](productlist-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

