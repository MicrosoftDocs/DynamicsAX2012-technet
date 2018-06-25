---
title: Customize service contracts
TOCTitle: Customize service contracts
ms:assetid: f03eab90-9af3-4284-a039-19cdd9903789
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh202119(v=AX.60)
ms:contentKeyID: 35949378
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Customize service contracts [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic describes one step in the process for managing integration ports. For more information, see <A href="managing-integration-ports.md">Managing integration ports</A>.</P>



This topic describes how to configure service contracts in services and Application Integration Framework (AIF) by using either the **Inbound ports** form or the **Outbound ports** form. To open these forms, follow one of these steps:

  - Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

  - Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.

Use the **Service contract customizations** FastTab to specify which service operations are available, and which data policies are used to customize documents.

For information about the types of services that Microsoft Dynamics AX 2012 supports and an overview of service operations, see [Services, service operations, and service groups](services-service-operations-and-service-groups.md). For more information about document service classes that includes details about the data fields and service operations that are supported, see [Standard Axd Documents](http://go.microsoft.com/fwlink/?linkid=216872) on MSDN.

## Register services

A service must be registered before it can be used. Some services that are included with Microsoft Dynamics AX 2012 are automatically registered during installation. We recommend that you register services before you use AIF features for the first time. Whenever a new service is added to the Application Object Tree (AOT), you must register the new service. Registration makes the service available in the configuration forms for enhanced integration ports. To register services, follow these steps.

1.  Click **System administration** \> **Setup** \> **Checklists** \> **Initialization checklist**.

2.  Expand the **Initialize system** node.

3.  Click **Set up Application Integration Framework**.

Microsoft Dynamics AX registers adapters, basic ports, and services. Registration can take some time to be completed.

## Expose service operations

When you configure an integration port, you must know which service operations you want to expose from the port. The names of service operations contain the name of the service and the name of the service operation, separated by a period. For example, the read operation for the Sales Order service is named **SalesSalesOrderService.read**.

To configure the service operations that can be accessed through the port, follow these steps.

1.  On the **Service contract customizations** FastTab, click **Service operations** to open the **Select service operations** form.

2.  In the **Remaining service operations** list, click the service operations that you want to expose. To select multiple service operations, hold down the CTRL key, and then click each service operation. To select a range of service operations, hold down the SHIFT key, and then click the first and last service operations in the range.

3.  If the service operations that you want are not listed, click the left arrow button to move selected service operations to the **Selected service operations** list. To move selected service operations back to the **Remaining service operations** list, click the right arrow button.

4.  Close the form.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><img src="images/Ee355075.alert_security(AX.60).gif" title="Security note" alt="Security note" /><strong>Security Note</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Expose only the service operations that you must expose to service consumers.</p></td>
</tr>
</tbody>
</table>


## Customize documents

A document that is exchanged through services and AIF contains data, and the data must follow a schema. The schema, which is also an XML document, defines the elements that the document can use to contain data that corresponds to database fields.

When you set up a document exchange in AIF, you can specify which data fields are transferred by specifying the elements that are used in the document. For each field, you can also specify the valid values, which are named legal values. This specification is known as the data policy for the document exchange. Note that data policies apply only to document services. The data policy is defined for each service that is exposed from the integration port. You configure the data policy by using the **Document data policies** form.

There are two settings for elements in the **Field level XSD restrictions** group in the **Document data policies** form: **Enabled** and **Required**.

An element that can be included in an exchange is said to be enabled. For inbound documents, only elements that are enabled can be submitted. If a document that is received includes elements that are not enabled, the document is rejected, and an exception is logged. For outbound documents, only elements that are enabled are included.

An element that must be included in an exchange is said to be required. For inbound documents, elements that are required are automatically enabled. For inbound documents, an element may be designated as required in three ways:

  - The document class defines the field as a mandatory field. If a field is mandatory, the database record cannot be inserted or updated unless the field exists. Additionally, no default value is available for the field. In this case, the Mandatory property of the database field is set to Yes.

  - The XML schema defines the element as a required element. In this case, the schema definition for the element has the minOccurs="1" attribute.

  - You define the element as a required element by selecting **Required** in the **Field level XSD restrictions** group.
    

    > [!IMPORTANT]
    > <P>When you define a required element, you must also select <STRONG>Validate document XML</STRONG> on the <STRONG>Processing options</STRONG> FastTab of the integration port. When XML validation is disabled, AIF does not apply data policies, which may cause unexpected results in some scenarios.</P>



For an inbound document, elements that are enabled but not required are optional to the exchange. If the schema defines an element as required, or if the document class defines the corresponding field as mandatory, you cannot use the data policy settings to make the element optional. If you clear the **Enabled** check box for an element that is used to calculate the value of another field, you must clear the **Enabled** check box for the calculated field. This requirement helps guarantee that unauthorized users cannot deduce the value of the original field, which is not enabled.

**Viewing schemas**

You can view and save the schema for the document service, including its imported schemas. When you view or save the schema, the schema includes the changes that were made by your data-policy customizations. If you have not made any data-policy customizations, then you will see the default document service schema.

To view the schema, click **View schema** to open the XML viewer. The XML viewer includes buttons that enable you to view imported schemas and to save schema files. You can use the schema files when working with tools, such as BizTalk Server, or creating transforms.

**Default behavior**

If you do not enable data policies, an integration port applies only the data policies that are specified by the default document service schema. All elements that are described by the schema are automatically enabled. All elements that the schema defines as required are automatically required.

### Configure data policies

To configure data policies for document exchanges, follow these steps.

1.  On the **Service contract customizations** FastTab, select **Customize documents**.

2.  Click **Data policies** to open the **Document data policies** form.

3.  In the **Document name** field, click a document name.

4.  In the **Field level XSD restrictions** group, configure each element for which you want to customize the data policy.
    
      - Select or clear the **Enabled** check box.
    
      - Select or clear the **Required** check box.

5.  In the **Legal values for %1** group, configure valid values for specific elements.
    
    1.  In the **Field level XSD restrictions** group, click an element name.
    
    2.  Click **Add** to add a new legal value.
    
    3.  In the **Legal value** field, enter the new legal value.

6.  Close the form.

## Next step

[Configure processing options](configure-processing-options.md)

