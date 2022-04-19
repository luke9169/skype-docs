---
description: Learn how to use the InstantMessagingFlowTemplate object to provide access to global configuration settings for IM flows.
title: Using an InstantMessagingFlowTemplate
TOCTitle: Using an InstantMessagingFlowTemplate
ms:assetid: 742acc0f-282c-4c39-b37f-cd371d3b84d9
ms:mtpsurl: https://msdn.microsoft.com/library/Dn466056(v=office.16)
ms:contentKeyID: 65239961
ms.date: 07/27/2015
mtps_version: v=office.16
---

# Using an InstantMessagingFlowTemplate

**Applies to**: Skype for Business 2015

The [InstantMessagingSettings](/dotnet/api/microsoft.rtc.collaboration.collaborationplatform.instantmessagingsettings) property provides access to global configuration settings for instant message (IM) flows by using an [InstantMessagingFlowTemplate](/dotnet/api/microsoft.rtc.collaboration.instantmessagingflowtemplate) object.

The following table shows the settings that can be configured for IM flows (represented by [InstantMessagingFlow](/dotnet/api/microsoft.rtc.collaboration.instantmessagingflow) objects) by using the **InstantMessagingFlowTemplate** class.

<table>
<colgroup>
<col />
<col />
</colgroup>
<thead>
<tr class="header">
<th><p>Member</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="/dotnet/api/microsoft.rtc.collaboration.instantmessagingflowtemplate.-ctor">InstantMessagingFlowTemplate()</a></p></td>
<td><p>Constructor. Create a new instance of the <strong>InstantMessagingFlowTemplate</strong> class.</p>
<p>InstantMessagingFlowTemplate()</p></td>
</tr>
<tr class="even">
<td><p><a href="/dotnet/api/microsoft.rtc.collaboration.instantmessagingflowtemplate.-ctor">InstantMessagingFlowTemplate(InstantMessagingFormat)</a></p></td>
<td><p>Constructor. Create a new instance of the <strong>InstantMessagingFlowTemplate</strong> class, specifying the formats that can be used.</p>
<p>InstantMessagingFlowTemplate(InstantMessagingFormat)</p></td>
</tr>
<tr class="odd">
<td><p><a href="/dotnet/api/microsoft.rtc.collaboration.instantmessagingflowtemplate.-ctor">InstantMessagingFlowTemplate(InstantMessagingFlowTemplate)</a></p></td>
<td><p>Constructor. Create a new instance of the <strong>InstantMessagingFlowTemplate</strong> class, using values from the specified flow template.</p>
<p>InstantMessagingFlowTemplate(InstantMessagingFlowTemplate)</p></td>
</tr>
<tr class="even">
<td><p><a href="/dotnet/api/microsoft.rtc.collaboration.instantmessagingflowtemplate.composingtimeoutvalue">ComposingTimeoutValue</a></p></td>
<td><p>Property. Gets or sets the value (in seconds) for composing time-out.</p>
<p>This property is used to control the default value used for all instant messaging flows. The default value is 3 seconds, and the maximum value is 30 seconds.</p>
<p>int ComposingTimeoutValue {get; set;}</p></td>
</tr>
<tr class="odd">
<td><p><a href="/dotnet/api/microsoft.rtc.collaboration.instantmessagingflowtemplate.messageconsumptionmode">MessageConsumptionMode</a></p></td>
<td><p>Property. Gets or sets the value that an application can use to indicate how it intends to handle instant messages.</p>
<p>The incoming messages are handled accordingly. If the application consumes messages locally, incoming messages are automatically acknowledged with a 200 response code. If the application proxies the messages, the incoming messages are automatically acknowledged with a 202 response code (if the remote supports message delivery notifications) or if the response is delayed. The application is responsible for sending a delivery notification later for every message received. The default value is <a href="/dotnet/api/microsoft.rtc.collaboration.instantmessageconsumptionmode">InstantMessageConsumptionMode</a>.<strong>ConsumedLocally</strong>.</p>
<p>InstantMessageConsumptionMode MessageConsumptionMode {get; set;}</p></td>
</tr>
<tr class="even">
<td><p><a href="/dotnet/api/microsoft.rtc.collaboration.instantmessagingflowtemplate.supportedformats">SupportedFormats</a></p></td>
<td><p>Property. Gets the value that indicates the consumption mode of the application.</p>
<p></p>
<p>InstantMessagingFormat SupportedFormats {get; set;}</p></td>
</tr>
<tr class="odd">
<td><p><a href="/dotnet/api/microsoft.rtc.collaboration.instantmessagingflowtemplate.toastformatsupport">ToastFormatSupport</a></p></td>
<td><p>Property. Gets or sets the toast format support value, a value of the <a href="/dotnet/api/microsoft.rtc.collaboration.capabilitysupport">CapabilitySupport</a> enumeration.</p>
<p>CapabilitySupport ToastFormatSupport {get; set;}</p></td>
</tr>
<tr class="even">
<td><p><a href="/dotnet/api/microsoft.rtc.collaboration.instantmessagingflowtemplate.waitingfordeliverynotificationdisabled">WaitingForDeliveryNotificationDisabled</a></p></td>
<td><p>Property. Gets or sets the value that controls whether the <a href="/dotnet/api/microsoft.rtc.collaboration.instantmessagingflow.beginsendinstantmessage">BeginSendInstantMessage</a> operation will wait for delivery notifications before completion.</p>
<p>bool WaitingForDeliveryNotificationDisabled {get; set;}</p></td>
</tr>
</tbody>
</table>


