---
layout: talk
title: Create Yourself a Botnet With These Zero Days
duration: 45 
scheduled: "13:20"
speakers: 
  -  name: Idar Lund
     image: IdarLund.png
     bio: |
      Idar Lund is a Principal Ethical Hacker at Telenor Cyberdefence and currently as an ethical hacker, red-team member and architect. He has over 15 years of experience as an IT-security professional. He also has long relationship with the Norwegian Armed Forces and participation in International operations.

      Idar began his career as a developer and then he moved on to security through a position in a Security Operation Center (SOC). He has operational and strategic experience in security by building and managing a SOC and has also helped out in ensuring that the elections in Norway are conducted securely. Idar has been a member of offensive security teams since 2017 and in 2023 transitioned to specialize in this field by utilizing previous Blue Team, infrastructure and architecture knowledge.

      Idar is also a member of the GIAC Advisory Board. Invitations are extended to GIAC certified professionals who demonstrate exemplary performance on GIAC exams. Members are often consulted as subject-matter experts for content-related issues in various GIAC program needs.

      Further, he has won three SANS competitions; NetWars Core and the CTF for SEC560: Enterprise Penetration Testing in London 2024 and during COVID lockdown in 2021 he won SEC504: Hacker Tools, Techniques, and Incident Handling CTF.

      Idar usually says he do't have a job. He's got a hobby that he gets paid to do.
     socials:
---
In this talk, Idar will show his research on a "smart garage door" opener. The intended use of the garage opener is to have an app on your phone and open/close it from there over the internet. What can possibly go wrong?

We will have a look at how the garage door opener is built, how to extract the software from it, static analysis of PHP source code, find several vulnerabilities, develop exploits for them and take a look on the infrastructure that are backing this device. Further we will have a look on how to find these devices online.

With this knowledge, one can use this chain of zero-days to create a 3-4k node botnet, open other's garage doors, brick devices or whatever else floats your boat.

And yes, this is actual zero-days. The device is unfortunately EoL and the company behind it has abandoned it.