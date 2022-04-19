---
title: EchoEventCauses element (QualityPropertiesType complexType) Schema C
TOCTitle: EchoEventCauses element
ms:assetid: 0754245f-61d2-9af9-d11e-d1606b811c39
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404750(v=office.16)
ms:contentKeyID: 68250663
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# EchoEventCauses element Schema C 

(QualityPropertiesType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Reasons of device echo detection and reported for audio streams when available. The causes are coded with the following bit flags: "0x01" - Sample timestamps from capture or render device were poor quality. "0x04" - High level of echo remained after echo cancellation. "0x10" - Signal from capture device had significant instances of maximum signal level.

**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
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

    <xs:element name="EchoEventCauses" >
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
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

