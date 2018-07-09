---
title: (RUS) Set up a customs counteragent
TOCTitle: (RUS) Set up a customs counteragent
ms:assetid: a196d3af-4564-440e-a7ea-5e753f6a4e51
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733263(v=AX.60)
ms:contentKeyID: 49685230
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a customs counteragent [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Customs counteragents** form to set up a vendor account as a customs authority or a customs broker. You can also set up a customs office code and a posting profile that is used to calculate customs payments. This information is included in customs declarations that are submitted to the customs authority. The codes for the customs offices are defined in the Customs Code of the Russian Federation.

In the **Acquit method** field, you can specify an acquit method. The acquit method determines the entity that provides customs when the customs clearance is processed by the customs broker. When you create a customs journal, the available customs brokers are filtered based on the acquit method that you selected.

1.  Click **Inventory management** \> **Setup** \> **Custom payments** \> **Customs counteragents**.

2.  Create a customs counteragent.

3.  In the **Counteragent account** field, select a vendor account number as the counteragent account number.

4.  In the **Counteragent type** field, select the type of counteragent.

5.  In the **Description** field, enter a brief description of the customs counteragent.

6.  In the **Customs office code** field, enter the identification code of the customs office.
    

    > [!NOTE]
    > <P>This field is available only when you select <STRONG>Custom authority</STRONG> in the <STRONG>Counteragent type</STRONG> field.</P>



7.  In the **Acquit method** field, select the acquit method for the customs services that are provided.
    

    > [!NOTE]
    > <P>This field is available only when you select <STRONG>Custom broker</STRONG> in the <STRONG>Counteragent type</STRONG> field.</P>



8.  In the **Posting profile** field, select the posting profile that is used to calculate the customs payments.

## See also

[(RUS) Set up a customer as a foreign counteragent](rus-set-up-a-customer-as-a-foreign-counteragent.md)

[(RUS) Set up a vendor as a foreign counteragent](rus-set-up-a-vendor-as-a-foreign-counteragent.md)

[(RUS) Customs counteragents (form)](https://technet.microsoft.com/en-us/library/jj733233\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

