# Awesome LOL  [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> Living off the Land (LOL) attack techniques, tools, and defender resources.

[<img src="banner.png" align="center" width="1792" height="592">](https://github.com/danzek/awesome-lol)

Living off the land (LOL/LoTL) is an attack strategy where adversaries abuse tools and features commonly present in the target environment to blend in with normal activity and evade detection.


## Contents

- [Cloud & App](#cloud--app)
- [Endpoint](#endpoint)
- [Network](#network)
- [Software Supply Chain](#software-supply-chain)
- [SecOps](#secops)



## Cloud & App

- [Azure IP Lookup](https://www.azurespeed.com/Azure/IPLookup) - Maps IP addresses and domains to Azure service tags, regions, and data centers using Microsoft's published service tag files.
- [Entra ID First Party Apps & Scope Browser](https://entrascopes.com/) - First-party applications including their pre-consented permissions in Microsoft Entra ID, apps vulnerable to ConsentFix/AuthCodeFix, and those with default exceptions from conditional access policies.
- [Hacking the Cloud](https://hackingthe.cloud) - Encyclopedia of attacks/tactics/techniques for cloud exploitation.
- [LOLAPI](https://themagicclaw.github.io/LOLAPI/) - Real-world abused APIs across Windows, Cloud, and Browser platforms with detection strategies, mitigation guidance, and red team POCs.
- [LOLAPPS](https://lolapps-project.github.io) - Living Off The Land Applications, including built-in and third-party applications.
- [Microsoft 365 Application IDs – BEC Investigation Resources](https://byteintocyber.com/microsoft-365-application-ids-bec-investigation-resources/) - Reference for application IDs commonly abused in M365.
- [Microsoft Graph Permissions Explorer](https://graphpermissions.merill.net/permission/) - Reference for MS Graph permissions and the APIs that are enabled and the data objects exposed to the calling application for each.
- [RogueApps](https://huntresslabs.github.io/rogueapps) - OIDC/OAuth 2.0 applications that are often abused and used maliciously.
- [TrailDiscover](https://traildiscover.cloud/) - Repository of AWS CloudTrail events with detailed descriptions, MITRE ATT&CK insights, real-world incidents, references, and security implications.


## Endpoint

- [Argument Injection Vectors](https://sonarsource.github.io/argument-injection-vectors/) - Exploitable options for argument injection.
- [Bootloaders.io](https://www.bootloaders.io) - Known malicious bootloaders for various operating systems.
- [BYOL](https://cloud.google.com/blog/topics/threat-intelligence/bring-your-own-land-novel-red-teaming-technique/) - Bring Your Own Land (BYOL). Executing custom C#-based assemblies entirely within memory to reduce reliance on tools present on the target system.
- [Evasion Techniques](https://evasions.checkpoint.com/about/) - Encyclopedia of evasion and anti-debug techniques.
- [Filesec.io](https://filesec.io) - File extensions being used by attackers, tagged by function and operating system.
- [GTFOArgs](https://gtfoargs.github.io) - Unix binaries that can be manipulated for argument injection, possibly resulting in security vulnerabilities.
- [GTFOBins](https://gtfobins.github.io) - Unix binaries that can be used to bypass local security restrictions in misconfigured systems.
- [HijackLibs](https://hijacklibs.net) - DLL Hijacking candidates. Mapping between DLLs and vulnerable executables.
- [lcdbins](https://github.com/ofasgard/lcdbins) - Collection of oneliners that use lowest-common denominator binaries (lcdbins) present on most UNIX-based operating systems to perform enumeration and post-exploitation activities.
- [LOFLCAB](https://lofl-project.github.io) - Living off the Foreign Land Cmdlets and Binaries (cmdlets, binaries, scripts, and WMI classes).
- [LOLAD](https://lolad-project.github.io) - Catalog of Active Directory techniques, commands, and functions that attackers can abuse.
- [LOLBAS](https://lolbas-project.github.io) - Living Off The Land Binaries, Scripts and Libraries.
- [LOLBins CTI-Driven](https://lolbins-ctidriven.vercel.app) - Maps threat actor LOLBin usage during intrusions into graphical, STIX-formatted data for threat intelligence platforms.
- [LOLDrivers](https://www.loldrivers.io) - Windows drivers used by adversaries to bypass security controls and carry out attacks.
- [LOLESXi](https://lolesxi-project.github.io/LOLESXi/) - Binaries/scripts natively available in VMware ESXi that adversaries have utilized.
- [LOLGlobs](https://0xv1n.github.io/LOLGlobs/) - Glob-based command obfuscation techniques for Linux, macOS, Windows CMD, and PowerShell used to bypass signature-based detection in AV, EDR, and WAF products.
- [LOLRMM](https://lolrmm.io) - Remote Monitoring and Management (RMM) tools that could be abused by threat actors.
- [LOOBins](https://www.loobins.io) - Living Off the Orchard (LOO): Built-in macOS binaries that can be abused by attackers, with detailed usage information.
- [LOTHardware](https://lothardware.com.tr) - Catalog of hardware and devices commonly abused by attackers.
- [MalAPI.io](https://malapi.io) - Maps Windows APIs to common techniques used by malware.
- [Persistence Info](https://persistence-info.github.io) - Windows persistence mechanisms to improve protection and detection efficiency.
- [Sploitify](https://sploitify.haxx.it/) - Interactive cheat sheet of mostly public server-side exploits.
- [WADComs](https://wadcoms.github.io) - Interactive cheat sheet with offensive security tools and their respective commands to be used against Windows / Active Directory environments.
- [WTFBins](https://wtfbins.wtf) - Benign applications that exhibit suspicious behavior, generating noise and false positives in threat hunting and automated detections.


## Network

- [Awesome Tunneling](https://github.com/anderspitman/awesome-tunneling) - Cloudflare/ngrok Tunnel alternatives and other tunneling software and services with focus on self-hosting.
- [LOLC2](https://lolc2.github.io) - C2 frameworks that leverage legitimate services to evade detection.
- [LOTS Project](https://lots-project.com) - Living Off Trusted Sites: Legitimate popular domains abused for phishing, C2, exfiltration, and tool delivery to evade detection.
- [LOTTunnels](https://lottunnels.github.io) - Living Off the Tunnels: Legitimate tunneling services abused for exfiltration, persistence, and shell access.


## Software Supply Chain

- [LoLCerts](https://github.com/WithSecureLabs/lolcerts) - Living Off The Leaked Certificates: Code signing certificates known to have been leaked or stolen, then abused by threat actors.
- [LOTP](https://boostsecurityio.github.io/lotp/) - Living Off the Pipeline: Inventories how development tools (typically CLIs) commonly used in CI/CD pipelines have lesser-known RCE-By-Design features ("foot guns").


## SecOps

- [LoFP](https://br0k3nlab.com/LoFP/) - Living off the False Positive: Autogenerated collection of false positives sourced from popular rule sets.
- [Project LOST](https://0xanalyst.github.io/Project-Lost/) - Living Off Security Tools: Security tools used by adversaries to bypass security controls and carry out attacks.
