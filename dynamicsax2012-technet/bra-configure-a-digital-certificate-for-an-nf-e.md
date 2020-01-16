---
title: (BRA) Configure a digital certificate for an NF-e
TOCTitle: (BRA) Configure a digital certificate for an NF-e
ms:assetid: aaaf0d4c-5bc0-4eee-80bb-f237c59f2322
ms:mtpsurl: https://technet.microsoft.com/library/JJ917352(v=AX.60)
ms:contentKeyID: 50952841
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- digital certificate
- BRA
- Brazil
- NF-e
- electronic fiscal document
audience: Application User
ms.search.region: Brazil
---

# (BRA) Configure a digital certificate for an NF-e 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must configure and grant access to the digital certificate to sign and transmit the generated XML message for a nota fiscal eletrônica (NF-e) batch.

To grant access to the digital certificate private key and configure the Windows communication foundation (WCF) client to use the certificate for authentication, you must import the digital certificate to the computer on which the Microsoft Dynamics AX application object server (AOS) is running.

Use the following procedure to grant an AOS user access to the digital certificate private key on a computer that is running Windows Server 2008.

1.  Click **Start**.

2.  In the **Start Search** field, enter mmc, and then press **ENTER** to open the Microsoft Management Console.

3.  In the **Console1** form, click **File**, and then click **Add/Remove Snap in**.

4.  In the **Add or Remove Snap-ins** form, in the **Available snap-ins** list, select **Certificate** snap-in, and then click **Add**.

5.  Select a check box to indicate the account to which the snap-in is added, and then click **Finish**.

6.  Click **OK**.

7.  In the **Console1** form, in the left pane, expand the **Certificates** node that you added, and then expand the **Personal** node.

8.  In the right pane, right-click **Certificates**, and then click **All Tasks** \> **Import**.

9.  Follow the instructions in the Certificate Import Wizard to import the digital certificate.

10. In the **Console1** form, right-click the digital certificate that you imported, and then click **All Tasks** \> **Manage Private Key**.

11. Select **NETWORK SERVICE**, and then click **Add** to add the user profile under which the Microsoft Dynamics AX AOS runs. Click **OK**.

12. Close the **Console1** form, and click **Yes** to save the changes.

## See also

[(BRA) About the NF-e process](bra-about-the-nf-e-process.md)

  


