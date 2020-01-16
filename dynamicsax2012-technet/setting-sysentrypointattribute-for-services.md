---
title: Setting SysEntryPointAttribute for Services
TOCTitle: Setting SysEntryPointAttribute for Services
ms:assetid: 89f733b4-936c-4673-86d0-f6b64c7708f6
ms:mtpsurl: https://technet.microsoft.com/library/Hh801193(v=AX.60)
ms:contentKeyID: 43976725
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Setting SysEntryPointAttribute for Services 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The [SysEntryPointAttribute](https://technet.microsoft.com/library/gg958657\(v=ax.60\)) indicates what authorization checks are performed for a method that is called on the server. This attribute must be set for all service operations. For more information about how to set attributes on X++ methods, see [Syntax for Attribute Classes](https://technet.microsoft.com/library/gg844185\(v=ax.60\)).

The AIF Document Service Wizard automatically decorates service operations with \[SysEntryPointAttribute(true)\]. When you develop custom services you must use the [SysEntryPointAttribute](https://technet.microsoft.com/library/gg958657\(v=ax.60\)) to decorate each service operation.

## SysEntryPointAttribute Settings

The following table describes the possible values for the constructor of the SysEntryPointAttribute class.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Setting</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>[SysEntryPointAttribute(true)]</p></td>
<td><p>Indicates authorization checks are performed on the calling user for all tables accessed by the method.</p></td>
</tr>
<tr class="even">
<td><p>[SysEntryPointAttribute(false)]</p></td>
<td><p>Indicates authorization checks are not performed on any tables accessed by the method.</p></td>
</tr>
</tbody>
</table>


## Example Document Service

The following example shows the SysEntryPointAttribute set to true on the create method for the CustCustomerService class.

    [AifDocumentCreateAttribute, SysEntryPointAttribute(true)]
    public AifEntityKeyList create(CustCustomer _custCustomer)
    {
        return this.createList(_custCustomer);
    }

## See also

[Attributes on X++ Types and Methods](https://technet.microsoft.com/library/gg846588\(v=ax.60\))

[AOSAuthorization Property on Tables](https://technet.microsoft.com/library/bb278259\(v=ax.60\))

