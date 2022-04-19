---
title: Learn about the ConnectionInfo element (MessageType complexType) schema C
TOCTitle: ConnectionInfo element
ms:assetid: 145a77b2-1939-4d7c-3e12-113646a74947
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404725(v=office.16)
ms:contentKeyID: 68250639
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Learn about the ConnectionInfo element (MessageType complexType) schema C

(MessageType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Connection-related properties regardless of the media stream and end points.  

## Element information

<table>

<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p><a href="connectioninfotype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">ConnectionInfoType</a></p></td>
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

    <xs:element name="ConnectionInfo"  type="ConnectionInfoType">
    
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
<td><p><a href="lyncdiagnostics-element-skype-for-business-sdn-interface-2-2-schema-c.md">LyncDiagnostics</a></p></td>
<td><p><a href="messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">MessageType</a></p></td>
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
<td><p><a href="callid-element-connectioninfotype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">CallId</a></p></td>
<td><p>xs:string</p></td>
<td><p>Unique identifier for the SIP call. This field should be used to correlate messages referring to the same call.</p></td>
</tr>
<tr class="even">
<td><p><a href="conferenceid-element-connectioninfotype-complextype-skype-sdn-2-2-c.md">ConferenceId</a></p></td>
<td><p>xs:string</p></td>
<td><p>Identifier to correlate call legs that belong to the same conference.</p></td>
</tr>
<tr class="odd">
<td><p><a href="conferenceuri-element-connectioninfotype-complextype-skype-sdn-2-2-c.md">ConferenceURI</a></p></td>
<td><p>xs:anyURI</p></td>
<td><p>(Deprecated - use ConferenceId instead) Sip URI used for the conference. This field is obfuscated unless hidepii is set to false in configuration.</p></td>
</tr>
<tr class="even">
<td><p><a href="connectivity-element-connectioninfotype-complextype-skype-sdn-2-2-c.md">Connectivity</a></p></td>
<td><p>xs:string</p></td>
<td><p>(Obsolete) The inclusion of Relay Ip/port indicates that a particular endpoint uses a media relay (edge server) and if not access the remote address directly. It is provided only in QualityUpdate events.</p></td>
</tr>
<tr class="odd">
<td><p><a href="conversationid-element-connectioninfotype-complextype-skype-sdn-2-2-c.md">ConversationId</a></p></td>
<td><p>xs:string</p></td>
<td><p>Identifier to correlate different SIP calls involved in the same conversation. In some cases Skype for Business uses different SIP calls for different modalities. This identifier permits correlating these SIP calls in the same conversation.</p></td>
</tr>
<tr class="even">
<td><p><a href="correlationid-element-connectioninfotype-complextype-skype-sdn-2-2-c.md">CorrelationId</a></p></td>
<td><p>xs:string</p></td>
<td><p>Identifier to correlate two SIP calls where mediation server is involved. Both SIP calls belong to the same conversation.</p></td>
</tr>
<tr class="odd">
<td><p><a href="cseq-element-connectioninfotype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">CSEQ</a></p></td>
<td><p>xs:string</p></td>
<td><p>Call sequence number as part of SIP standard that needs to be used to filter for unrelated error messages. This field is not provided for QualityUpdates.</p></td>
</tr>
<tr class="even">
<td><p><a href="endtime-element-connectioninfotype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">EndTime</a></p></td>
<td><p>xs:dateTime</p></td>
<td><p>Denotes then time when the conversation ended. It is provided only in QualityUpdate events.</p></td>
</tr>
<tr class="odd">
<td><p><a href="mediabypass-element-connectioninfotype-complextype-skype-sdn-2-2-c.md">MediaBypass</a></p></td>
<td><p>xs:boolean</p></td>
<td><p>Denotes media bypass. It is provided only in QualityUpdate message when mediabypass was part of the call.</p></td>
</tr>
<tr class="even">
<td><p><a href="mediationserverlegposition-element-connectioninfotype-complextype-skype-sdn-2-2-c.md">MediationServerLegPosition</a></p></td>
<td><p>xs:string</p></td>
<td><p>Indicates whether the call was incoming to a mediation server or outgoing from the medation server. It is provided only in QualityUpdate events.</p></td>
</tr>
<tr class="odd">
<td><p><a href="sourcepool-element-connectioninfotype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">SourcePool</a></p></td>
<td><p>xs:string</p></td>
<td><p>Name of the Skype for Business pool this message originated. If a QualityUpdate message is merged and originated from two pools only one is included here. Currently, the FQDN of one sourcepool is provided, expect a comma delimited list in future releases.</p></td>
</tr>
<tr class="even">
<td><p><a href="starttime-element-connectioninfotype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">StartTime</a></p></td>
<td><p>xs:dateTime</p></td>
<td><p>Denotes the time when the conversation started. It is provided only in QualityUpdate events.</p></td>
</tr>
<tr class="odd">
<td><p><a href="timestamp-element-connectioninfotype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">TimeStamp</a></p></td>
<td><p>xs:dateTime</p></td>
<td><p>UTC time when the report is processed.</p></td>
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
<td><p>Originator</p></td>
<td><p>xs:string</p></td>
<td><p>optional</p></td>
<td><p>Indicates source endpoint (Endpoint Id) that provided the quality metrics used for this report. It is provided only in QualityUpdate events.</p></td>
<td><p>Values of the xs:string type.</p></td>
</tr>
</tbody>
</table>

