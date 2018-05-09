---
title: Add or configure websites
TOCTitle: Add or configure websites
ms:assetid: 5b1f0280-ee34-45b7-a688-298f00163715
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh496419(v=AX.60)
ms:contentKeyID: 37071996
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Add or configure websites 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In services and Application Integration Framework (AIF), the web services on IIS feature lets you expose services through websites. These websites are exposed to an intranet or the Internet through Internet Information Services (IIS). During installation of web services on IIS, Microsoft Dynamics AX Setup creates a default website, as follows:

  - The default name of the website is computer name-Default Web Site-MicrosoftDynamicsAXAif60.

  - The default share path of the virtual directory is \\\\computer name\\MicrosoftDynamicsAXAif60.

  - The default URL is http://computer name:8101/MicrosoftDynamicsAXAif60.

You can create additional websites if you require them. For example, you might have to expose a web service through a web server that is installed on a different computer than the instance of Application Object Server (AOS).

## Add a website

Before you can use the HTTP adapter to connect an integration port to a website other than the default website, you must create a record in the **Web sites** form.

1.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Web sites**.

2.  Click **New**.

3.  Enter a name and an optional description for the website.

4.  In the **Virtual directory share path** field, enter the URI of the virtual directory for the website.
    
      - If your website is deployed as an application, you can view the virtual directory path in IIS Manager. Click **Advanced settings**, and then view the string in the **Virtual path** field. Note that you must add the server name to the beginning of the string in the **Virtual path** field. For example, if the server name is MyServer, and the **Virtual path** field contains the string \\MyWebsiteVirtualDirectory, the full virtual directory path is \\\\MyServer\\MyWebsiteVirtualDirectory.
    
      - If your website is not deployed as an application, you must add a virtual directory by using IIS Manager. In the **Connections** pane, select your website, and then click **Add virtual directory**. Then, in the **Add virtual directory** dialog box, enter the required information. To view the virtual path, select the virtual directory in the **Connections** pane, and then click **Advanced settings**. Note that you must add the server name to the beginning of the string in the **Virtual path** field, as described in the previous item.

5.  In the **URL** field, enter the address of the website, such as http://MyComputer:8101/MyNewWebsite.

6.  Click **Validate** to test the website connection. Validation confirms that each directory path that you selected exists, and that the object server has permissions to read, write, and delete in the directory. The Infolog contains detailed information about the status of the website connection.

After you have added a website, you can select the website when you configure an integration port to use the **HTTP** adapter.

## Configuration notes

  - You must set the appropriate permissions for a new virtual directory so that Microsoft Dynamics AX can access the file share. The group that is named Microsoft Dynamics AX Web Service Administrators must have full access to the new virtual directory and file share. If this group does not exist as a local group on the new computer, you must create it. You must then add, as a user, the domain account for all AOS instances that require access. For these changes to take effect, you must restart all AOS instances that you added to the group.

  - When you install web services on IIS, a record for the new website is added to the AifWebsites table. If you uninstall Web services on IIS, this record is not deleted from the table. Because this record still exists, you may receive a warning if you later reinstall Web services on IIS. You can either manually delete the record from the AifWebsites table or ignore the warning.

## See also

[Install web services on IIS](install-web-services-on-iis.md)

[Create a Virtual Directory (IIS 7)](http://go.microsoft.com/fwlink/?linkid=230439)

[Understanding Sites, Applications, and Virtual Directories on IIS 7](http://go.microsoft.com/fwlink/?linkid=230441)

[Walkthrough: Exchanging documents by using the HTTP adapter](walkthrough-exchanging-documents-by-using-the-http-adapter.md)

