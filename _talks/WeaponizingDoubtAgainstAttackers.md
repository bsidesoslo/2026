---
layout: talk
title: "Trust Nothing: Weaponizing Doubt Against Attackers"
duration: 45 
scheduled: "09:45"
speakers: 
  -  name: André Lima
     image: AndreLima.png
     bio: |
       André Lima is the Red Team Leader at Telenor CyberDefence, doing cyber security testing since 2011, in Portugal, Australia, and now settled in Oslo.
       
       He is also a researcher and tries to publish as often as possible at his [Youtube channel](https://www.youtube.com/@0x4ndr3), and [blog](https://0x4ndr3.github.io/), while also doing presentations at [cyber security conferences](https://github.com/0x4ndr3/Presentations).
       
       His main areas of expertise are reverse engineering, exploit development, and malware development with a focus on EDR bypasses.
       
       When not working, he enjoys playing basketball, tennis, or simply watching Formula 1.
     socials:
      - type: twitter
        url: https://x.com/0x4ndr3
      - type: linkedin
        url: https://www.linkedin.com/in/aflima/
---
Attackers rely on one thing the moment they land in your network: that what they see is real. Credentials look like credentials. File shares look like file shares. That trust is their single greatest weakness — and most defenders never exploit it.

In 1943, a corpse carrying fake invasion plans redirected the German army and helped turn World War II. The principle behind Operation Mincemeat — feed the adversary convincing lies and let them defeat themselves — is one of the most underused tools in modern cybersecurity.

This talk shows how to build a practical deception stack that turns every step of an intrusion into a tripwire. We'll move from zero to a working deployment using accessible, mostly free technologies: 

 * canary tokens that fire the instant a decoy is touched
 * ProjFS-backed phantom filesystem that fabricates enticing files on demand 
 * SSH and RDP honeypots that capture attacker behavior
 * Microsoft Defender for Identity honey tokens that catch credential theft inside Active Directory. 
 
 Every layer is demonstrated live, with detection logic and real telemetry.
Defenders spend most of their budget trying to keep attackers out. This is about what happens after they get in — and how to make sure they trip an alarm before they reach anything that matters.