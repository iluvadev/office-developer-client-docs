---
title: "PidTagOriginalDeliveryTime Canonical Property"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- MAPI.PidTagOriginalDeliveryTime
api_type:
- COM
ms.assetid: 700ccfc9-493a-483b-aca0-aa2d7f6bb229
description: "Contains a copy of the original message's delivery date and time in a thread for Outlook 2013 and Outlook 2016."
---

# PidTagOriginalDeliveryTime Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Contains a copy of the original message's delivery date and time in a thread. 
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |PR_ORIGINAL_DELIVERY_TIME  <br/> |
|Identifier:  <br/> |0x0055  <br/> |
|Data type:  <br/> |PT_SYSTIME  <br/> |
|Area:  <br/> |General messaging  <br/> |
   
## Remarks

This property is copied from the original **PR_MESSAGE_DELIVERY_TIME** ([PidTagMessageDeliveryTime](pidtagmessagedeliverytime-canonical-property.md)) property in subsequent reply or forward operations and used in read and nonread reports. Delivery reports use the **PR_DELIVER_TIME** ([PidTagDeliverTime](pidtagdelivertime-canonical-property.md)) property instead.
  
## Related resources

### Protocol specifications

[[MS-OXPROPS]](https://msdn.microsoft.com/library/f6ab1613-aefe-447d-a49c-18217230b148%28Office.15%29.aspx)
  
> Provides references to related Exchange Server protocol specifications.
    
[[MS-OXOMSG]](https://msdn.microsoft.com/library/daa9120f-f325-4afb-a738-28f91049ab3c%28Office.15%29.aspx)
  
> Specifies the properties and operations that are permissible on email message objects.
    
### Header files

Mapidefs.h
  
> Provides data type definitions.
    
Mapitags.h
  
> Contains definitions of properties listed as alternate names.
    
## See also



[MAPI Properties](mapi-properties.md)
  
[MAPI Canonical Properties](mapi-canonical-properties.md)
  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)
  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)

