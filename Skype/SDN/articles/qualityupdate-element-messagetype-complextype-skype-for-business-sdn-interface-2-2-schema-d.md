---
title: QualityUpdate element (MessageType complexType) (Schema D)
TOCTitle: QualityUpdate element
ms:assetid: 5949a98c-b419-789f-566c-97b56fca0416
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170952(v=office.16)
ms:contentKeyID: 65855527
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# QualityUpdate element (Schema D)

(MessageType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Specifies the event that a call has ended and contains a report of the quality metrics of individual media streams. These quality metrics for a stream may include updates provided by both endpoints which are merged.


**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p><a href="qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityType</a></p></td>
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

    <xs:element name="QualityUpdate"  type="QualityType">
    
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
<td><p><a href="lyncdiagnostics-element-skype-for-business-sdn-interface-2-2-schema-d.md">LyncDiagnostics</a></p></td>
<td><p><a href="messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">MessageType</a></p></td>
<td><p>The root element for output from the Skype for Business SDN Manager.</p></td>
</tr>
</tbody>
</table>


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
<td><p><a href="from-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">From</a></p></td>
<td><p><a href="qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityEndPointType</a></p></td>
<td><p>The source of the reported media stream.</p></td>
</tr>
<tr class="even">
<td><p><a href="properties-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Properties</a></p></td>
<td><p><a href="qualitypropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityPropertiesType</a></p></td>
<td><p>Properties of the media stream, including a selected set of quality metrics reported and thresholds that are used to determine a bad call.</p></td>
</tr>
<tr class="odd">
<td><p><a href="route-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Route</a></p></td>
<td><p><a href="routetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">RouteType</a></p></td>
<td><p>Network path of the media stream only provided in Skype for Business 2013 and when the traceRoute feature is activated in Skype for Business.</p></td>
</tr>
<tr class="even">
<td><p><a href="to-element-qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">To</a></p></td>
<td><p><a href="qualityendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityEndPointType</a></p></td>
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
<td><p><a href="connectionmodalities-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">ConnectionModalities</a></p></td>
<td><p>required</p></td>
<td><p>Modality or media type for which the quality metrics are reported. The supported options are audio, video and applicationsharing.</p></td>
<td><p>Values of the ConnectionModalities type.</p></td>
</tr>
</tbody>
</table>

