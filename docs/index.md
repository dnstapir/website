---
title: What is DNS TAPIR?
---

# The Problem

The DNS system is an integral part of the Internet infrastructure, and by its nature fully distributed, highly resilient and with no central point of control. It is also an old protocol with no security mechanisms at its core. This makes it ideal for abuse.

There are several security products available to counter threats in DNS. Threat intel usually comes from third party sources and internal research. The quality of that intel is used as a sales argument, which creates silos of information and partial, frequently disjoined protection from vendors, and research is focused on commercial value. This makes us all less secure.
Government interests in this space tend to fall into intelligence gathering or regulation. The prior is not prone to sharing information whereas the latter lacks maturity and means of enforcement. The net effect is that threat actors and entities outside government jurisdiction remain completely unhindered, while law abiding citizens and entities incur even further administrative burdens and restrictions to little or no effect. 

Research into DNS threats requires data. This is a tightrope balance between legitimate interest and privacy, and efforts are made to strengthen privacy controls within DNS. Privacy, however, is a double-edged sword, and unfortunately, individual privacy and security both received the dull edge. Malicious actors use privacy measures to hide and mask activities, some privacy mechanisms make more identifying information available to DNS providers doing data collection, while other mechanisms make those same data collection activities more difficult to monitor. Big data has fostered a 'collect everything, sort it out later'-attitude and with the security threat landscape evolving rapidly, the temptation of 'just in case' over-collection and purpose creep is hard to resist. Frequent mishaps have eroded trust in both corporate and government data collection, as well as oversight and regulation.


# The Solution

Ethical data collection -- treat data with the respect it deserves. The implied conflict between privacy and security does not exist. For exploration and ideation, as close a representation of the actual data is desirable, but subsequent analysis always relies on extracted features. Once identified, it is both possible and desirable to minimise the collected data to those features as close to the subject as possible. Doing this at the edge before aggregation and analysis, leaves identifying information in the monitored system and transmits less data to analysis, something which speeds up detection and mitigation, and simplifies data governance for the receiver. Data you do not have you cannot lose.

Identifiers are one thing, but patterns in the data itself may reveal the identity of a client. The relationships that leak this information are often not trivial, which is why a process designed to remove identifying information requires both good design and critical review. For this, transparency is an absolute requirement - for the transformation, for the data transmitted and for the effects of aggregation. 

Independent research and democratised threat intel. Since both commercial interests and government efforts suffer from inherent limitations to their effectiveness, an entity that is under the influence of neither is needed to address the problem. With a neutral party responsible for data collection and research, it is possible to adopt a fully data-driven approach where actions and reporting is based on what is actually seen, with less bias introduced by special interests.

# The Initiative

**Organisation**. Research lab controlled by a foundation. The foundation is constructed to guarantee independence, protection of data and safeguarding individual privacy. 

**Input**. Data collection is done through open source components and open APIs. Data minimisation, anonymization and partial aggregation is done at the source for all continuously analysed data. Sensitive research data with residual PII is handled according to secure data lifecycle principles in agreement with original data controller and disjoined from immediate identifiers.

**Analysis**. Continuous analysis is done on aggregated data. The main focus of the initiative is to evolve and expand on methods of analysis, utilising state of the art data science techniques and technologies. 

**Output**. Provide actionable threat intel to partners in realtime, publish discoveries to the larger community, and act as a DNS privacy watchdog.
