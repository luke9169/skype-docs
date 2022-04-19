---
title: MessageProperties complexType (Schema D)
TOCTitle: MessageProperties complexType
ms:assetid: f7c0c752-ecdc-55bc-dfe0-06998ec1e06f
ms:mtpsurl: https://msdn.microsoft.com/library/Mt171066(v=office.16)
ms:contentKeyID: 65855639
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# MessageProperties complexType (Schema D)

(Skype for Business SDN Interface 2.2, Schema "D")


**In this article**  
Type information  
Definition  
Elements and attributes  

## Type information

<table>
<colgroup>
<col />
<col />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
<tr class="odd">
<td><p><strong>Extension base</strong></p></td>
<td><p>None</p></td>
</tr>
</tbody>
</table>


## Definition

```xml
      <xs:complexType name="MessageProperties">
      </xs:complexType>
      
```

## Elements and attributes

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
<td><p><a href="msdiagnostics-element-messageproperties-complextype-skype-sdn-2-2-d.md">MSDiagnostics</a></p></td>
<td><p>xs:string</p></td>
<td><p>Skype for Business-specific diagnostics message.</p></td>
</tr>
<tr class="even">
<td><p><a href="msdiagnosticsclient-element-messageproperties-complextype-skype-sdn-2-2-d.md">MSDiagnosticsClient</a></p></td>
<td><p>xs:string</p></td>
<td><p>Skype for Business-specific diagnostics message from the client.</p></td>
</tr>
<tr class="odd">
<td><p><a href="msdiagnosticspublic-element-messageproperties-complextype-skype-sdn-2-2-d.md">MSDiagnosticsPublic</a></p></td>
<td><p>xs:string</p></td>
<td><p>Skype for Business-specific public diagnostics message.</p></td>
</tr>
<tr class="even">
<td><p><a href="responsecode-element-messageproperties-complextype-skype-sdn-2-2-d.md">ResponseCode</a></p></td>
<td><p><a href="responsecodetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">ResponseCodeType</a></p></td>
<td><p>Message describing the error.</p></td>
</tr>
</tbody>
</table>


### Attributes

None.

