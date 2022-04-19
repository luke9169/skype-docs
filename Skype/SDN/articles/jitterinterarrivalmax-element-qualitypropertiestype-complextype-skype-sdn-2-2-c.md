---
title: JitterInterArrivalMax element (QualityPropertiesType complexType) (Schema C)
TOCTitle: JitterInterArrivalMax element
ms:assetid: e1b198ae-9856-8c49-160e-4c49b0aef912
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404782(v=office.16)
ms:contentKeyID: 68250692
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# JitterInterArrivalMax element (Schema C)

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Maximum inter-arrival jitter, as specified in \[RFC3550\] section 6.4.1. This metric is reported for all modalities/media types when available. (ms)

**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>

<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>xs:string</p></td>
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

    <xs:element name="JitterInterArrivalMax"  type="xs:string">
    
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