Applications specify their consumption mode using the [InstantMessageConsumptionMode](/dotnet/api/microsoft.rtc.collaboration.instantmessageconsumptionmode) enumeration. The following table lists the enumeration values for this type.

<table>
<colgroup>
<col />
<col />
</colgroup>
<thead>
<tr class="header">
<th><p>Enumeration value</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>ConsumedLocally</strong></p></td>
<td><p>The message is consumed locally as soon as it is delivered. This is the default consumption mode.</p></td>
</tr>
<tr class="even">
<td><p><strong>ProxiedToRemoteEntity</strong></p></td>
<td><p>The message is proxied to a remote entity. The success or failure of the delivery is known only later.</p></td>
</tr>
</tbody>
</table>


If the application hosts a remote client, there can be a delay when the client sends the typing indications to a backend server. For this reason, the default value of three seconds for the idle time-out period may not be long enough. The application can set the idle time-out period to a larger value using flow settings.

The [SupportedFormats](/dotnet/api/microsoft.rtc.collaboration.instantmessagingflowtemplate.supportedformats) property lists the content types that the application supports for consuming messages received in the flow.

The internal IM media provider supports the sending and receiving of delivery notification messages that are sent by applications that do not directly consume messages, but serve as proxies for delivering the received messages to remote entities. A user-created Web server application is an example of such an application. If an application configures the flow as **ProxiedToRemoteEntity**, the application must register for the [MessageReceived](/dotnet/api/microsoft.rtc.collaboration.instantmessagingflow.messagereceived) event on the flow, and must send message delivery notifications with the [BeginSendSuccessDeliveryNotification(InstantMessageId, AsyncCallback, Object)](/dotnet/api/microsoft.rtc.collaboration.instantmessagingflow.beginsendsuccessdeliverynotification) or [BeginSendFailureDeliveryNotification(InstantMessageId, Int32, AsyncCallback, Object)](/dotnet/api/microsoft.rtc.collaboration.instantmessagingflow.beginsendfailuredeliverynotification) method. Because the messages are serialized, there might be an impact on application performance.

**InstantMessagingFlow** exposes the [DeliveryNotificationReceived](/dotnet/api/microsoft.rtc.collaboration.instantmessagingflow.deliverynotificationreceived) event, which is raised when an incoming delivery notification message is received. **InstantMessagingFlow** also exposes two methods to send delivery notifications to the message sender: [BeginSendFailureDeliveryNotification](/dotnet/api/microsoft.rtc.collaboration.instantmessagingflow.beginsendfailuredeliverynotification) and [BeginSendSuccessDeliveryNotification](/dotnet/api/microsoft.rtc.collaboration.instantmessagingflow.beginsendsuccessdeliverynotification).

An application that uses either of the overloaded [BeginSendInstantMessage](/dotnet/api/microsoft.rtc.collaboration.instantmessagingflow.beginsendinstantmessage) methods has no need to use the **DeliveryNotificationReceived** event, unless **WaitingForDeliveryNotificationDisabled** is set to true. The **BeginSendInstantMessage** methods automatically match incoming delivery notification messages to pending "SendMessage" operations that wait for them.

