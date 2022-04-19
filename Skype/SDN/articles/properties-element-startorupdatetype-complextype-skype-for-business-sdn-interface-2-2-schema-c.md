---
title: Properties element (StartOrUpdateType complexType) (Schema C)
TOCTitle: Properties element (StartOrUpdateType complexType)
ms:assetid: 02bbebb5-4c55-7fe0-59b7-013bd0697c49
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404810(v=office.16)
ms:contentKeyID: 68250722
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Properties element (Schema C)

(StartOrUpdateType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Properties of the started or updated media stream.

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
<td><p><a href="startpropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">StartPropertiesType</a></p></td>
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

    <xs:element name="Properties"  type="StartPropertiesType" minOccurs="0">
    
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
<td><p><a href="start-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Start</a></p></td>
<td><p><a href="startorupdatetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">StartOrUpdateType</a></p></td>
<td><p>Event that a media stream is started. Every Start element contains a report about a particular media stream. This event is raised when the call is established, i.e., when the call is picked up and the SIP INVITE is answered with a 200 OK response.</p></td>
</tr>
<tr class="even">
<td><p><a href="update-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Update</a></p></td>
<td><p><a href="startorupdatetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">StartOrUpdateType</a></p></td>
<td><p>Event that a media stream previously started has been updated. This event is raised when an update to core parameters of call have changed and the change is established, i.e., when the request is answered with a 200 OK response.</p></td>
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
<td><p><a href="bandwidth-element-startpropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Bandwidth</a></p></td>
<td><p><a href="bandwidthtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">BandwidthType</a></p></td>
<td><p>Describes the maximum and average amount of bandwidth needed by this stream. It takes the possible codecs and stream multiplexing into account.</p></td>
</tr>
<tr class="even">
<td><p><a href="codec-element-startpropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Codec</a></p></td>
<td><p><a href="codectype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">CodecType</a></p></td>
<td><p>Codec and estimates for the bandwidth that the codecs will use. This list contains all codecs that are agreed upon by the two endpoints. Both end-points may decide to switch among these codecs at any time (without additional signalling).</p></td>
</tr>
<tr class="odd">
<td><p><a href="protocol-element-startpropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Protocol</a></p></td>
<td><p>xs:string</p></td>
<td><p>Transmission protocol of the media stream such as TCP or UDP.</p></td>
</tr>
</tbody>
</table>


### Attributes

None.

