---
title: (MEX) Customize Microsoft Dynamics AX to include the XML addenda element for a customer
TOCTitle: (MEX) Customize Microsoft Dynamics AX to include the XML addenda element for a customer
ms:assetid: 00649794-1532-4f2a-9362-a77f23d7d46b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242090(v=AX.60)
ms:contentKeyID: 36055915
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Customize
- AX
- (MEX)
- customer
- Microsoft Dynamics
- XML addenda
audience: Application User
ms.search.region: Mexico
---

# (MEX) Customize Microsoft Dynamics AX to include the XML addenda element for a customer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can customize Microsoft Dynamics AX to include the XML addenda element for a customer. The addenda element is an optional element in the XML schema definition (XSD) provided by the Servicio de Administración Tributaria (SAT). The addenda element contains open syntax that you can use to include specific commercial information in electronic invoices, based on the customer’s requirements. Because there is no specific format defined for the addenda element, it is not validated by the SAT.

You can customize the EInvoiceXMLFormat\_MX class to include the addenda element and set the addenda attribute that contains specific commercial information based on the customer’s requirements. The EInvoiceXMLFormat\_MX class designs the nodes, subnodes, and attributes that the XSD must have to generate the .xml files of electronic invoices.

On the Menu bar, click **Windows**, and then click **New Development Workspace**. On the toolbar, click the **Project** icon, and then click **Shared Projects** \> **MX\_Einvoice** to open the EInvoiceXMLFormat\_MX class. This class retrieves the electronic invoice information from the classes, EInvoiceJourBaseMap\_MX (the electronic invoice header), and EInvoiceTransBaseMap\_MX (the electronic invoice lines). To retrieve this information, the EInvoiceXMLFormat\_MX class interacts with a set of abstract classes.

The electronic invoices are generated from the CustInvoiceJour and ProjInvoiceJour tables. Therefore, you must include the newNode attribute in the following classes to allow the EInvoiceXMLFormat\_MX class to retrieve the electronic invoice information:

  - EInvoiceJourBaseMap\_MX

  - CustInvoiceJourEInvoiceJourMap\_MX

  - ProjInvoiceJourEInvoiceJourMap\_MX


> [!NOTE]
> <P>Before you customize these classes, verify that the newNode attribute is not included in these classes.</P>



1.  In the EInvoiceXMLFormat\_MX class, create a create\_AddendaElement element that returns an XML element, and then set the newNode attribute. You can use the following source code to create the element and set the attribute.
    
        protected XmlElement create_AddendaElement()
        {
            XmlElement addendaElement;
        
            addendaElement  = this.createElement('Addenda');
            addendaElement.setAttribute('newNode',  eInvoiceJourMap.addendanewNodeInformation());
        // Note how the information is retrieved.
        
            return addendaElement;
        }

2.  Add the create\_AddendaElement element to the createXmlDocumentInvoiceJour method. This method creates the XML file of the electronic invoice. You can use the following source code to customize the createXmlDocumentInvoiceJour method.
    
        protected XmlElement createXmlDocumentInvoiceJour()
        {
            XmlElement      comprobanteElement;
            XmlElement      emissorElement;
            XmlElement      receptorElement;
            XMLElement      addendaElement;
            ;
            comprobanteElement  = this.create_ComprobanteElement();
            emissorElement      = this.create_EmisorElement();
            receptorElement     = this.create_ReceptorElement();
        
        
            comprobanteElement.appendChild(emissorElement);
            comprobanteElement.appendChild(receptorElement);
        
        
            this.createLines(comprobanteElement);
        
            this.createTaxesLines(comprobanteElement);
        
            addendaElement      = this.create_AddendaElement();
            comprobanteElement.appendChild(addendaElement);
        
        
            return comprobanteElement;
        }

3.  In the EInvoiceJourBaseMap\_MX class, create a newNodeInformation abstract method. You can use the following source code to create the abstract method.
    
        /// <summary>
        /// Returns the newNode information related to the posted document.
        /// </summary>
        /// <returns>
        /// Returns the newNode information related to the posted document.
        /// </returns>
        public abstract str newNodeInformation()
        {
        }

4.  In the CustInvoiceJourEInvoiceJourMap\_MX class, include the newNodeInformation abstract method. You can use the following source code to include the abstract method.
    
        /// <summary>
        /// Returns the newNode information related to CustInvoiceJour.
        /// </summary>
        /// <returns>
        /// Returns newNode information related to CustInvoiceJour.
        /// </returns>
        public str newNodeInformation()
        {
            return custInvoicejour. newNodeInformation;
        }

5.  In the ProjInvoiceJourEInvoiceJourMap\_MX class, include the newNodeInformation abstract method. You can use the following source code to include the abstract method.
    
        /// <summary>
        /// Returns the newNode information related to ProjInvoiceJour.
        /// </summary>
        /// <returns>
        /// Returns the newNode information related to ProjInvoiceJour.
        /// </returns>
        public str newNodeInformation()
        {
            return projInvoiceJour. newNodeInformation;
        }

After you customize Microsoft Dynamics AX, you can generate the following .xml file that includes the addenda element.

    <?xml version="1.0" encoding="UTF-8"?>
    <Comprobante
        …
        <Emisor
        ...
        </Emisor>
        <Receptor
        ...
        </Receptor>
        <Conceptos>
            <Concepto
            ...
            </Concepto>
        </Conceptos>
        <Impuestos
        ...
        </Impuestos>
        <Addenda newNode=""
        </Addenda>
    </Comprobante>

  


