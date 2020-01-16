---
title: Configure processing options
TOCTitle: Configure processing options
ms:assetid: 414871d6-7b56-46ff-ba12-4a8984a19189
ms:mtpsurl: https://technet.microsoft.com/library/Hh202050(v=AX.60)
ms:contentKeyID: 35949284
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Configure processing options 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic describes one step in the process for managing integration ports. For more information, see <A href="managing-integration-ports.md">Managing integration ports</A>.</P>



This topic describes how to configure processing options in services and Application Integration Framework (AIF) by using either the **Inbound ports** form or the **Outbound ports** form. To open these forms, follow one of these steps.

  - Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

  - Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.

Use the **Processing options** FastTab to specify how documents are validated, changed, or otherwise handled by the integration port. This topic provides information about how to configure settings for the following areas:

  - **Configure document handling** – Configure these settings to control error handling, parallel processing, and document validation.

  - **Configure transforms** – Configure these settings if you want to use Extensible Stylesheet Language Transformations (XSLT) or .NET-based transforms to convert any propriety format to the AIF schema, or any AIF schema to a proprietary format. For an overview of transforms, see [Messages and transforms in AIF](messages-and-transforms-in-aif.md).

  - **Configure pipelines** – Configure these settings if you want to preprocess requests or post-process responses for service operations by using components. For an overview of pipelines, see [Messages and transforms in AIF](messages-and-transforms-in-aif.md).

  - **Configure value mapping** – Configure these settings if you want to translate data values based on business rules.

  - **Configure document filters** – Configure these settings if you want to limit, or filter, the list of entity keys that is returned when a service requests entity keys.

The following sections provide information about how to configure settings for each area.

## Configure document handling

To configure how an integration port handles document exchanges, follow these steps.

1.  For inbound integration ports, configure how Microsoft Dynamics AX responds to errors that occur when batched messages are processed. Batched messages are message sets that combine multiple messages into a single message by using the message-set schema. For more information about schemas in AIF, see [Messages and transforms in AIF](messages-and-transforms-in-aif.md).
    
    In the **Upon error in batched requests:** field, select one of the following values:
    
      - **Continue** – Keep processing messages. The messages that raise errors may not process correctly. Check the exceptions log for details about errors.
    
      - **Halt** – Stop processing the rest of the message set.
    
      - **Rollback** – Stop processing the message set and undo any previously processed messages that have the current message-set identifier.
    

    > [!NOTE]
    > <P>This setting applies only when you use the file system adapter.</P>



2.  For inbound integration ports, select the **Process requests in parallel** check box to use parallel processing of messages. Clear the check box to use sequential processing. This check box affects both individual and batched message types. See [Sequential and parallel processing in services and AIF](sequential-and-parallel-processing-in-services-and-aif.md).

3.  Select the **Validate document XML** check box if you want Microsoft Dynamics AX to test that the document matches the schema for its service operation. Clear the check box if you want documents to be processed without validation.
    

    > [!WARNING]
    > <P>Disable validation only for trusted messages, such as messages that originate from trusted, internal sources. Disabling validation after you define custom data policies may produce unexpected results. See <A href="customize-service-contracts.md">Customize service contracts</A>.</P>



4.  Select the **Replace existing documents on create** check box if you want to enable the **create** service operation to perform the **update** service operation, if the record already exists. This setting simplifies the creation and update process, especially when using asynchronous message exchanges, where multiple operations cannot be easily performed.
    

    > [!WARNING]
    > <P>Use this setting only when multiple, concurrent users are not accessing the integration port.</P>



5.  For outbound integration ports, select a default encoding format in the **Default encoding format** field. Outbound documents are created by using the encoding format that you select. The default encoding format is **UTF-8**.

## Configure transforms

You can apply transformations, or transforms, to documents that are processed by an inbound or outbound integration port. In inbound integration ports, you can specify transforms for inbound messages or outbound responses. In outbound integration ports, you can specify transforms for outbound messages. Transforms for inbound exchanges are run before transforms for outbound exchanges. Transforms process the whole message. Therefore, both the body and headers of the message are processed.


> [!IMPORTANT]
> <P>You must apply a transform whenever an inbound document does not match the AIF schema.</P>



### Manage transforms

Before you can use a particular transform, you must add it to the database by using the **Manage transforms** form. You can also use this form to modify or delete the information about a transform. To add a new transform to the database, follow these steps.


