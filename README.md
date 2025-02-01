# Awesome LOL / Commonly Abused  [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> Awesome list of Living off the Land (LOL) methods, tools, and features commonly abused by attackers

Resources related to living off the land (LOL / LoTL) techniques, tools, detections, and more.

*[Contributions welcome](https://github.com/danzek/awesome-lol-commonly-abused/blob/main/contributing.md).*

---

## Contents

- [Cloud & App](#cloud-app)
  - [AWS](#aws)
  - [Azure](#azure)
    - [M365](#m365)
  - [General](#general)
- [DevOps](#devops)
- [Endpoint](#endpoint)
  - [General](#general)
  - [macOS](#macos)
  - [Unix](#unix)
  - [Windows](#windows)
- [Hardware](#hardware)
- [Network](#network)
- [SecOps](#secops)

- [References](#references)


---

## Cloud & App

Related to cloud environments / services or SaaS apps.

### AWS

Related to Amazon Web Services (AWS).

- [TrailDiscover](https://traildiscover.cloud/) - An evolving repository of CloudTrail events with detailed descriptions, MITRE ATT&CK insights, real-world incidents, references and security implications.

### Azure

Microsoft Azure related.

- [Azure IP Lookup](https://www.azurespeed.com/Azure/IPLookup) - Find Azure service tags and region details for a given IP address or domain name. This tool leverages Microsoft's published service tag files to map IP addresses to physical data centers and cloud services. By checking the provided IP address or domain against these files, it identifies whether the IP is part of Azure, which service tag it belongs to, and the Azure region from which it originates.
- [Microsoft Graph Permissions Explorer](https://graphpermissions.merill.net/permission/) - Reference for MS Graph permissions and the APIs that are enabled and the data objects exposed to the calling application for each.

#### M365

Related to Microsoft 365.

- [Microsoft 365 Application IDs – BEC Investigation Resources](https://byteintocyber.com/microsoft-365-application-ids-bec-investigation-resources/) - Reference for application IDs in M365.

### General

Information related to cloud & app regardless of specific cloud environment or app.

- [Cloud Native Landscape](https://landscape.cncf.io) - The Cloud Native Interactive Landscape filters and sorts hundreds of projects and products, and shows details including GitHub stars, funding, first and last commits, contributor counts and headquarters location. This project is intended as a map through the previously uncharted terrain of cloud native technologies. This attempts to categorize most of the projects and product offerings in the cloud native space. There are many routes to deploying a cloud native application, with CNCF Projects representing a particularly well-traveled path.
- [Hacking the Cloud](https://hackingthe.cloud) - Hacking the Cloud is an encyclopedia of the attacks/tactics/techniques that offensive security professionals can use on their next cloud exploitation adventure. The goal is to share this knowledge with the security community to better defend cloud native technologies.

## DevOps

Related to Development Operations (DevOps) including software development life cycle (SDLC), CI/CD, DevSecOps, and other integrations between software development and IT operations.

- [LoLCerts](https://github.com/WithSecureLabs/lolcerts) - Living Off The ~~Land~~ Leaked Certificates. A repository of code signing certificates known to have been leaked or stolen, then abused by threat actors.
- [LOTP](https://boostsecurityio.github.io/lotp/) - Living Off the Pipeline. The idea of the LOTP project is to inventory how development tools (typically CLIs), commonly used in CI/CD pipelines, have lesser-known RCE-By-Design features ("foot guns"), or more generally, can be used to achieve arbitrary code execution by running on untrusted code changes or following a workflow injection.


## Endpoint

Focused on endpoints (i.e., servers and workstations).


### General

Information relevant to endpoints regardless of operating system.

- [Bootloaders.io](https://www.bootloaders.io) - Curated list of known malicious bootloaders for various operating systems.
- [Evasion Techniques](https://evasions.checkpoint.com/about/) - An encyclopedia of evasion and anti-debug techniques.
- [Filesec.io](https://filesec.io) - File extensions being used by attackers. Tagged by function and operating system.
- [LOLAPPS](https://lolapps-project.github.io) - Living Off The Land Applications: Sowing the seeds for application exploitation ease. This project was made because exploitation isn't limited to binaries using command line techniques. Both built-in and third-party applications have been used & abused for adversarial gain since the dawn of time, and knowing these methods can help when all else fail.
- [LOLESXi](https://lolesxi-project.github.io/LOLESXi/) - Living Off The Land ESXi eatures a comprehensive list of binaries/scripts natively available in VMware ESXi that adversaries have utilised in their operations.
- [LOLRMM](https://lolrmm.io) - LOLRMM is a curated list of Remote Monitoring and Management (RMM) tools that could potentially be abused by threat actors.
- [Sploitify](https://sploitify.haxx.it/) - Sploitify is an interactive cheat sheet, containing a curated list of public server-side exploits (mostly).
- [WTFBins](https://wtfbins.wtf) - WTFBins are binaries that behave exactly like malware, except, somehow, they're not? This project aims to catalogue benign applications that exhibit suspicious behavior. These binaries can emit noise and false positives in threat hunting and automated detections. By cataloguing them here, the hope is to allow defenders to improve their detection rules and threat hunting queries.


### macOS

Specific to macOS or Mac OS X.

- [LOOBins](https://www.loobins.io) - Living Off the Orchard (LOO): macOS Binaries (LOOBins) is designed to provide detailed information on various built-in macOS binaries and how they can be used by threat actors for malicious purposes.


### Unix

Unix-specific.

- [Argument Injection Vectors](https://sonarsource.github.io/argument-injection-vectors/) - A curated list of exploitable options when dealing with argument injection bugs. These are not vulnerabilities in the associated programs but rather intended features that were proven to be useful to attackers in very specific scenarios.
- [GTFOArgs](https://gtfoargs.github.io) - GTFOArgs is a curated list of Unix binaries that can be manipulated for argument injection, possibly resulting in security vulnerabilities.
- [GTFOBins](https://gtfobins.github.io) - GTFOBins is a curated list of Unix binaries that can be used to bypass local security restrictions in misconfigured systems.
- [ofasgard/lcdbins](https://github.com/ofasgard/lcdbins) - An lcdbin is a lowest-common denominator binary - one which, with rare exceptions, should be present on any UNIX-based operating system. This repository is a collection of oneliners that use lcdbins to perform enumeration and post-exploitation activities that you'd normally use other tools for - such as id, netstat or python. Use them when you find yourself in a stripped-down environment where the usual tools aren't available.


### Windows

Windows-specific.

- [BYOL](https://cloud.google.com/blog/topics/threat-intelligence/bring-your-own-land-novel-red-teaming-technique/) - Bring Your Own Land (BYOL). Executing custom C#-based assemblies entirely within memory to reduce reliance on tools present on the target system.
- [HijackLibs](https://hijacklibs.net) - HijackLibs provides an curated list of DLL Hijacking candidates. A mapping between DLLs and vulnerable executables is kept and can be searched via this website.
- [LOFLCAB](https://lofl-project.github.io) - Living off the Foreign Land Cmdlets and Binaries. The objective of the LOFL project is to document every cmdlet, binary, script, and WMI class that can be used for Living Off the Foreign Land techniques.
- [LOLAD](https://lolad-project.github.io) - Living Off The Land and Exploitation Active Directory. The LOLAD and Exploitation project provides a comprehensive collection of Active Directory techniques, commands, and functions that can be used natively to support offensive security operations and Red Team exercises. These techniques leverage AD’s built-in tools to conduct reconnaissance, privilege escalation, and lateral movement, among other tactics.
- [LOLBAS](https://lolbas-project.github.io) - Living Off The Land Binaries, Scripts and Libraries. The goal of the LOLBAS project is to document every binary, script, and library that can be used for Living Off The Land techniques.
- [LOLBins CTI-Driven](https://lolbins-ctidriven.vercel.app) - The LOLBins CTI-Driven (Living-Off-the-Land Binaries Cyber Threat Intelligence Driven) is a project that aims to help cyber defenders understand how LOLBin binaries are used by threat actors during an intrusion in a graphical and digestible format for the TIPs platform using the STIX format.
- [LOLDrivers](https://www.loldrivers.io) - Living Off The Land Drivers. LOLDrivers is a curated list of Windows drivers used by adversaries to bypass security controls and carry out attacks.
- [MalAPI.io](https://malapi.io) - MalAPI.io maps Windows APIs to common techniques used by malware.
- [Persistence Info](https://persistence-info.github.io) - Curated information about Windows persistence mechanisms to improve protection / detection efficiency.
- [WADComs](https://wadcoms.github.io) - WADComs is an interactive cheat sheet, containing a curated list of offensive security tools and their respective commands, to be used against Windows / Active Directory environments.


## Hardware

Related to hardware devices that are not considered traditional endpoints (e.g., removable storage devices, Arduino, Flipper Zero, etc.).

- [LOTHardware](https://lothardware.com.tr) - Living off the Hardware Project. LOTHardware is a resource collection that provides guidance on identifying and utilizing malicious hardware and malicious devices.


## Network

Network-specific or related to network traffic without being specific only to one operating system.

- [anderspitman/awesome-tunneling](https://github.com/anderspitman/awesome-tunneling) - List of ngrok/Cloudflare Tunnel alternatives and other tunneling software and services. Focus on self-hosting.
- [LOLC2](https://lolc2.github.io) - A collection of C2 frameworks that leverage legitimate services to evade detection.
- [LOTS Project](https://lots-project.com) - Living Off Trusted Sites (LOTS) Project. Attackers are using popular legitimate domains when conducting phishing, command and control, exfiltration, and downloading tools to evade detection. This curated list of websites allows attackers to use their domain or subdomain.
- [LOTTunnels](https://lottunnels.github.io) - Living Off The Tunnels. The LOTTunnels Project is a community driven project to document digital tunnels that can be abused by threat actors as well by insiders for data exfiltration, persistence, shell access, etc.


## SecOps

Related to Security Operations (SecOps) including SIEM, SOAR, EDR, and other tools used for threat hunting, playbook automation, incident coordination, and other integrations between cybersecurity and IT operations.

- [LoFP](https://br0k3nlab.com/LoFP/) - Living off the False Positive is an autogenerated collection of false positives sourced from some of the most popular rule sets. The information is categorized along with MITRE ATT&CK techniques, rule source, and data source. Entries include details from related rules along with their description and detection logic.
- [Project LOST](https://0xanalyst.github.io/Project-Lost/) - Living Off Security Tools. A curated list of security tools used by adversaries to bypass security controls and carry out attacks.

---

## References

Resources consulted in compilation of this awesome list include:

- [LOLOL](https://lolol.farm) - Living Off the Living Off the Land. A great collection of resources to thrive off the land.
- [sheimo/awesome-lolbins-and-beyond](https://github.com/sheimo/awesome-lolbins-and-beyond) - A curated list of awesome LOLBins, GTFO projects, and similar 'Living Off the Land' security resources.
