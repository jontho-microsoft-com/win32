---
title: ID Attribute (VMLFrame)(VML)
description: ID Attribute (VMLFrame)(VML)
ms.assetid: '3580fad7-b49e-44d7-b266-90fbfc2a02c9'
---

# ID Attribute (VMLFrame)(VML)

This topic describes VML, a feature that is deprecated as of Windows Internet Explorer 9. Webpages and applications that rely on VML should be [migrated to SVG](http://go.microsoft.com/fwlink/p/?LinkID=236964) or other widely supported standards.

> [!Note]  
> As of December 2011, this topic has been archived. As a result, it is no longer actively maintained. For more information, see [Archived Content](https://msdn.microsoft.com/library/hh772377). For information, recommendations, and guidance regarding the current version of Windows Internet Explorer, see [Internet Explorer Developer Center](http://go.microsoft.com/fwlink/p/?linkid=204313).

 

Defines a unique identifier for the frame. Read/write. **String**.

**Applies To**

[VMLFrame](msdn-online-vml-vmlframe-element.md)

**Tag Syntax**

&lt;v: *element* ID=" *expression* "&gt;

**Script Syntax**

*element* .ID="*expression*"

*expression*=*element*.ID

**Remarks**

Use **ID** to reference a frame. For example, you can move the frame around on the page by changing the frame position referenced by the **ID**.

*VML Standard Attribute*

**Example**

The **ID** of the frame is "frame01".


```HTML
   <v:vmlframe id="frame01" clip="True"
   origin="100pt,100pt" size="50pt,50pt"
   src="external.vml#shape01"
   style='top:160pt; left:100pt; width:50pt; height:50pt'
   </v:vmlframe>
```



 

 



