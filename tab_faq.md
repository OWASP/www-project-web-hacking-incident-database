---
title: FAQ
layout: col-sidebar
tab: true
order: 2
tags: faq-tag
---
## What incidents are included in WHID?

WHID only tracks media reported security incidents that can be associated with a negative impact to a public web application (such as downtime, data leakage, planting of malware, etc...). We also try to limit the database only to targeted attacks, though the distinction between targeted and non-targeted attacks is grey.

The database does not include known vulnerabilities in web based applications, an area well covered by other databases such as [CVE](https://www.cve.org/). WHID does not include incidents in which web site were breached using operating system or network layer vulnerabilities.

We also consider most web site defacements as non targeted attacks and we do not include them in the database. We will, however, include defacements of high profile websites.  For information about web site defacements refer to [zone-h](https://zone-h.org/archive).

As those criteria are somewhat subjective, we welcome comments on the inclusion or exclusion of publicized security breaches.

## Were there only few dozen web hacks last year?

The criteria for inclusion into WHID as mentioned above is a bit strict. The goal is to list only incidents that are related to web application layer compromises by threat actors. The goal is to show that application layer security is a risk that cannot be ignored regardless of the perceived value of the website.

Keep in mind, that while there are countless website hacks, the vast majority are not reported. Even for those reported most of the time it is difficult to tell how exactly they occurred (attack methods).

Specifically addressing the defacement incidents reported in zone-h, bear in mind that in nearly all of these incidents there is no public information on the way in which they were carried. Additionally, many defacements are not targeted and are the result of a wide scan for vulnerable sites and therefore we do not normally include defacements in WHID.

## Why can't I find a well known incident in WHID?

The reason is probably that the incident did not occur due to a web application vulnerability, or there was not direct impact (outcome). For example probably the most well known information security breach ever, the CardSystems incident was added only in April 2006, nearly a year after it was initially publicized. While we always suspected that it was a web hack and industry rumors hinted that, no public information regarding the way in which the hack was done was available until April 2006. Actually the CardSystems incident was brought in previous versions of this FAQ as an example of an incident that we would like to add to WHID but cannot. For other hacks such information is not available and may not become available in the future.

## How reliable are the incidents reported in WHID?

The data collected is NOT reported directly to OWASP/WASC but is rather collected from public sources, mostly technical media, mailing list post and researchers advisories. As a result the reliability of the reported information depends on the source. Since the source (or sources) is included with each entry, the reader can assess its reliability independently. We do however assess the source before including an incident in the database and if for whatever reason something we added to the database is found to be erroneous, we remove it, though this has ever happened to date.

For media reported incidents, we're trusting that the reporter or news outlet verified the information. For mailing list reported incidents and research advisories, these issues are normally quickly confirmed our refuted by other subscribers or by the offended vendor. In case of doubt evaluate the level of information provided in the disclosure and the publishing history of the researcher.

## Breach vs. Disclosure

WHID includes "breaches" but not "disclosures". Breaches are incidents in which a web site was compromised, while disclosures are incidents in which a researcher published a vulnerability in a web site. In other words, breaches are incidents in which we know bad guys took advantage of a vulnerability, while disclosures are incidents in which whitehat hackers disclose the vulnerability details.  WHID is focused on compromises by real threat actors.

## The "Unknown" Attack Method

Some of the incident attack methods are classified as "Unknown". You may wonder why were these incidents included in the list, as there is no way to know that the hacker exploited a web application vulnerability. In some cases the public information available indicates that the incident exploited a web application vulnerability, and in others we deducted from the available information.  This important inclusion criteria for WHID is a negative impact to a web application or its data.  Attack Method and Application Weakness may be listed as Unknown if those details are not available.

## How can I contribute?

You can help make WHID better. You don't need to invest a lot of time:

* If you encounter a new Web incident, use the [WHID Submittal Form](https://docs.google.com/forms/d/e/1FAIpQLSdRxE1DqOsgKf_nMNwtb2vY3EBRKsBgc0-sBzVdj5zud0HwEQ/viewform?embedded=true&formkey=dHktV0FmWGMyTDZPbkZtOEJXNzhPbXc6MQ&pli=1)
* As we speak English we miss alot in non English speaking countries so we are especially looking for non English sources. As long as they can be translated using Google translate of a similar service, we can include it.
* If you want to contribute more, become a WHID editor. Send an e-mail to the project leaders with a few words (and preferably a link) about yourself and sign up to this site. We will activate your account and enable you to edit incidents. We need you to:
add past incidents. 
