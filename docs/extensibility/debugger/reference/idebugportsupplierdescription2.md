---
title: "IDebugPortSupplierDescription2 | Microsoft Docs"
ms.date: "11/04/2016"
ms.topic: "conceptual"
helpviewer_keywords: 
  - "IDebugPortSupplierDescription2 interface"
ms.assetid: dd19b9d6-0703-44b3-9498-cedffa0ce5b7
author: "gregvanl"
ms.author: "gregvanl"
manager: douge
ms.workload: 
  - "vssdk"
---
# IDebugPortSupplierDescription2
Enables the [!INCLUDE[vsprvs](../../../code-quality/includes/vsprvs_md.md)] UI to display text inside the **Transport Information** section of the **Attach to Process** dialog box.  
  
## Syntax  
  
```  
IDebugPortSupplierDescription2 : IUnknown  
```  
  
## Notes for Implementers  
 This interface is implemented by port suppliers.  
  
## Methods  
 The following table shows the methods of `IDebugPortSupplierDescription2`.  
  
|Method|Description|  
|------------|-----------------|  
|[GetDescription](../../../extensibility/debugger/reference/idebugportsupplierdescription2-getdescription.md)|Retrieves the description and description metadata for the port supplier.|  
  
## Requirements  
 Header: Msdbg.h  
  
 Namespace: Microsoft.VisualStudio.Debugger.Interop  
  
 Assembly: Microsoft.VisualStudio.Debugger.Interop.dll