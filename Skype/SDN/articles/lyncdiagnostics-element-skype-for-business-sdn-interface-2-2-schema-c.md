---
title: LyncDiagnostics element, schema C
TOCTitle: LyncDiagnostics element, schema C
description: Information about the LyncDiagnostics element, the root element for output from the Skype for Business SDN Manager.
ms:assetid: 2b7bc3eb-cb1d-d725-4432-6fe913ecf3cf
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404787(v=office.16)
ms:contentKeyID: 68250697
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# LyncDiagnostics element 

(Skype for Business SDN Interface 2.2, Schema "C")

The root element for output from the Skype for Business SDN Manager.

**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p><a href="messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">MessageType</a></p></td>
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

    <xs:element name="LyncDiagnostics"  type="MessageType">
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

None.

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
<td><p><a href="bye-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Bye</a></p></td>
<td><p><a href="byetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">ByeType</a></p></td>
<td><p>Event that a Sip call has ended and all media stream terminated.</p></td>
</tr>
<tr class="even">
<td><p><a href="connectioninfo-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">ConnectionInfo</a></p></td>
<td><p><a href="connectioninfotype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">ConnectionInfoType</a></p></td>
<td><p>Connection-related properties regardless of the media stream and end points.</p></td>
</tr>
<tr class="odd">
<td><p><a href="ended-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Ended</a></p></td>
<td><p><a href="endedtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">EndedType</a></p></td>
<td><p>Event that a Sip call has ended and all media stream terminated.</p></td>
</tr>
<tr class="even">
<td><p><a href="error-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Error</a></p></td>
<td><p><a href="errortype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">ErrorType</a></p></td>
<td><p>This event is optional. Error event that a SIP dialog has failed. Error events are also sent for SIP calls that are terminated even before a media stream is started or for failed to be updated.</p></td>
</tr>
<tr class="odd">
<td><p><a href="incallquality-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">InCallQuality</a></p></td>
<td><p><a href="qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">QualityType</a></p></td>
<td><p>Indicates that a significant quality related event occurred in the client. Either the quality dropped into another level or improved. There are 3 levels: Good, Poor, Bad. The media stack determines the quality level. Furthermore, this event is also sent when a video stream is deescalated. Even in an issue free network at least one IncallQuality message is sent.</p></td>
</tr>
<tr class="even">
<td><p><a href="invite-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Invite</a></p></td>
<td><p><a href="invitetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">InviteType</a></p></td>
<td><p>Event that an endpoint attempts to establish a call. DialogListener will include this element in its output if the sendcallinvites entry is set to True (activated) in the DialogListener configuration file. In addition, DialogListener will also notifies any SIP Invite messages (re-invites), not just the first one. Following this message Earlymedia may be flowing but this element is not intended to report on early media streams.</p></td>
</tr>
<tr class="odd">
<td><p><a href="properties-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Properties</a></p></td>
<td><p><a href="messageproperties-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">MessageProperties</a></p></td>
<td><p>Details of the Error or reason for ending the streams.</p></td>
</tr>
<tr class="even">
<td><p><a href="qualityupdate-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">QualityUpdate</a></p></td>
<td><p><a href="qualitytype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">QualityType</a></p></td>
<td><p>Specifies the event that a call has ended and contains a report of the quality metrics of individual media streams. These quality metrics for a stream may include updates provided by both endpoints which are merged.</p></td>
</tr>
<tr class="odd">
<td><p><a href="rawsdp-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">RawSDP</a></p></td>
<td><p>xs:string</p></td>
<td><p>Raw Session Description Protocol (SDP) data that is included as the payload of the underlying SIP messages of the Invite, LRSInvite and StartOrUpdate type, if the sendrawsdp entry is set to True in the DialogListener configuration file.</p></td>
</tr>
<tr class="even">
<td><p><a href="route-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Route</a></p></td>
<td><p><a href="routetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">RouteType</a></p></td>
<td><p>Network path of the media stream only provided in Skype for Business 2013 and when the traceRoute feature is activated in Skype for Business.</p></td>
</tr>
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
<td><p>Version</p></td>
<td><p>xs:string</p></td>
<td><p>optional</p></td>
<td><p>Version number of this data structure. It provides a simple distinction between LyncDiagnostics messages formats. LyncDiagnostics message matching to this xsd use Version C.</p></td>
<td><p>Values of the xs:string type.</p></td>
</tr>
</tbody>
</table>

