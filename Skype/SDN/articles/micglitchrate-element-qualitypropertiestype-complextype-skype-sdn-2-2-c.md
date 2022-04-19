---
title: MicGlitchRate element (QualityPropertiesType complexType), schema C
TOCTitle: MicGlitchRate element
description: Information about the MicGlitchRate element, schema C. Average glitches per five minutes for the microphone capture.
ms:assetid: 33b1d78d-b885-fb91-f8a3-9ee648d405fd
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404793(v=office.16)
ms:contentKeyID: 68250704
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# MicGlitchRate element, schema C 

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Average glitches per five minutes for the microphone capture. For good quality this should be less than one per five minutes. This will not be reported by audio/video conferencing servers, mediation servers, or IP phones.

**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>Not defined</p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.C.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="MicGlitchRate" >
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>
<thead>
<tr class="header">
<th><p>Element</p></th>
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="properties-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Properties</a></p></td>
<td><p><a href="qualitypropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">QualityPropertiesType</a></p></td>
<td><p>Properties of the media stream, including a selected set of quality metrics reported and thresholds that are used to determine a bad call.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

