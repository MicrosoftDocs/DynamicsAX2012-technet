---
title: (DNK) Set up batch processing for OIOUBL electronic invoicing
TOCTitle: (DNK) Set up batch processing for OIOUBL electronic invoicing
ms:assetid: f1ff9c46-5c14-45af-81b5-1db3d849c245
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227520(v=AX.60)
ms:contentKeyID: 36059959
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- batch processing
- electronic invoicing
- OIOUBL
audience: Application User
ms.search.region: Denmark
---

# (DNK) Set up batch processing for OIOUBL electronic invoicing 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Batch job** form to set up batch processing for Offentlig Information Online Universal Business Language (OIOUBL) electronic invoicing.

You can set up a batch job for sales outbound electronic invoices, and another batch job for project outbound electronic invoices.

1.  Click **System administration** \> **Inquiries** \> **Batch jobs** \> **Batch jobs**.

2.  Press CTRL+N to create a batch job, and then in the **Job description** field, enter a short description for the batch job.

3.  Save the batch job, and then click **View tasks**.

4.  In the **Batch tasks** form, press CTRL+N to create a batch task for the batch job, and then in the **Class name** field, select the **AifOutboundProcessingService** class name. In the **Company accounts** field, select the company you created the batch job for.

5.  Create two batch tasks that use the following class names:
    
      - **AifGatewaySendService**
    
      - **EInvoiceFileTransform\_OIOUBL**

6.  Select the batch task that uses the **EInvoiceFileTransform\_OIOUBL** class name, and then in the **Batch group** field, select a batch group.

7.  Click **Refresh** to refresh the data in the form.

8.  Click **Parameters**.

9.  In the **E-invoice OIOUBL XSL File Transformation** form, specify the locations of the Source, Target, Processed, and Error file storage folders. For the XSLT file path, select the path for the **eSalesInvoice\_DK\_OIOUBL** file for sales outbound electronic invoices, or the path for the **eProjectInvoice\_DK\_OIOUBL** file for project outbound electronic invoices, and then close the form.

10. Click the **Overview** tab.

11. Select the batch task that uses the **AifGatewaySendService** class name (the second task) to set up the order in which the batch tasks are run.

12. In the lower pane, press CTRL+N to create a condition for the selected batch task to run after the batch task that uses the **AifOutboundProcessingService** class name (the first task) has ended.

13. In the **Task ID** field, select the batch task that uses the **AifOutboundProcessingService** class name.

14. In the **Expected status** field, select **Ended**.
    

    > [!NOTE]
    > <P>You can also select the batch task that uses the <STRONG>EInvoiceFileTransform_OIOUBL</STRONG> class name, and then set the condition to run the batch task when the batch task that uses the <STRONG>AifGatewaySendService</STRONG> class name has ended.</P>



## See also

[(DNK) Set up recurring batch jobs](dnk-set-up-recurring-batch-jobs.md)

[Batch job (form)](https://technet.microsoft.com/en-us/library/aa585684\(v=ax.60\))

[Batch tasks (form)](https://technet.microsoft.com/en-us/library/hh209494\(v=ax.60\))

  