> [!NOTE]
> <P>You must be logged into Windows Server as an administrator to add a new transform.</P>



1.  Open the **Manage transforms** form by following one of these steps.
    
      - Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**. Click **Inbound transforms**. Then, on the **Action Pane**, click **Manage transforms**.
    
      - Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**. Click **Outbound transforms**. Then, on the **Action Pane**, click **Manage transforms**.
    
      - Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**. Click **Outbound transforms**. Then, on the **Action Pane**, click **Manage transforms**.
    
      - In the MorphX development environment, click **Tools** \> **Application Integration Framework** \> **Manage transforms**.

2.  Click **New**.

3.  Enter a name and description for the transform.

4.  In the **Type** field, select the type of transform that you want to add to the database:
    
      - **XSL** – Add an XML-based transform that is contained in an .xsl or .xslt file.
    
      - **.NET assembly** – Add a .dll file that is created by using the .NET Framework.
        

        > [!WARNING]
        > <P>We do not recommend adding multiple instances of the same .NET assembly to the <STRONG>Manage transforms</STRONG> form by using a different name for each instance. When multiple instances of the .NET assembly are listed in the form, each instance refers to the same .dll file. Changes to the .dll file will affect all ports that reference the transform, regardless of the name of the transform in the <STRONG>Manage transforms</STRONG> form.</P>



5.  Click **Load**.

6.  Browse to the file that contains the transform, and then click **Open**.
    
    You can use the **Transform details** group to view the XSLT code or information about the .NET Framework assembly for the transform that you loaded.

7.  To save the data, press CTRL+S or close the form.

### Apply transforms

To apply transforms, follow these steps.

1.  For inbound transforms, select **Transform all requests**. For outbound transforms, select **Transform all responses**.

2.  Click **Inbound transforms** or **Outbound transforms**.
    

    > [!WARNING]
    > <P>Transforms that you apply by using this setting will not be run for synchronous message exchanges. For synchronous messages, use pipelines for preprocessing and post-processing of AIF messages.</P>

    
    Depending on the button that you clicked, either the **Inbound transforms** form or the **Outbound transforms** form opens. These forms are identical, except each instance contains only the transforms that are applied to the type of exchange that you are modifying, either inbound or outbound. You can use these forms to add a new transform, delete a transform, or modify a transform for the port.

3.  Click **New**.

4.  In the **Transform name** field, select a transform. This field contains the names of transforms that you added to the database in the previous section by using the **Manage transforms** form.

5.  If you apply multiple transforms to the port, you can change the order in which the transforms are processed. To move a transform higher in the order, select the name of the transform, and then click **Move up**. To move a transform lower in the order, select the name of the transform, and then click **Move down**.

6.  Close the form.

## Configure pipelines

You can use pipelines to add custom processing to documents that are processed by an inbound or outbound integration port. In inbound integration ports, you can use pipelines for inbound requests or outbound responses. In outbound integration ports, you can use pipelines for outbound messages. For inbound exchanges, pipelines are run after transforms. For outbound exchanges, pipelines are run before transforms. Pipelines process only the body of the message. For more information about pipelines, see [Messages and transforms in AIF](messages-and-transforms-in-aif.md).

### Add a pipeline component

To add a component to a pipeline, follow these steps.

1.  For inbound pipelines, select **Preprocess service operation requests**. For outbound pipelines, select **Post-process service operation responses**.

2.  Click **Inbound pipelines** or **Outbound pipelines**.
    
    Depending on the button that you clicked, either the **Inbound pipelines** form or the **Outbound pipelines** form opens. These forms are identical, except each instance contains only the pipeline components that are applied to the type of exchange that you are modifying, either inbound or outbound. You can use these forms to add a new component to the pipeline, delete a component from the pipeline, or modify a component in the pipeline.

3.  Click **New**.

4.  In the **Service operation ID** field, select a service operation.
    
    Each pipeline component is associated with a specific service operation. You can associate multiple pipeline components to each service operation.

5.  In the **Class name** field, select a component. The form may take some time to search for available components.

6.  In the **Purpose** field, enter the reason that you are using the component.

7.  Press CTRL+S to save the data.

8.  Click **Configure** to modify settings for the component that you added. Each type of component has a different configuration form. See the following sections for detailed information about how to configure each type of component.

### Configure the AifValueSubstitutor component

