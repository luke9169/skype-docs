---
title: RDPTileProcessingLatencyBurstDensity element (QualityPropertiesType complexType), schema D
TOCTitle: RDPTileProcessingLatencyBurstDensity element
description: More information about the RDPTileProcessingLatencyBurstDensity element, schema D.
ms:assetid: f9b089bb-0197-e654-3292-6fc2e83fcbbf
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170956(v=office.16)
ms:contentKeyID: 65855530
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# RDPTileProcessingLatencyBurstDensity element, schema D

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Burst density in the processing time for remote desktop protocol (RDP) tiles. A "bursty" transmission is a transmission where data flows in unpredictable bursts as opposed to a steady stream. This metric is only reported for application sharing streams using Skype for Business 2013.


**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p><a href="nonnegativedouble-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">NonNegativeDouble</a></p></td>
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

    <xs:element name="RDPTileProcessingLatencyBurstDensity"  type="NonNegativeDouble">
    
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

