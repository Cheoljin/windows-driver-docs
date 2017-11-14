---
title: Filtering condition data types
author: windows-driver-content
description: This section describes filtering condition data types.
ms.assetid: 43810fc0-f386-4a21-9229-c8c8f8d6710f
keywords:
- Filtering condition data types network drivers
ms.author: windowsdriverdev
ms.date: 11/08/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# Filtering condition data types

The data type for the condition value for each filtering condition is specified as an FWP_DATA_TYPE value as follows.

<table>
<tr>
<th>Filtering condition identifier</th>
<th>Condition value data type</th>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_LOCAL_ADDRESS</p>
</td>
<td>
<p>For an IPv4 address:</p>
<dl>
<dd>
FWP_V4_ADDR_MASK or FWP_UINT32
</dd>
</dl>
<p>For an IPv6 address:</p>
<dl>
<dd>
FWP_V6_ADDR_MASK or FWP_BYTE_ARRAY16_TYPE
</dd>
</dl>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_REMOTE_ADDRESS</p>
</td>
<td>
<p>For an IPv4 address:</p>
<dl>
<dd>
FWP_V4_ADDR_MASK or FWP_UINT32
</dd>
</dl>
<p>For an IPv6 address:</p>
<dl>
<dd>
FWP_V6_ADDR_MASK or FWP_BYTE_ARRAY16_TYPE
</dd>
</dl>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_SOURCE_ADDRESS</p>
</td>
<td>
<p>For an IPv4 address:</p>
<dl>
<dd>
FWP_V4_ADDR_MASK or FWP_UINT32
</dd>
</dl>
<p>For an IPv6 address:</p>
<dl>
<dd>
FWP_V6_ADDR_MASK or FWP_BYTE_ARRAY16_TYPE
</dd>
</dl>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_DESTINATION_ADDRESS</p>
</td>
<td>
<p>For an IPv4 address:</p>
<dl>
<dd>
FWP_V4_ADDR_MASK or FWP_UINT32
</dd>
</dl>
<p>For an IPv6 address:</p>
<dl>
<dd>
FWP_V6_ADDR_MASK or FWP_BYTE_ARRAY16_TYPE
</dd>
</dl>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_LOCAL_ADDRESS_TYPE</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_DESTINATION_ADDRESS_TYPE</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_LOCAL_INTERFACE</p>
</td>
<td>
<p>FWP_UINT64</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_FORWARD_INTERFACE</p>
</td>
<td>
<p>FWP_UINT64</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_PROTOCOL</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_LOCAL_PORT</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_REMOTE_PORT</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_ICMP_TYPE</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_ICMP_CODE</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_EMBEDDED_LOCAL_ADDRESS_TYPE</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_EMBEDDED_REMOTE_ADDRESS</p>
</td>
<td>
<p>For an IPv4 address:</p>
<dl>
<dd>
FWP_V4_ADDR_MASK or FWP_UINT32
</dd>
</dl>
<p>For an IPv6 address:</p>
<dl>
<dd>
FWP_V6_ADDR_MASK or FWP_BYTE_ARRAY16_TYPE
</dd>
</dl>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_EMBEDDED_PROTOCOL</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_EMBEDDED_LOCAL_PORT</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_EMBEDDED_REMOTE_PORT</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_FLAGS</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_DIRECTION</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_INTERFACE_INDEX</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_SUB_INTERFACE_INDEX</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_SOURCE_INTERFACE_INDEX</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_SOURCE_SUB_INTERFACE_INDEX</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_DESTINATION_INTERFACE_INDEX</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_DESTINATION_SUB_INTERFACE_INDEX</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_ALE_APP_ID</p>
</td>
<td>
<p>FWP_BYTE_BLOB_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_ALE_USER_ID</p>
</td>
<td>
<p>FWP_SECURITY_DESCRIPTOR_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_ALE_REMOTE_USER_ID</p>
</td>
<td>
<p>FWP_SECURITY_DESCRIPTOR_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_ALE_REMOTE_MACHINE_ID</p>
</td>
<td>
<p>FWP_SECURITY_DESCRIPTOR_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_ALE_PROMISCUOUS_MODE</p>
</td>
<td>
<p>FWP_UNIT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_ALE_SIO_FIREWALL_SYSTEM_PORT</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_ALE_NAP_CONTEXT</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_REMOTE_USER_TOKEN</p>
</td>
<td>
<p>FWP_SECURITY_DESCRIPTOR_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_RPC_IF_UUID</p>
</td>
<td>
<p>FWP_BYTE_ARRAY16_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_RPC_IF_VERSION</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_RPC_IF_FLAG</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_DCOM_APP_ID</p>
</td>
<td>
<p>FWP_BYTE_ARRAY16_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IMAGE_NAME</p>
</td>
<td>
<p>FWP_BYTE_BLOB_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_RPC_PROTOCOL</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_RPC_AUTH_TYPE</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_RPC_AUTH_LEVEL</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_SEC_ENCRYPT_ALGORITHM</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_SEC_KEY_SIZE</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_LOCAL_ADDRESS_V4</p>
</td>
<td>
<p>FWP_V4_ADDR_MASK or FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_LOCAL_ADDRESS_V6</p>
</td>
<td>
<p>FWP_V6_ADDR_MASK or FWP_BYTE_ARRAY16_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_PIPE</p>
</td>
<td>
<p>FWP_BYTE_BLOB_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_REMOTE_ADDRESS_V4</p>
</td>
<td>
<p>FWP_V4_ADDR_MASK or FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_REMOTE_ADDRESS_V6</p>
</td>
<td>
<p>FWP_V6_ADDR_MASK or FWP_BYTE_ARRAY16_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_PROCESS_WITH_RPC_IF_UUID</p>
</td>
<td>
<p>FWP_BYTE_ARRAY16_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_RPC_EP_VALUE</p>
</td>
<td>
<p>FWP_BYTE_BLOB_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_RPC_EP_FLAGS</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_CLIENT_TOKEN</p>
</td>
<td>
<p>FWP_SECURITY_DESCRIPTOR_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_RPC_SERVER_NAME</p>
</td>
<td>
<p>FWP_BYTE_BLOB_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_RPC_SERVER_PORT</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_RPC_PROXY_AUTH_TYPE</p>
</td>
<td>
<p>FWP_BYTE_BLOB_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_CLIENT_CERT_KEY_LENGTH</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_CLIENT_CERT_OID</p>
</td>
<td>
<p>FWP_BYTE_BLOB_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_INTERFACE_MAC_ADDRESS</p>
</td>
<td>
<p>FWP_BYTE_ARRAY6_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_LOCAL_MAC_ADDRESS</p>
</td>
<td>
<p>FWP_BYTE_ARRAY6_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_REMOTE_MAC_ADDRESS</p>
</td>
<td>
<p>FWP_BYTE_ARRAY6_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_ETHER_TYPE</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_VLAN_ID</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_NDIS_PORT</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_NDIS_MEDIA_TYPE</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_NDIS_PHYSICAL_MEDIA_TYPE</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_L2_FLAGS</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_LOCAL_MAC_ADDRESS_TYPE</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_REMOTE_MAC_ADDRESS_TYPE</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_INTERFACE</p>
</td>
<td>
<p>FWP_UINT64</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_PACKAGE_ID</p>
</td>
<td>
<p>FWP_SID</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_MAC_SOURCE_ADDRESS</p>
</td>
<td>
<p>FWP_BYTE_ARRAY6_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_MAC_DESTINATION_ADDRESS</p>
</td>
<td>
<p>FWP_BYTE_ARRAY6_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_MAC_SOURCE_ADDRESS_TYPE</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_MAC_DESTINATION_ADDRESS_TYPE</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_SOURCE_PORT</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_IP_DESTINATION_PORT</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_VSWITCH_ID</p>
</td>
<td>
<p>FWP_BYTE_BLOB_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_VSWITCH_NETWORK_TYPE</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_VSWITCH_SOURCE_INTERFACE_ID</p>
</td>
<td>
<p>FWP_BYTE_BLOB_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_VSWITCH_DESTINATION_INTERFACE_ID</p>
</td>
<td>
<p>FWP_BYTE_BLOB_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_VSWITCH_SOURCE_INTERFACE_TYPE</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_VSWITCH_DESTINATION_INTERFACE_TYPE</p>
</td>
<td>
<p>FWP_UINT8</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_VSWITCH_SOURCE_VM_ID</p>
</td>
<td>
<p>FWP_BYTE_BLOB_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_VSWITCH_DESTINATION_VM_ID</p>
</td>
<td>
<p>FWP_BYTE_BLOB_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_VSWITCH_TENANT_NETWORK_ID</p>
</td>
<td>
<p>FWP_UINT16</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_ALE_PACKAGE_ID</p>
</td>
<td>
<p>FWP_SID</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_ALE_ORIGINAL_APP_ID</p>
</td>
<td>
<p>FWP_BYTE_BLOB_TYPE</p>
</td>
</tr>
<tr>
<td>
<p>FWPM_CONDITION_QM_MODE</p>
</td>
<td>
<p>FWP_UINT32</p>
</td>
</tr>
</table>

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bp_mb\p_mb%5D:%20Planning%20your%20APN%20database%20submission%20%20RELEASE:%20%281/18/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")