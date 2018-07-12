---
title: Configure or bypass IPsec for Synch Service
TOCTitle: Configure or bypass IPsec for Synch Service
ms:assetid: 645f73b8-684b-46cd-aa62-6d59342d22fb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ679918(v=AX.60)
ms:contentKeyID: 49557900
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Configure or bypass IPsec for Synch Service 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Synch Service requires a specific configuration for IPsec encryption and authentication. This topic provides instructions for setting up the minimum configuration. If you use another method to help secure data transport, such as a virtual private network (VPN), you can bypass the IPsec requirement for Synch Service.


> [!NOTE]
> <P>Synch Service is required for Retail only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack. In Microsoft Dynamics AX 2012 R3, this component is used only to support previous versions of Retail POS while you upgrade (N-1).</P>



For more information about the firewall settings that are required by Microsoft Dynamics AX Retail services, see [Firewall settings for Microsoft Dynamics AX components](firewall-settings-for-microsoft-dynamics-ax-components.md).

## Configure IPsec when a VPN is not used

This procedure must be completed on every computer where Synch Service is installed. This includes the computer that runs Application Object Server (AOS) and all computers that run the Microsoft Dynamics AX client.


> [!NOTE]
> <P>On computers that are on a domain, domain policies override the local policies that are described in this section. Consult the domain administrator to determine whether you have to complete this procedure.</P>



Retail supports Network Load Balancing (NLB) for data that comes from the store to Microsoft Dynamics AX. If IPsec is enabled, we recommend that you not use NLB.

1.  Click **Start** \> **Administrative Tools** \> **Local Security Policy**. You can also open Local Security Policy by typing **secpol.msc** in the search or **Run** box.

2.  Right-click **IP Security Policies on Local Computer**, and then click **Create IP Security Policy**.

3.  In the IP Security Policy Wizard, provide the requested information. On the **Requests for Secure Communication** page, clear the **Activate the default response rule** check box. On the final page of the wizard, select the **Edit properties** check box, and then click **Finish**.

4.  In the **New IP Security Policy** dialog box, clear the **Use Add Wizard** option, and then click **Add**.

5.  In the **New Rule Properties** dialog box, on the **IP Filter List** tab, click **Add**.

6.  In the **IP Filter List** dialog box, type a name for the filter, clear the **Use Add Wizard** option, and then follow these steps:
    
    1.  Click **Add**.
    
    2.  On the **Addresses** tab, select **Any IP Address** in both boxes.
    
    3.  On the **Protocol** tab, select a protocol type of **TCP**, select **From any port**, select **To this port**, and then type the port number that you specified as the server port for Synch Service communications. By default, the port number is 16750.
    
    4.  On the **Description** tab, type a name or a brief description for this filter, and then click **OK**.
    
    5.  Click **OK** to close the **IP Filter List** dialog box.

7.  In the **New Rule Properties** dialog box, on the **IP Filter List** tab, select the new filter list.

8.  On the **Filter Action** tab, clear the **Use Add Wizard** check box, and then click **Add**.

9.  In the **New Filter Action Properties** dialog box, follow these steps:
    
    1.  On the **General** tab, type a name for the filter action.
    
    2.  On the **Security Methods** tab, select **Negotiate security**, click **Add**, select **Integrity and encryption**, and then click **OK**.
    
    3.  Click **OK**.

10. On the **Filter Action** tab, select the new filter action.

11. On the **Authentication Methods** tab, click **Add**.

12. Select the authentication method to use, specify any required settings, and then click **OK**.

13. Select the new authentication method, click **Move Up** until the new method is at the top of the list, and then click **Close**.

14. In the **New Rule Properties** dialog box, click **Apply**.

15. In the **Local Security Policy** console, right-click the new policy, and then click **Assign**.

## Bypass the IPsec requirement when a VPN is used

If you use a method other than IPsec to help secure data transport, such as a VPN, you can bypass the IPsec requirement for Synch Service. Complete the following procedure in Microsoft Dynamics AX.

1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Channel integration** \> **Commerce Data Exchange: Synch Service profiles**.

2.  Select the profile for which to bypass IPsec, select **Disable IPSec**, and then click **Close**.

3.  On the computer that runs Synch Service, start the Synch Service Settings wizard. To start the wizard, click **Start** \> **All Programs** \> **Microsoft Dynamics AX** \> **Commerce Data Exchange** \> **Synch Service** \> **Service Settings**.
    

    > [!IMPORTANT]
    > <P>You must run the wizard as an administrator.</P>



4.  Click **Next** until you reach the **Synch Service Properties** page.

5.  Select **Disable IPsec**, and then click **Close**.

  


