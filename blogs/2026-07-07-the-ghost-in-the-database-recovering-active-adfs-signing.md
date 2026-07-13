---
title: "The ‘Ghost’ in the Database: Recovering Active ADFS Signing Keys via Machine DPAPI"
url: "https://cloud.google.com/blog/topics/threat-intelligence/recovering-active-adfs-signing-keys-machine-dpapi/"
date: "2026-07-07"
author: "Mandiant"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
Written by: Shebin Mathew Introduction The "Golden SAML" technique, first described by CyberArk researchers in 2017, and further detailed by Mandiant researchers in 2021 , remains one of the most effective methods for threat actors to forge identity assertions in the Microsoft ecosystem. By obtaining the private key of an ADFS token-signing certificate, an attacker can authenticate as any user to any SAML-federated application, bypassing multifactor authentication (MFA), conditional access, and all identity-based controls. However, during a recent red team engagement, Mandiant discovered that 
