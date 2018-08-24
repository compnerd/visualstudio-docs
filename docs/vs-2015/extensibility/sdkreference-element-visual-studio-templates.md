---
title: "SDKReference Element (Visual Studio Templates) | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-general"
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 72c8b352-0b7a-42b3-ba5d-2a2d1e90c34b
caps.latest.revision: 6
ms.author: "gregvanl"
manager: "ghogen"
---
# SDKReference Element (Visual Studio Templates)
[!INCLUDE[vs2017banner](../includes/vs2017banner.md)]

The latest version of this topic can be found at [SDKReference Element (Visual Studio Templates)](https://docs.microsoft.com/visualstudio/extensibility/sdkreference-element-visual-studio-templates).  
  
Specifies that the item template uses an SDK reference.  
  
## Syntax  
  
```xml  
<VSTemplate>      
    <TemplateContent>          
        <References>              
            <Reference>  
                <SDKReference>SDKname</SDKReference>  
```  
  
## Attributes and Elements  
 The following sections describe attributes, child elements, and parent elements.  
  
### Attributes  
 None.  
  
### Child Elements  
 None.  
  
### Parent Elements  
  
|Element|Description|  
|-------------|-----------------|  
|[Reference](../extensibility/reference-element-visual-studio-templates.md)|Specifies the assembly reference to add when the item is added to a project.|  
  
## Text Value  
 A text value is required.  
  
## Remarks  
 This text specifies the SDK reference to add to a project when the item template is instantiated.  
  
```xml  
<VSTemplate Version="3.0.0" xmlns="http://schemas.microsoft.com/developer/vstemplate/2005" Type="Item">   
    <TemplateData> . . . </TemplateData>   
    <TemplateContent>   
        <References>   
            <Reference>   
                <SDKReference>Microsoft Visual C++ Runtime Package, Version=11.0.0.0</SDKReference>  
...  
```  
  
## See Also  
 [References Element (Visual Studio Templates)](../extensibility/references-element-visual-studio-templates.md)   
 [Reference Element (Visual Studio Templates)](../extensibility/reference-element-visual-studio-templates.md)   
 [Creating Project and Item Templates](../ide/creating-project-and-item-templates.md)   
 [Visual Studio Template Schema Reference](../extensibility/visual-studio-template-schema-reference.md)
