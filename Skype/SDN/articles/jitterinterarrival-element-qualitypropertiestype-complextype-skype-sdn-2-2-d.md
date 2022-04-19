---
title: JitterInterArrival element (QualityPropertiesType complexType) (Schema D)
TOCTitle: JitterInterArrival element
ms:assetid: 31844ffc-0d7f-0012-5a0b-c98594657e0c
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170906(v=office.16)
ms:contentKeyID: 65855480
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# JitterInterArrival element (Schema D)

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Average inter-arrival jitter, as specified in \[RFC3550\] section 6.4.1. This metric is reported for all available modalities/media types. (ms)


**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>

<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>xs:unsignedInt</p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="JitterInterArrival"  type="xs:unsignedInt">
    
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
<td><p><a href="properties-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Properties</a></p></td>
<td><p><a href="qualitypropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityPropertiesType</a></p></td>
<td><p>Properties of the media stream, including a selected set of quality metrics reported and thresholds that are used to determine a bad call.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

