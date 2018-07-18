---
title: (DNK) Set up AIF for OIOUBL electronic invoicing
TOCTitle: (DNK) Set up AIF for OIOUBL electronic invoicing
ms:assetid: df365dc0-d048-49d0-a6fe-88d31f65cafb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227417(v=AX.60)
ms:contentKeyID: 36059695
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- AIF
- electronic invoicing
- OIOUBL
- Forms.AifOutboundPort
- NO - 00009
- MsDynAx060.Forms.AifOutboundPort
audience: Application User
ms.search.region: Denmark
---

# (DNK) Set up AIF for OIOUBL electronic invoicing 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Outbound ports** form to create an outbound port, set up services and adapters for an outbound port, and specify the Application Integration Framework (AIF) settings that are required to generate Offentlig Information Online Universal Business Language (OIOUBL) electronic invoices.

You must scan for new adapters and services before you can set up outbound ports for the first time. The port setup is affected when there is a change in the Application Object Tree (AOT). You must also scan the adapters and services every time that a change that affects the port configuration is made to the AOT.

For information about how to configure the enhanced integration port, go to [Managing integration ports](managing-integration-ports.md).

1.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.

2.  In the **Port name** and **Description** fields, enter a name and a description for the outbound port.

3.  In the **Adapter** field, select **File system adapter**. This adapter is used to create and save the OIOUBL electronic invoices.

4.  In the **URI** field, specify the location of the Source folder where you want to save the sales invoices. For more information, see [(DNK) Configure Microsoft Dynamics AX for OIOUBL electronic invoicing](dnk-configure-microsoft-dynamics-ax-for-oioubl-electronic-invoicing.md).

5.  Click the **Service contract customizations** FastTab, and then click **Service operations**.

6.  In the **Select service operations** form, select the **SalesSalesEInvoiceService.read** service operation for sales invoices, or the **ProdProjEInvoiceService.read** service operation for project invoices, and move it to the **Selected service operations** list.

7.  Close the form.

8.  In the **Outbound ports** form, select the **Customize documents** check box, and then click **Data policies**.

9.  In the **Document data policies** form, click **Enable all** to select all XML schema elements, and then close the form.

10. Click the **Processing options** FastTab, and then in the **Default encoding format** field, select **UTF-8**.

11. Select the **Apply value mapping** check box, and then click **Value mapping** to open the **Value mapping** form, where you can map the values such as item number, customer account number, vendor account number, terms of delivery, and unit for the outbound port. Close the form.
    

    > [!NOTE]
    > <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: You must indicate a unit for which you specified the external code according to the United Nations Center for Trade Facilitation and Electronic Business Information Content Management Group (UN/CEFACT ICG) standards. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh209233(v=ax.60)">Units (form)</A> and <A href="https://technet.microsoft.com/en-us/library/aa583814(v=ax.60)">External codes (form)</A>.</P>



12. Click the **Troubleshooting** FastTab, and then in the **Logging mode** field, select **All document versions**.

13. Select the **Include exceptions in fault** check box to display the X++ error messages.

14. Click the **Security** FastTab, and then in the **Restrict to company** field, select the company for which the electronic invoices are generated.

15. Click **Activate** to use the port to exchange data by using AIF.

## See also

[AIF outbound ports (form)](https://technet.microsoft.com/en-us/library/hh227495\(v=ax.60\))

  


