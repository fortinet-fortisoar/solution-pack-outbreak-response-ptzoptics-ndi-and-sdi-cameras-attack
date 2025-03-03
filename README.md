# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

FortiGuard Labs has observed attack attempts aimed at PTZOptics cameras, with FortiGuard sensors detecting telemetry from as many as 4,000 devices. This surge in activity highlights the vulnerabilities present in these devices, which can be easily exploited by attackers seeking unauthorized access, potentially leading complete camera takeover, infection with bots, pivoting to other devices connected on the same network, or disruption of video feeds. 

 The **Outbreak Response - PTZOptics NDI and SDI Cameras Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.0.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/ptzoptics-cameras-attack) contains information about the outbreak alert **Outbreak Response - PTZOptics NDI and SDI Cameras Attack**. 

## Background: 

PTZOptics cameras are used in industrial, healthcare, business, and government sectors worldwide. The majority of the blocked attack attempts observed by FortiGuard telemetry are from United States, Japan, and South Korea. 

CVE-2024-8956 is a weak authentication flaw (PT30X-SDI/NDI-xx firmware before 6.3.40), allowing unauthorized users to access, which may reveal usernames, MD5 password hashes, and network configurations.

CVE-2024-8957 is caused by insufficient input sanitization (PT30X-SDI/NDI-xx before 6.3.40) in the 'ntp_addr' field, allowing attackers to use a specially crafted payload to insert commands for remote code execution. 

## Announced: 

Taking proactive measures is essential to safeguard against these vulnerabilities and protect sensitive information from malicious actors. FortiGuard recommends users to download firmware updates from the vendor. 

## Latest Developments: 

November 4, 2024: Cybersecurity and Infrastructure Security Agency (CISA) added the vulnerabilities to known exploited vulnerabilities (KEV) catalog

October 31, 2024: GreyNoise released a detailed technical analysis
https://www.labs.greynoise.io/grimoire/2024-10-31-sift-0-day-rce/ 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|