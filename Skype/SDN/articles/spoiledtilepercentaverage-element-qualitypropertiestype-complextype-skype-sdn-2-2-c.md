---
title: SpoiledTilePercentAverage element (QualityPropertiesType complexType) (Schema C) 
TOCTitle: SpoiledTilePercentAverage element
ms:assetid: 7276321f-18e1-1c58-30d9-a2d381b2cfe0
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404851(v=office.16)
ms:contentKeyID: 68250763
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# SpoiledTilePercentAverage element (Schema C)

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Average percentage of the content that did not reach the viewer but was instead discarded and overwritten by fresh content. When available, this metric is only reported for application sharing streams and only for Skype for Business 2013. (percent)

**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<colgroup>
<col />
<col />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>xs:decimal</p></td>
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

    <xs:element name="SpoiledTilePercentAverage"  type="xs:decimal">
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>
<colgroup>
<col />
<col />
<col />
</colgroup>
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

