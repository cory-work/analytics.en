---
title: People
description: The number of unique individuals, typically with multiple devices.
feature: Metrics
exl-id: 0136b843-2a1e-44d5-b5a6-e0fb03b7b995
---
# People

There are two versions of the 'People' metric.
 
For members of the [Device Co-op](https://experienceleague.adobe.com/docs/device-co-op/using/data/people.html) that do not use [Cross-Device analytics](../cda/overview.md), the 'People' metric is a statistically-derived count of the number of people represented in the report. It is the number of visitor IDs that are identified by the Device Co-op plus the number of devices that are not identified by the Co-op.
 
Within a [Cross-Device analytics](../cda/overview.md) virtual report suite, the 'People' metric is a not a statistical derivation. Instead, it is the sum of individuals who are identified in the report, plus the number of devices that are not identified as belonging to a person.

If a visitor is identified mid-visit, that visitor can count as 2 People (1 unidentified person and 1 identified person). [Replay](/help/components/cda/replay.md) mitigates this double counting depending on the reporting window, replay frequency, and success rate. See [Unique devices](unique-devices.md) for more information.
