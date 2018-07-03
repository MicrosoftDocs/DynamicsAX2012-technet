---
title: Method Type Attribute
TOCTitle: Method Type Attribute
ms:assetid: d0b383f0-e92d-492e-b0e7-1c50f70fe1aa
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg881191(v=AX.60)
ms:contentKeyID: 35251829
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Method Type Attribute 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you use the AIF Document Service Wizard to create a service in Microsoft Dynamics AX, it adds the method type attribute to each service class method that is exposed as a service operation. The method type attribute corresponds to the action that the method performs: create, read, update, delete, find, getKeys, getChangedKeys, and findKeys.

The following code shows the CustCustomerService.delete method decorated with the AifDocumentDeleteAttribute attribute.
```X++  
    [AifDocumentDeleteAttribute, SysEntryPointAttribute(true)] 
    public void delete(AifEntityKeyList _entityKeyList)
    {
        CustCustomer custCustomer = new CustCustomer();
        this.deleteList(_entityKeyList, custCustomer);
    }
```

> [!NOTE]
> <P>The <A href="https://technet.microsoft.com/en-us/library/gg958657(v=ax.60)">SysEntryPointAttribute</A> is required to be set for service operations. For more information, see <A href="setting-sysentrypointattribute-for-services.md">Setting SysEntryPointAttribute for Services</A>.</P>



The method type attribute is used when you call the metadata service to return information about a particular service. For example, you could call the metadata service and request all the methods on a particular service class that have the AifDocumentDeleteAttribute attribute. This would return all the service methods that delete data. For more information, see [Metadata Service](metadata-service.md).

The method type attribute is optional. However, if you add a method to a service class that performs one of these actions, you should use the corresponding method type attribute. The following table lists the method type attributes.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Attribute</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AifDocumentCreateAttribute</p></td>
<td><p>Specifies that the method creates a document.</p></td>
</tr>
<tr class="even">
<td><p>AifDocumentDeleteAttribute</p></td>
<td><p>Specifies that the method deletes a document.</p></td>
</tr>
<tr class="odd">
<td><p>AifDocumentFindAttribute</p></td>
<td><p>Specifies that the method finds one or more documents.</p></td>
</tr>
<tr class="even">
<td><p>AifDocumentFindKeysAttribute</p></td>
<td><p>Specifies that the method finds one or more documents and returns only the document keys.</p></td>
</tr>
<tr class="odd">
<td><p>AifDocumentReadAttribute</p></td>
<td><p>Specifies that the method reads a single document.</p></td>
</tr>
<tr class="even">
<td><p>AifDocumentUpdateAttribute</p></td>
<td><p>Specifies that the method updates one or more documents.</p></td>
</tr>
<tr class="odd">
<td><p>AifDocumentGetKeysAttribute</p></td>
<td><p>Specifies that the method retrieves the keys for documents based on a document filter. For more information, see <a href="configure-processing-options.md">Configure processing options</a>.</p></td>
</tr>
<tr class="even">
<td><p>AifDocumentGetChangedKeysAttribute</p></td>
<td><p>Specifies that the method retrieves the keys for documents based on a document filter and a date that is passed in. For more information, see <a href="configuring-aif-for-change-tracking.md">Configuring AIF for change tracking</a>.</p></td>
</tr>
</tbody>
</table>


If you create your own custom document service, make sure that you add the method type attribute to the methods that are exposed as service operations.

## See also

[Metadata Service](metadata-service.md)

[Document Class Service Operations](document-class-service-operations.md)

