---
title: Route element (QualityType complexType) (Schema D)
TOCTitle: Route element (QualityType complexType)
ms:assetid: 8c8b09b2-f976-ac9b-7c94-0daf791d03ee
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170993(v=office.16)
ms:contentKeyID: 65855568
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Route element (QualityType complexType) (Schema D)

(QualityType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Network path of the media stream only provided in Skype for Business 2013 and when the traceRoute feature is activated in Skype for Business.


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
<td><p><a href="routetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">RouteType</a></p></td>
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

    <xs:element name="Route"  type="RouteType" minOccurs="0">
    
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
<td><p><a href="incallquality-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">InCallQuality</a></p></td>
<td><p><a href="qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityType</a></p></td>
<td><p>Indicates that a significant quality related event occurred in the client. Either the quality dropped into another level or improved. There are 3 levels: Good, Poor, Bad. The media stack determines the quality level. Furthermore, this event is also sent when a video stream is deescalated. Even in an issue free network at least one IncallQuality message is sent.</p></td>
</tr>
<tr class="even">
<td><p><a href="qualityupdate-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityUpdate</a></p></td>
<td><p><a href="qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">QualityType</a></p></td>
<td><p>Specifies the event that a call has ended and contains a report of the quality metrics of individual media streams. These quality metrics for a stream may include updates provided by both endpoints which are merged.</p></td>
</tr>
</tbody>
</table>


### Child elements

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
<td><p><a href="hop-element-routetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Hop</a></p></td>
<td><p>xs:string</p></td>
<td><p>IP address of one hop (router, gateway, switch, etc) on the path from the source to the destination of the media stream.</p></td>
</tr>
</tbody>
</table>


### Attributes

None.

