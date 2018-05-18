---
Description: 'The Network Provider API specifies a single capabilities function.'
ms.assetid: 'fc74a043-da13-485f-9f54-a43064add927'
title: Capabilities Functions
---

# Capabilities Functions

The Network Provider API specifies a single capabilities function. When the operating system requests information about a network provider's capabilities, the [*Multiple Provider Router*](https://msdn.microsoft.com/library/windows/desktop/ms721594#-security-multiple-provider-router-gly) (MPR) calls the [**NPGetCaps**](npgetcaps.md) function of each network provider whose network is active.

The [**NPGetCaps**](npgetcaps.md) function returns a bitmask indicating which functions of the Network Provider API the network provider supports. The **NPGetCaps** function is the only function that a network provider must implement. The operating system calls this function to determine which other functions of the Network Provider API the provider supports.

 

 


