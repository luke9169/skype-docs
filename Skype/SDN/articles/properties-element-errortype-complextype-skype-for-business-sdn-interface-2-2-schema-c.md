---
title: Properties element (ErrorType complexType) (Schema C)
TOCTitle: Properties element (ErrorType complexType)
ms:assetid: b8dc6e6d-114d-55db-a16c-0a41628f0757
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404813(v=office.16)
ms:contentKeyID: 68250725
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Properties element (Schema C)

(ErrorType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Properties of the Error.

**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<colgroup>
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p><a href="errorproperties-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">ErrorProperties</a></p></td>
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

    <xs:element name="Properties"  type="ErrorProperties" minOccurs="0">
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>
<colgroup>
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
<td><p><a href="error-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Error</a></p></td>
<td><p><a href="errortype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">ErrorType</a></p></td>
<td><p>This event is optional. Error event that a SIP dialog has failed. Error events are also sent for SIP calls that are terminated even before a media stream is started or for failed to be updated.</p></td>
</tr>
</tbody>
</table>


### Child elements

<table>
<colgroup>
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
<td><p><a href="msdiagnostics-element-errorproperties-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">MSDiagnostics</a></p></td>
<td><p>xs:string</p></td>
<td><p>More info related to the error.</p></td>
</tr>
<tr class="even">
<td><p><a href="msdiagnosticsclient-element-errorproperties-complextype-skype-sdn-2-2-c.md">MSDiagnosticsClient</a></p></td>
<td><p>xs:string</p></td>
<td><p>Info about the error related to and reported by the client.</p></td>
</tr>
<tr class="odd">
<td><p><a href="msdiagnosticspublic-element-errorproperties-complextype-skype-sdn-2-2-c.md">MSDiagnosticsPublic</a></p></td>
<td><p>xs:string</p></td>
<td><p>Public info about the error.</p></td>
</tr>
<tr class="even">
<td><p><a href="responsecode-element-errorproperties-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">ResponseCode</a></p></td>
<td><p>xs:int</p></td>
<td><p>SIP Error code.</p></td>
</tr>
<tr class="odd">
<td><p><a href="responsephrase-element-errorproperties-complextype-skype-sdn-2-2-c.md">ResponsePhrase</a></p></td>
<td><p>xs:string</p></td>
<td><p>More info related to the error.</p></td>
</tr>
</tbody>
</table>


### Attributes

None.

