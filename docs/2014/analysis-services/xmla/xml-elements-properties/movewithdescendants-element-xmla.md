---
title: "MoveWithDescendants Element (XMLA) | Microsoft Docs"
ms.custom: ""
ms.date: "03/06/2017"
ms.prod: "sql-server-2014"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "analysis-services"
  - "docset-sql-devref"
ms.tgt_pltfrm: ""
ms.topic: "reference"
api_name: 
  - "MoveWithDescendants Element"
api_location: 
  - "http://schemas.microsoft.com/analysisservices/2003/engine"
topic_type: 
  - "apiref"
f1_keywords: 
  - "microsoft.xml.analysis.movewithdescendants"
  - "http://schemas.microsoft.com/analysisservices/2003/engine#MoveWithDescendants"
  - "urn:schemas-microsoft-com:xml-analysis#MoveWithDescendants"
helpviewer_keywords: 
  - "MoveWithDescendants element"
ms.assetid: d02285b6-1801-4da9-8e2b-9ab008e25558
caps.latest.revision: 11
author: minewiskan
ms.author: owend
manager: craigg
---
# MoveWithDescendants Element (XMLA)
  Indicates whether the descendants of attribute members are also updated by the parent [Update](../xml-elements-commands/update-element-xmla.md) command.  
  
## Syntax  
  
```xml  
  
<Update>  
   ...  
   <MoveWithDescendants>...</MoveWithDescendants>  
   ...  
</Update>  
```  
  
## Element Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Data type and length|Boolean|  
|Default value|False|  
|Cardinality|0-1: Optional element that can occur once and only once.|  
  
## Element Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|[Update](../xml-elements-commands/update-element-xmla.md)|  
|Child elements|None|  
  
## Remarks  
 The `MoveWithDescendants` element determines whether the `Update` command should not just update the attribute members identified by the [Attributes](attributes-element-xmla.md) element, but also that the descendants of those attribute members are to be updated as well.  
  
> [!NOTE]  
>  This element applies only to attribute members in parent-child hierarchies.  
  
 For more information about updating members, see [Inserting, Updating, and Dropping Members &#40;XMLA&#41;](../../multidimensional-models-scripting-language-assl-xmla/inserting-updating-and-dropping-members-xmla.md).  
  
## See Also  
 [Properties &#40;XMLA&#41;](xml-elements-properties.md)  
  
  
