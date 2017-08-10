---
layout: default
title:  "OTF members expand concept for Kazoo EDR (Event Data Records)"
date:   2017-08-10 12:00:00
categories: pull-request kazoo contributions 
---

Founding member and volunber director Noal Mehl has submitted an _Open Telecom Foundation endorse _ contribution to the Kazoo open source project that would greatly enhance Kazoo's ability to provide output of new realtime events. **EDR (Event Data Records)** would allow for a much more flexible and detailed method for Kazoo to provide output of a new types of realtime eventing. 

Over the last few weeks a number of Open Telecom Members have been involved in expanding Kazoo EDR, which started over a year ago as a contracted project by OTF member Voxter. Leading these efforts to revive and revitalize Kazoo EDR is [Max Lay](https://github.com/kalda341) of OTF founding member Conversant. [Max Lay](https://github.com/kalda341) has provided updated to the EDR code and is preparing for a pull release (PR) contribution to the upstream project repo. 

> "As a developer/integrator/operator, I want EDR to be extended and mainlined to allow for flexible eventing consuming and publishing. The overall goal is a flexible way to capture rich event information from existing and new kazoo apps (both kz_apps and ecallmgr). We are hoping to to extend the existing EDR application (and ACDC initially) to address this."

**Noal Mehl**
Director, Open Telecom Foundation

> "It's great to see renewed interest in adding a new flexible event engine to Kazoo. EDR looks to be a good compliment to Blackhole and can also lead to other realtime eventing output systems that developers can find all sorts of uses for. Our initial use case for EDR would be to add realtime events to ACDc via Blackhole. Of course, there are so many other parts of Kazoo that could benefit. Beyond this more obvious example, it would be excellent to have inbound calls from the PSTN fire events as they pass through individual steps Callflows. When combined with Elastic search, this kind of output would provide for excellent debugging."

**[Graham Nelson-Zutter](/who/#who_directors_graham)**
Director, Open Telecom Foundation

> "Third party integrations with kazoo can also benefit. This eventing layer would help to generate evens from a logical/business perspective (e.g. what is happening) instead of a technical perspective. You can have events like 'You receive a call, the call has the following A-number, the following B-number and is transferred by C-extension'. This sort of events are currently hard to filter out from the data and are much needed for third party integrations like CRM. This very example is why I made the channel_bridge webhook back then. This is just an example, there are many more cases like this, but IMO an illustration of why this a such a good overall addition to the platform!"

**[Remco van Vugt](/who/#who_directors_remco)**
Director, Open Telecom Foundation

Please be part of the conversation! We'd love to hear your ideal on how to improve Kazoo EDR:

**2600Hz Kazoo Project Jira (Issue Tracker)**
[https://2600hz.atlassian.net/browse/KAZOO-5635](https://2600hz.atlassian.net/browse/KAZOO-5635)

**2600Hz Kazoo Project Community Forum (Open Discussions Group)**
[https://forums.2600hz.com/forums/topic/9084-edr-architectural-discussion/](https://forums.2600hz.com/forums/topic/9084-edr-architectural-discussion/)


