---
title: Configure client performance options
TOCTitle: Configure client performance options
ms:assetid: a3fc921c-f132-413c-802a-89e3eea409d8
ms:mtpsurl: https://technet.microsoft.com/library/Dn629437(v=AX.60)
ms:contentKeyID: 61321532
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Configure client performance options 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Many interface enhancements that have been added in Microsoft Dynamics AX 2012 carry performance overhead. To improve performance, you can reduce the use of FactBoxes and preview panes, or set forms to preload in your environment.

## Performance considerations for FactBoxes and preview panes

FactBoxes and preview panes can help you present relevant information in a single form, so that you do not have to switch between forms so often. However, FactBoxes and preview panes can be performance intensive for the following reasons:

  - Each FactBox and preview pane is a separate form. Therefore, for each FactBox and preview pane that is opened, you incur the cost of form initialization (**FormInit**) and rendering (**FormRun**).

  - FactBoxes and preview panes are rendered sequentially.

  - If a FactBox that includes an SQL query is expanded, the query is sent to the instance of Microsoft Dynamics AX Application Object Server (AOS) and the database. Therefore, the load on the servers increases.

  - FactBox queries that include summary information can be quite expensive with regard to database processing.

## Reducing client performance issues

This section describes how users, developers, and system administrators can reduce client performance issues that are caused by FactBoxes and preview panes.

  - **Users** – Users can collapse FactBoxes that are used less frequently by clicking the arrow (^) in the upper-right corner of the FactBox. When a FactBox is collapsed, the query that populates it is not executed. Therefore, the effect on the database is reduced. However, **FormInit** is still called. Users can also hide FactBoxes by clicking the rectangle in the upper-right corner of the FactBox. When a FactBox is hidden, no **FormInit** or query cost is incurred. When a user collapses and hides FactBoxes, these settings affect only the user and the selected form.

  - **Developers/Partners** – Partners and developers can change the form and remove unnecessary FactBoxes. Partners and developers should also verify that the query for any FactBox performs well, especially if the query requires lots of data, or if the form is required by many users.

  - **System administrators** – System administrators can configure system-wide client performance settings in the **Client performance options** form.

## Configuring client performance options

This section describes how you can adjust settings that affect the performance of client forms.

## Tune FactBox performance

As an administrator, you can completely disable FactBoxes. Alternatively, you can set FactBoxes to time out for all clients.

  - To disable FactBoxes, in the Client performance options form, clear the **FactBoxes enabled (requires client restart)** option.
    
    Users must restart the client to see the effect of this option.

  - To set a time-out value in seconds, in the Client performance options form, enter a value in the **Timeout (sec)** field.
    
    The time-out value limits the time that the database spends on FactBox queries. If the query cannot be completed in the time-out limit, the query is canceled. This behavior limits the load on Microsoft SQL Server and the response time for the form.

## Tune preview pane performance

You can completely disable preview panes. Alternatively, you can set preview panes to use the **Automatic enhanced previews enabled (requires client restart)** option.

  - To disable preview panes, in the Client performance options form, clear the **FactBoxes enabled (requires client restart)** option.

  - To enable enhanced previews in the Client performance options form, select the **Automatic enhanced previews enabled (requires client restart)** option.

## Preload complex forms

By default, forms that include more than 80 controls are preloaded and added to a preload cache. When the user opens a form, the system checks the preload cache for a preloaded version of the form. If a preloaded version is found, the system completes the initialization process and loads the form. Not all forms are preloaded. If resource limitations are met, the system starts to remove forms from the cache, starting with the forms that were least recently used. Forms such as lookups, parts, preview panes, and system forms are excluded from this mechanism.

You can turn off preloading by using the following methods:

  - To turn off preloading for the whole system, in the Client performance options form, clear the **Form pre-loading enabled (requires a client restart)** option.

  - To turn off preloading for a form, follow one of these steps:
    
      - Set form argument **allowUseOfPreloadedForm** for the X++ method to **true**.
    
      - Set the **Form.AllowPreLoading** metadata property to **No**.

  


