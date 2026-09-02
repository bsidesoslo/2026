---
layout: talk
title: "Breaking the Charge: Security Analysis of the Phoenix Contact CHARX EV Charging Controller"
duration: 45 
scheduled: "14:05"
speakers: 
  -  name: Piotr Ptaszek
     image: PiotrPtaszek.png
     bio: |
      Senior Purple Teamer @ Tier-1 Global Bank, specializing in adversary simulation, red team operations, and offensive tooling development. Experienced in penetration testing across banking and energy sectors, including Web/Mobile/AD/OT-ICS/Embedded systems in critical infrastructure. Conducts independent hardware security research, holds multiple CVE/ZDI vulnerability disclosures. Co-author of "Introduction to IT Security" and leads hands-on security training.
     socials:
      - type: linkedin
        url: https://www.linkedin.com/in/piotr-ptaszek/
  -  name: Mateusz Wójcik
     image: MateuszWojcik.png
     bio: |
      Independent security researcher, red team operator, and former programmer specializing in IoT security, loves to find new vulnerabilities in IoT devices, especially those based on architectures like ARM and MIPS.

---
Electric vehicle charging infrastructure is rapidly expanding, becoming a critical component of modern transportation. Despite the increased attention on its security, our research shows that even devices previously examined in competitions such as Pwn2Own can still hide impactful vulnerabilities.

We picked up this device right after Pwn2Own results were announced and the competition was over - and quickly found that the story was far from finished. Our security analysis of this commercially available Phoenix Contact CHARX SEC-3000 EV charging station controller uncovered serious, previously unknown issues that had gone unnoticed during the event. By combining firmware analysis with emulation techniques, we identified several critical vulnerabilities (including OS Injection) affecting the device. We will walk through the approaches, challenges, and what we have learned.