---
title: "Implementing a Delivery Extension | Microsoft Docs"
ms.custom: ""
ms.date: "03/16/2017"
ms.prod: reporting-services
ms.prod_service: "reporting-services-native"
ms.service: ""
ms.component: "extensions"
ms.reviewer: ""
ms.suite: "pro-bi"
ms.technology: 


ms.tgt_pltfrm: ""
ms.topic: "reference"
applies_to: 
  - "SQL Server 2016 Preview"
helpviewer_keywords: 
  - "delivery [Reporting Services]"
  - "custom delivery extensions [Reporting Services]"
  - "extensions [Reporting Services], delivery"
  - "delivery extensions [Reporting Services]"
ms.assetid: 600cd229-efcd-480e-8c95-3c3c39ff4e7a
caps.latest.revision: 32
author: "guyinacube"
ms.author: "asaxton"
manager: "erikre"
ms.workload: "Inactive"
---
# Implementing a Delivery Extension
  [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)] [!INCLUDE[ssRSnoversion](../../../includes/ssrsnoversion-md.md)] enables users to create and publish reports that, once created and published, can be delivered to various locations. In addition, [!INCLUDE[ssRSnoversion](../../../includes/ssrsnoversion-md.md)] includes several delivery extensions and a delivery API that enable developers to create additional delivery extensions to further extend the functionality of delivery in [!INCLUDE[ssRSnoversion](../../../includes/ssrsnoversion-md.md)].  
  
 For a sample implementation of a delivery extension, see [SQL Server Reporting Services Product Samples](http://go.microsoft.com/fwlink/?LinkId=177889).  
  
## In This Section  
 [Delivery Extensions Overview](../../../reporting-services/extensions/delivery-extension/delivery-extensions-overview.md)  
 Introduces how to write a custom delivery extension for [!INCLUDE[ssRSnoversion](../../../includes/ssrsnoversion-md.md)].  
  
 [Preparing to Implement a Delivery Extension](../../../reporting-services/extensions/delivery-extension/preparing-to-implement-a-delivery-extension.md)  
 Describes the interfaces and classes available when implementing an [!INCLUDE[ssRSnoversion](../../../includes/ssrsnoversion-md.md)] delivery extension, as well as issues to consider before implementation.  
  
 [Creating a Delivery Extension Library](../../../reporting-services/extensions/delivery-extension/creating-a-delivery-extension-library.md)  
 Describes assigning a namespace for your [!INCLUDE[ssRSnoversion](../../../includes/ssrsnoversion-md.md)] delivery extension and compiling your delivery extension into a library DLL.  
  
 [Implementing the IDeliveryExtension Interface for a Delivery Extension](../../../reporting-services/extensions/delivery-extension/implementing-the-ideliveryextension-interface-for-a-delivery-extension.md)  
 Describes the attributes of a delivery extension, and how to implement your own delivery extension class.  
  
 [Using a Notification Class for a Delivery Extension](../../../reporting-services/extensions/delivery-extension/using-a-notification-class-for-a-delivery-extension.md)  
 Describes the attributes of a **Notification** class and how to use it in your delivery extension implementation.  
  
 [Using the Setting Class for a Delivery Extension](../../../reporting-services/extensions/delivery-extension/using-the-setting-class-for-a-delivery-extension.md)  
 Describes the attributes of a **Setting** class and how to use it in your delivery extension implementation.  
  
 [Using the IDeliveryReportServerInformation Interface for a Delivery Extension](../../../reporting-services/extensions/delivery-extension/using-the-ideliveryreportserverinformation-interface-for-a-delivery-extension.md)  
 Describes the attributes of a **IDeliveryReportServerInformation** interface and how to use it in your delivery extension implementation.  
  
 [Using the Report Class for a Delivery Extension](../../../reporting-services/extensions/delivery-extension/using-the-report-class-for-a-delivery-extension.md)  
 Describes the attributes of a **Report** class and how to use it in your delivery extension implementation.  
  
 [Using the RenderedOutputFile Class for a Delivery Extension](../../../reporting-services/extensions/delivery-extension/using-the-renderedoutputfile-class-for-a-delivery-extension.md)  
 Describes the attributes of a **RenderedOutputFile** class and how to use it in your delivery extension implementation.  
  
 [Implementing the ISubscriptionBaseUIUserControl Interface for a Delivery Extension](../../../reporting-services/extensions/delivery-extension/implementing-the-isubscriptionbaseuiusercontrol-interface.md)  
 Describes the attributes of a delivery extension user control and how to implement your own user interface for a subscription.  
  
 [Deploying a Delivery Extension](../../../reporting-services/extensions/delivery-extension/deploying-a-delivery-extension.md)  
 Describes how to deploy your delivery extension.  
  
 [Debugging Delivery Extension Code](../../../reporting-services/extensions/delivery-extension/debugging-delivery-extension-code.md)  
 Describes how to debug code in your delivery extension.  
  
 [Removing a Delivery Extension](../../../reporting-services/extensions/delivery-extension/removing-a-delivery-extension.md)  
 Describes how to remove a delivery extension from a report server.  
  
## See Also  
 [Reporting Services Extensions](../../../reporting-services/extensions/reporting-services-extensions.md)   
 [Reporting Services Extension Library](../../../reporting-services/extensions/reporting-services-extension-library.md)  
  
  