Before you can use the **AifValueSubstitutor** component, you must create at least one lookup table. A lookup table contains lookup entries that map internal values to external values. To create, delete, or modify lookup tables, use the **Value substitution maps** form. For information about how to create and use lookup tables, see [Configure value substitution maps](configure-value-substitution-maps.md).

### Configure the AifXmlTransform component

To configure the **AifXmlTransform** component, you use the **Pipeline XSLT transform** form. In this form, you can select an XSLT ID and specify how the XSLT is used.

#### Manage pipeline XSLT transforms

Before you can configure the **AifXmlTransform** component, you must add at least one transform to the database, or XSLT repository, by using the **XSLT repository** form. You can also use this form to modify, view, or delete an XSLT in the repository. To add a new transform to the XSLT repository, follow these steps.

1.  In the **Pipeline XSLT transform** form, click **Import XSLT**. The **XSLT repository** form opens.

2.  In the **XSLT repository** form, click **New** to add a new record.

3.  In the **XSLT ID** field, enter a unique ID for the transform.

4.  Click **Import**.

5.  Browse to the file that contains the XSLT style sheet that you want to add to the XSLT repository, and then click **Open**.
    
    To view the XML code for the XSLT that you imported, click **View**.

6.  Close the form.

#### Apply pipeline XSLT transforms

To apply a pipeline XSLT transform, follow these steps.

1.  In the **Pipeline XSLT transform** form, select an XSLT ID in the **XSLT ID** field.

2.  For inbound ports, you can limit the XSLT transform to a specific parameter for the service operation. Click **Apply transform to parameter**, and then select a method parameter in the **Parameter name** field.

3.  To enable scripts in the pipeline XSLT transform to run, click **Scripting enabled**.
    

    > [!WARNING]
    > <P>Scripts can pose a security risk. Enable scripting only for XSLT transforms that come from trusted sources.</P>



4.  Close the form.

## Configure value mapping

During value mapping, field data values are translated based on business rules. For example, you can translate internal item numbers to vendor-specific item numbers or industry-standard numbers, depending on the trading partner.

Value mapping can be performed on inbound and outbound XML documents, and is configured on each port. Value mapping creates a translation index between a field in Microsoft Dynamics AX and an external field in the document. This index gives you more flexibility when you must handle various internal, vendor-based, or industry-based codes.

To configure value mapping, follow these steps.

1.  Select **Apply value mapping**.

2.  Click **Value mapping** to open the **Value mapping** form.

3.  In each **Document value** field, select the document value that you want to use. The following table describes the settings for the **Document value** fields.
    
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
    <td><p><strong>Not specified</strong></p></td>
    <td><p>Do not apply a value map. This setting is the default setting.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Our</strong></p></td>
    <td><p>Use the code for the document value that is used internally by the company, and that is a part of the company's internal tables. Examples of internal codes are item numbers, customer account numbers, and vendor account numbers.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>External code</strong></p></td>
    <td><p>Use a custom external code instead of the code in the document. For example, in the <strong>Handling vendor numbers</strong> group, you can select a value for an external vendor code in the <strong>Vendor code</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>External item number</strong></p></td>
    <td><p>For items, use the external item number.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Bar code</strong></p></td>
    <td><p>For items, use a bar code value. Select a bar code by using the <strong>Bar code</strong> group.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>ISO currency code</strong></p></td>
    <td><p>For currency codes, use the International Standards Organization (ISO) 4217 currency code.</p></td>
    </tr>
    </tbody>
    </table>


4.  Perform general configuration. For more information, see the following sections:
    
    1.  Validate input
    
    2.  Use defaulting
    
    3.  Configure outbound properties

5.  Close the form.

The following table describes the data values that you can map.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Data</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Partners</strong></p></td>
<td><ul>
<li><p><strong>Vendor code</strong></p></li>
<li><p><strong>Customer code</strong></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Addresses</strong></p></td>
<td><ul>
<li><p><strong>Country/region code</strong></p></li>
<li><p><strong>County code</strong></p></li>
<li><p><strong>State code</strong></p></li>
<li><p><strong>ZIP/postal code</strong></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Items</strong></p></td>
<td><ul>
<li><p><strong>Item number code</strong></p></li>
<li><p><strong>Warehouse code</strong></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Units</strong></p></td>
<td><p><strong>Unit code</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Other base data</strong></p></td>
<td><ul>
<li><p><strong>Currency code</strong></p></li>
<li><p><strong>Mode of delivery code</strong></p></li>
<li><p><strong>Delivery terms codes</strong></p></li>
<li><p><strong>Charges code</strong></p></li>
<li><p><strong>Sales tax code</strong></p></li>
</ul></td>
</tr>
</tbody>
</table>


