---
title: Production Floor app for Microsoft Dynamics AX
TOCTitle: Production Floor app
ms:assetid: d90c2d60-1353-40d8-bf80-4b0e4c30a7c5
ms:mtpsurl: https://technet.microsoft.com/library/Dn771606(v=AX.60)
ms:contentKeyID: 62551179
author: Khairunj
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Production Floor app for Microsoft Dynamics AX 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

With the Microsoft Dynamics AX Production Floor app, you can quickly perform daily production tasks, such as:

  - View details about active production jobs

  - Start production jobs, report jobs as finished, and enter feedback about the jobs

  - Read files that are attached to production jobs

  - Clock-in or clock-out when you start or exit the app

  - Register breaks, indirect activities, and absences

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dn771606.TopicIcons_AboutThisApp(AX.60).png" title="About this app" alt="About this app" />
<p>Devices you can install this app on</p>
<p>Download this app</p>
<p>Use this app in demo mode</p>
<p>Integrate this app with Microsoft Dynamics AX</p>
<p>Set up this app on your device</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="https://blogs.msdn.com/b/axcompapp/">Dynamics AX companion apps (blog)</a></p></td>
</tr>
</tbody>
</table>


## Devices you can install this app on

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Device</p></th>
<th><p>Supported operation systems</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Tablet</p></td>
<td><p>Windows 8.1 RT</p>
<p>Windows 8.1 Pro</p></td>
</tr>
<tr class="even">
<td><p>Phone</p></td>
<td><p>Not supported</p></td>
</tr>
</tbody>
</table>


## Download this app

Click [here](https://apps.microsoft.com/windows/en-us/app/cc07f817-e74c-48aa-86ad-1c0345fff989) to download this app from the Store.

## Use this app in demo mode

You can run this app in demo mode, which lets you explore the features of the app without a connection to Microsoft Dynamics AX. To run the app in demo mode, complete these steps:

1.  Start the app.

2.  Swipe in from the right edge of the screen and tap **Settings**. (Or, if you’re using a mouse, point to the upper-right of the screen, move the mouse pointer down, and then click **Settings**.)

3.  Choose **Connection**.

4.  Move the **Demo mode** slider to **On**.

After running the app in demo mode, you can integrate the app with Microsoft Dynamics AX by completing the following sections in this article.

## Integrate this app with Microsoft Dynamics AX

To integrate this app with Microsoft Dynamics AX, complete the following procedures.

## Verify prerequisites

Before you can integrate this app with Microsoft Dynamics AX, make sure that the following prerequisites are in place.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required software</p></td>
<td><p>Microsoft Dynamics AX 2012 R3 or later must be installed. Note the following requirments:</p>
<ul>
<li><p>The <strong>Web services on IIS</strong> component must be installed.</p></li>
<li><p>The following license codes must be enabled: <strong>SFC1</strong>, <strong>SFC2</strong>, and <strong>SFCUser</strong>.</p></li>
</ul></td>
<td><p><a href="install-microsoft-dynamics-ax-2012.md">Install Microsoft Dynamics AX 2012</a></p>
<p><a href="install-web-services-on-iis.md">Install web services on IIS</a></p>
<p><a href="provide-license-information.md">Provide license information</a></p></td>
</tr>
<tr class="even">
<td><p>Required permissions</p></td>
<td><p>You must be assigned to the <strong>System administrator</strong> role in Microsoft Dynamics AX. You must be assigned to this role in order to:</p>
<ul>
<li><p>Integrate this app with Microsoft Dynamics AX.</p></li>
<li><p>Use this app.</p></li>
</ul></td>
<td><p><a href="assign-users-to-security-roles.md">Assign users to security roles</a></p></td>
</tr>
</tbody>
</table>


## Deploy the shop floor service

1.  Open the Microsoft Dynamics AX client.

2.  Open a new development workspace.

3.  In the AOT, expand the **Service Groups** node.

4.  Right-click **JmgShopfloorServiceGroup**, and then click **Deploy Service Group**.
    
    When the deployment is complete, the **Infolog** form is displayed. Verify that the following message is displayed in the form:
    
    *The port ‘JmgShopfloorServiceGroup’ was deployed successfully.*

## Create an inbound port

1.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

2.  Click **New**.

3.  In the **Port name** field, enter a name for the port, such as *ProductionFloorApp*.

4.  In the **Description** field, enter a description to help you identify this port.

5.  From the **Adapter** list, click **HTTP**.

6.  In the **URI** field, click the drop-down arrow. The **Select Web site** form is displayed.

7.  From the **Web site** list, select the available web site. (You’ll enter the URI of this web site when you Set up this app on your device.) Click **OK**.

8.  Click the **Service operations** button. The **Select service operations** form is displayed.

9.  From the **Remaining service operations** box, select all operations that start with “Jmg,” and then move them into the **Selected service operations** box. Click **Close**.

10. Click **Activate**.
    
    When the activation is complete, the **Infolog** form is displayed. Verify that the following message is displayed in the form:
    
    *The port 'ProductionFloorApp' was deployed successfully.*

## Set up this app on your device

1.  Start the app.

2.  Swipe in from the right edge of the screen and tap **Settings**. (Or, if you’re using a mouse, point to the upper-right of the screen, move the mouse pointer down, and then click **Settings**.)

3.  Choose **Connection**.

4.  Move the **Demo mode** slider to **Off**.

5.  Enter the server address. This is the URI of the web site that you selected in step 7 of the previous procedure. For example, the URI is formatted like this:
    
    http://*ServerName:PortNumber*/MicrosoftDynamicsAx41Aif/*ProductionFloorApp*/xppservice.svc
    
    In this example URI, *ProductionFloorApp* is the name of the inbound port that you entered in step 3 of the pervious procedure.

6.  Enter your Active Directory user name and password.

7.  Select a Microsoft Dynamics AX data partition. If you do not select a partition, the default partition is used.

8.  Click **Test connection** to verify that you can connect to the server.

9.  Select a company.

  


