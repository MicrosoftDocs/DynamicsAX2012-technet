---
title: About creating multiple party records for one party
TOCTitle: About creating multiple party records for one party
ms:assetid: 274d6d24-0b8f-4f97-9410-517d776f6bdb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208489(v=AX.60)
ms:contentKeyID: 36056209
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About creating multiple party records for one party 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some organizations have multiple locations, legal entities, or lines of business. In this situation, party records for an organization can have varying default values depending on agreements that the organization has with your organization. It can be difficult to know when to create a single party record for a customer that has multiple locations, for example, versus when to create a party record for each location for the customer.

Creating separate records helps reduce confusion when you communicate with different areas in an organization. We recommend that you review your customer and vendor records and decide whether to create multiple party records by using the following criteria:

  - **Legal entity** – Create a separate party record for each legal entity within an organization or for any legal entity that is located in a country/region that differs from the other legal entities in the organization. This is especially important if separate organization numbers are assigned to the legal entities.
    
    For example, Fabrikam’s customer Contoso has four separate legal entities within Contoso Corporation:
    
      - Contoso-Hardware; organization number 123
    
      - Contoso-Software; organization number 234
    
      - Contoso-Education UK; organization number 345
    
      - Contoso-Education US; organization number 45678
    
    In this situation, Fabrikam should create five separate customer records: one customer record for Contoso Corporation, and one customer record for each legal entity. Each record contains the legal entity information, the organization number, and location information that is specific to the legal entity.

  - **Default values** – Create separate party records for departments or divisions within an organization, if necessary. If an organization does not contain multiple legal entities but does have departments or divisions, create separate party records based on the arrangements that your company has with each division or department.
    
    For example, Fabrikam is a customer of Contoso. Contoso has an individual agreement with each division of Fabrikam regarding default values such as credit limit and delivery terms. Contoso should create a separate customer record for each Fabrikam department.
    
    Each customer record for Fabrikam is associated with a unique party and contains division information, which includes location.

When you create multiple party records, you will likely want to record and track how the parties are related. To indicate the relationships, on the **Party** form, on the **Relationships** FastTab,

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

