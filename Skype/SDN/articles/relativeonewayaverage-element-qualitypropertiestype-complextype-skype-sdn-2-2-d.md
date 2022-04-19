---
title: RelativeOneWayAverage element (QualityPropertiesType complexType) Schema D
TOCTitle: RelativeOneWayAverage element
ms:assetid: c2169339-f0d9-8b20-426d-0fabc1b0463c
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170974(v=office.16)
ms:contentKeyID: 65855549
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# RelativeOneWayAverage element Schema D

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Average amount of one-way latency. Relative one-way latency measures the delay between the client and the server. This metric is only reported for application sharing streams using Skype for Business 2013. (ms)


**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>xs:double</p></td>
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

    <xs:element name="RelativeOneWayAverage"  type="xs:double">
    
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

