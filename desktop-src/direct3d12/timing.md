---
title: Timing
description: This section covers querying timestamps, and calibrating the GPU and CPU timestamp counters.
ms.assetid: 'CC1E5BAB-4363-43FF-BF5B-6C9AEBECD6CA'
---

# Timing

This section covers querying timestamps, and calibrating the GPU and CPU timestamp counters.

-   [Timestamp Frequency](#timestamp-frequency)
-   [Timestamp Calibration](#timestamp-calibration)
-   [Related topics](#related-topics)

## Timestamp Frequency

Applications can query the GPU timestamp frequency on a per-command queue basis (refer to the [**ID3D12CommandQueue::GetTimestampFrequency**](id3d12commandqueue-gettimestampfrequency.md) method).

The returned frequency is measured in Hz (ticks/sec). This API fails (and returns E\_FAIL) if the specified command queue does not support timestamps (see the table in the [Queries](queries.md) section).

## Timestamp Calibration

D3D12 enables applications to correlate results obtained from timestamp queries with results obtained from calling `QueryPerformanceCounter`. This is enabled by the call [**ID3D12CommandQueue::GetClockCalibration**](id3d12commandqueue-getclockcalibration.md).

[**GetClockCalibration**](id3d12commandqueue-getclockcalibration.md) samples the GPU timestamp counter for a given command queue and samples the CPU counter via `QueryPerformanceCounter` at nearly the same time. Again this API fails (returning E\_FAIL) if the specified command queue does not support timestamps (see the table in the [Queries](queries.md) section).

Note that GPU and CPU timestamp counters are not necessarily directly related to the clock speed of these processors, but instead work from timestamp ticks.

## Related topics

<dl> <dt>

[Counters and Queries](counters-and-queries.md)
</dt> <dt>

[**ID3D12Device::SetStablePowerState**](id3d12device-setstablepowerstate.md)
</dt> <dt>

[**ID3D12Object::SetName**](id3d12object-setname.md)
</dt> <dt>

[**ID3DUserDefinedAnnotation**](https://msdn.microsoft.com/library/windows/desktop/hh446881)
</dt> <dt>

[Performance Measurement](performance-measurement.md)
</dt> </dl>

 

 



