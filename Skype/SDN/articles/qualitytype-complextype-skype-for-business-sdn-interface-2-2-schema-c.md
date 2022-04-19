---
title: QualityType complexType (Schema C)
TOCTitle: QualityType complexType
ms:assetid: 0d4e9da0-f04f-12df-22d6-369443e72b03
ms:mtpsurl: https://msdn.microsoft.com/library/Mt429359(v=office.16)
ms:contentKeyID: 68250801
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# QualityType complexType (Schema C)

(Skype for Business SDN Interface 2.2, Schema "C")

**In this article**  
Type information  
Definition  
Elements and attributes  

## Type information

<table>
<tbody>
<tr class="odd">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.C.XSD</p></td>
</tr>
<tr class="odd">
<td><p><strong>Extension base</strong></p></td>
<td><p>None</p></td>
</tr>
</tbody>
</table>


## Definition

```xml
      <xs:complexType name="QualityType">
         <xs:attribute name="Type" type="xs:string" use="required"/>
  
      </xs:complexType>
      
```

## Elements and attributes

### Child elements

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
<td><p><a href="from-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">From</a></p></td>
<td><p><a href="qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">QualityEndPointType</a></p></td>
<td><p>The source of the reported media stream.</p></td>
</tr>
<tr class="even">
<td><p><a href="properties-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Properties</a></p></td>
<td><p><a href="qualitypropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">QualityPropertiesType</a></p></td>
<td><p>Properties of the media stream, including a selected set of quality metrics reported and thresholds that are used to determine a bad call.</p></td>
</tr>
<tr class="odd">
<td><p><a href="route-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Route</a></p></td>
<td><p><a href="routetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">RouteType</a></p></td>
<td><p>Network path of the media stream only provided in Skype for Business 2013 and when the traceRoute feature is activated in Skype for Business.</p></td>
</tr>
<tr class="even">
<td><p><a href="to-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">To</a></p></td>
<td><p><a href="qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">QualityEndPointType</a></p></td>
<td><p>Destination of the media stream.</p></td>
</tr>
</tbody>
</table>


### Attributes

<table>
<thead>
<tr class="header">
<th><p>Attribute</p></th>
<th><p>Type</p></th>
<th><p>Required</p></th>
<th><p>Description</p></th>
<th><p>Possible values</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Type</p></td>
<td><p>xs:string</p></td>
<td><p>required</p></td>
<td><p>Modality or media type for which the quality metrics are reported. The supported options are audio, video and applicationsharing.</p></td>
<td><p>Values of the xs:string type.</p></td>
</tr>
</tbody>
</table>

