---
layout: talk
title: "Ghosts in the Cluster - Hiding in Kubernetes for Years"
duration: 45 
scheduled: "10:50"
speakers: 
  -  name: Rory McCune
     image: RoryMcCune.png
     bio: |
       Rory has worked in the cyber security arena for the last 26 years in a variety of roles. These days he spends his work time on container and cloud native security as a senior security researcher and advocate for Datadog. 
       
       He is an active member of the container security community having delivered presentations at a variety of conferences including RSA and OWASP Appsec EU. 
       
       He has also presented at major containerization conferences such as Kubecon EU and is an author of the CIS Benchmarks for Docker and Kubernetes and member of Kubernetes SIG-Security.
     socials:
       - type: linkedin
         url: https://www.linkedin.com/in/rorym/
       - type: mastodon
         url: https://infosec.exchange/@raesene
       - type: bluesky
         url: https://bsky.app/profile/mccune.org.uk
---
You've popped a Kubernetes cluster. You've got admin creds. Now the real question is how do you stay? Kubernetes abstracts away enormous complexity across multiple layers, from container runtimes to cluster APIs and each of those layers has dark corners where an attacker can set up shop and go unnoticed for months or even years.

This talk is a post-exploitation deep dive into Kubernetes persistence. We'll walk through a compromised cluster layer by layer, demonstrating how attackers can escape to cluster nodes, spin up containers invisible to kubectl, abuse the Kubelet API to dodge audit logging and admission control, and create phantom credentials that survive long after the initial breach is forgotten. 

If defenders aren't watching every layer of the stack, they won't see you coming - or going.