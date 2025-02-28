---
description: "= (Equal To) (DMX)"
title: "= (Equal To) (DMX) | Microsoft Docs"
ms.date: 02/17/2022
ms.prod: sql
ms.technology: analysis-services
ms.custom: dmx
ms.topic: reference
ms.author: owend
ms.reviewer: owend
author: minewiskan
---
# = (Equal To) (DMX)
[!INCLUDE[ssas](../includes/applies-to-version/ssas.md)]

  Performs a comparison operation that determines whether the value of one Data Mining Extensions (DMX) expression is equal to the value of another DMX expression.  
  
## Syntax  
  
```  
  
DMX_Expression = DMX_Expression   
```  
  
#### Parameters  
 *DMX_Expression*  
 A valid DMX expression.  
  
## Return Value  
 A Boolean value that contains TRUE if both parameters are non-null and the value of the first parameter is equal to the value of the second parameter. The Boolean value contains FALSE if both parameters are non-null and the value of the first parameter is not equal to the value of the second parameter. The Boolean value contains a null value if either parameter or both parameters evaluate to a null value.  
  
## See Also  
 [Comparison Operators &#40;DMX&#41;](../dmx/operators-comparison.md)   
 [Data Mining Extensions &#40;DMX&#41; Operator Reference](../dmx/data-mining-extensions-dmx-operator-reference.md)   
 [Operators &#40;DMX&#41;](../dmx/operators-dmx.md)  
  
  
