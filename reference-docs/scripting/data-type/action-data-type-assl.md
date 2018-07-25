---
title: "Action Data Type (ASSL) | Microsoft Docs"
ms.date: 05/03/2018
ms.prod: sql
ms.technology: analysis-services
ms.custom: assl
ms.topic: reference
ms.author: owend
ms.reviewer: owend
author: minewiskan
manager: kfile
---
# Action Data Type (ASSL)

  Defines an abstract primitive data type that represents an action in a [Cube](../objects/cube-element-assl.md) element or a [Perspective](../objects/perspective-element-assl.md) element.  
  
## Syntax  
  
```xml  
  
<Action>  
   <Name>...</Name>  
   <ID>...</ID>  
   <Caption>...</Caption>  
      <CaptionIsMdx>...</CaptionIsMdx>  
      <Translations>...</Translations>  
   <TargetType>...</TargetType>  
   <Target>...</Target>  
   <Condition>...</Condition>  
   <Type>...</Type>  
   <Invocation>...</Invocation>  
   <Application>...</Application>  
      <Description>...</Description>  
      <Annotations>...</Annotations>  
</Action>  
```  
  
## Data Type Characteristics  
  
|Characteristic|Description|  
|--------------------|-----------------|  
|Base data types|None|  
|Derived data types|[DrillThroughAction](drillthroughaction-data-type-assl.md), [ReportAction](reportaction-data-type-assl.md), [StandardAction](standardaction-data-type-assl.md)|  
  
## Data Type Relationships  
  
|Relationship|Element|  
|------------------|-------------|  
|Parent elements|[Actions](../collections/actions-element-assl.md)|  
|Child elements|[Annotations](../collections/annotations-element-assl.md), [Application](../properties/application-element-assl.md), [Caption](../properties/caption-element-assl.md), [CaptionIsMdx](../properties/captionismdx-element-assl.md), [Condition](../properties/condition-element-assl.md), [Description](../properties/description-element-assl.md), [ID](../properties/id-element-assl.md), [Invocation](../properties/invocation-element-assl.md), [Name](../properties/name-element-assl.md), [Target](../properties/target-element-assl.md), [TargetType](../properties/targettype-element-assl.md), [Translations](../collections/translations-element-assl.md), [Type](../properties/type-element-action-assl.md)|  
|Derived elements|[DrillThroughAction](drillthroughaction-data-type-assl.md), [ReportAction](reportaction-data-type-assl.md), [StandardAction](standardaction-data-type-assl.md)|  
  
## Remarks  
 For more information about actions, see [Actions &#40;Analysis Services - Multidimensional Data&#41;](../../../analysis-services/multidimensional-models/actions-analysis-services-multidimensional-data.md).  
  
 The corresponding element in the Analysis Management Objects (AMO) object model is <xref:Microsoft.AnalysisServices.Action>.  
  
## See Also  
 [Cube Element &#40;ASSL&#41;](../objects/cube-element-assl.md)   
 [Perspective Element &#40;ASSL&#41;](../objects/perspective-element-assl.md)   
 [PerspectiveAction Data Type &#40;ASSL&#41;](perspectiveaction-data-type-assl.md)   
 [Analysis Services Scripting Language XML Data Types &#40;ASSL&#41;](analysis-services-scripting-language-xml-data-types-assl.md)  
  
  