### Validate input

In services and AIF, data in an inbound XML document is usually validated by the Ax\<Table\> classes. Input validation guarantees that restrictions on the referential integrity, number sequence, and business logic are enforced. Input validation also prevents the insertion of incorrect data into the application. If you disable input validation, data from an inbound XML document is inserted into Microsoft Dynamics AX, regardless of the quality of that data.

By default, input validation is enabled. To disable input validation, clear **Validate input** on the **Setup** tab of the **Value mapping** form.

### Use defaulting

Defaulting sets predefined values in an inbound document if the document does not contain these values. If you disable defaulting, an inbound XML document is processed, regardless of whether the document contains required field values. As a result, some required fields may not contain values. If required fields do not contain values, the document is not processed, and an error is logged.

By default, defaulting is enabled. To disable defaulting, clear **Use defaulting** on the **Setup** tab of the **Value mapping** form.

### Configure outbound properties

You can limit the number of documents or entity keys that are returned from a request. By limiting the number of records that are returned, you reduce the size of the XML document that Application Object Server (AOS) processes.

For example, you may want to limit documents when the **read** and **find** service operations are called. These service operations typically return complete documents, and the number of records that are returned is unknown when the request is made. Therefore, large data sets may be returned.

To limit the number of documents that are returned, follow these steps.

1.  In the **Value mapping** form, click the **Setup** tab.

2.  In the **Limit number of documents** field, select **Yes**.

3.  If you want to limit the number of documents to 1,000, which is the default, select **Default** in the **Limitation type** field. If you want to use a limit other than 1,000, select **Specified**.

4.  If you selected **Specified** in the previous step, enter a value for the new limit in the **Max. number of documents** field.

## Configure document filters

You can apply document filters to documents that are sent in response to certain requests. Service users can retrieve a specific instance of a document by using an entity key. To retrieve a list of valid entity keys, service users can use the **findKeys**, **getKeys**, and **getChangedKeys** service operations.

  - **findKeys** – This service operation returns entity keys based on a query that the service user provides. Document filters do not affect this service operation.

  - **getKeys** – This service operation returns only entity keys that match document filters that you specify for the integration port.

  - **getChangedKeys** – This service operation returns only entity keys that match document filters that you specify for the integration port, and that were changed after a date and time that the caller specifies.

Each document filter that you create is defined for a specific document service. Each document filter adds a subset of entity keys to the response message.If no document filters are created for a port, **getKeys** and **getChangedKeys** return an empty set.


> [!NOTE]
> <P>Document filters are applied only to documents that have been configured for change tracking. Change tracking must be enabled for the database tables that the document service uses. For more information about how to enable change tracking, see <A href="https://go.microsoft.com/fwlink/?linkid=227482">Configuring and Managing Change Tracking</A>.</P>
> <P>Document filters can be used only with enhanced integration ports. Basic integration ports do not support document filters.</P>



To configure a document filter, follow these steps.

1.  In the **Inbound ports** form, click **Document Filters**. The **Document Filters** form opens.

2.  In the **Document name** field, select the document to which you want to add a filter. For example, for the Sales Order service, select **SalesOrder**.

3.  Select an existing document filter, or click **Add** to create a new document filter.

4.  In the **Description** field, enter a description that can remind you what the document filters do. For example, you can type "Amounts more than 10,000."

5.  Click **Configure** to open the configuration form for document filters. The contents of this form vary, depending on the document that you selected in step 2. The form is also customized for the service that you selected.

6.  In the **Tables** tree view, select the table that contains the field that you want to filter. For example, for the Sales Order service, select **Sales orders**.

7.  On the **Range** tab, select the row that contains the field that you want to modify, or click **Add** to add a new field.

8.  In the **Field** field, select the field that you want to filter. For example, for the Sales Order service, you may want to filter the **Total amount** field.

9.  In the **Criteria** field, enter the filtering rule. For example, if you are filtering the **Total amount** field, you may want to return only sales orders that have amounts of more than 10,000. In this case, type "\>10000".

10. When you have finished, close the forms.

## Next step

[Configure troubleshooting options for integration ports](configure-troubleshooting-options-for-integration-ports.md)

