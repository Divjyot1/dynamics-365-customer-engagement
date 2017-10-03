---
title: "Section properties (Dynamics 365 Customer Engagement) | MicrosoftDocs"
ms.custom: ""
ms.date: 09/30/2017
ms.reviewer: ""
ms.service: "crm-online"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
ms.assetid: 2d3af6e9-e8a4-4129-b708-383b2740c015
caps.latest.revision: 63
ms.author: "rdubois"
manager: "brycho"
---
# Section properties

[!INCLUDE[cc-applies-to-update-9-0-0](../includes/cc_applies_to_update_9_0_0.md)]

 A section in a Dyanmics 365 Customer Engagement form occupies the space available in a tab column. Sections have a label that can be displayed and a line may be shown below the label.  
  
 Sections can have up to 4 columns and includes options for displaying how labels for fields in the section are displayed.  
  
 Headers and footers are similar to sections but cannot be removed. If they don’t contain anything they will not be shown.  
  
|Tab|Property|Description|  
|---------|--------------|-----------------|  
|**Display**|**Name**|**Required**: The unique name for the section that is used when referencing it in scripts. The name can contain only alphanumeric characters and underscores.|  
||**Label**|**Required**: The localizable label for the section visible to users.|  
||**Show the label of this section on the form**|Sections are frequently used without labels to control formatting of the fields within them.|  
||**Show a line at top of the section**|A line at the top of a section can help break up the form layout.|  
||**Field Label Width**|**Required**: Set a value between 50 and 250 to specify the space allowed for field labels.<br /><br /> Header and footer elements also have this property.|  
||**Visibility**|Showing the section is optional and can be controlled using scripts. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Visibility options](../customize/visibility-options-legacy.md)|  
||**Lock the section on the form**|This will prevent the section from accidentally being removed and prevents people from removing the contents.<br /><br /> Removing a section will not only remove the section, but also any fields within it.<br /><br /> Someone wanting to remove this section would need to change this setting before removing it.|  
|**Formatting**<br /><br /> Header and footer components also have this property.|**Layout**|Specify up to four columns to be in the section.|  
||**Field Label Alignment**|Labels for fields within the section can be aligned left, right, or center.|  
||**Field Label Position**|Labels for fields within the section can be positions on the side or on top of the fields.|  